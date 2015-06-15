##  The Rules

<ol>
<li class="fragment" data-fragment-index="0">Operate on field collections after node save, otherwise the host entity is not set</li>
<li class="fragment" data-fragment-index="1">Operate recursively, if a field collection is an entity, use a helper function that operates on an entity, not a node.</li>
<li class="fragment" data-fragment-index="2">Prefix helper functions with underscores</li>
<li class="fragment" data-fragment-index="3">Don’t be afraid to repeat yourself. Recursion happens afterwards.</li>
<li class="fragment" data-fragment-index="4">Don’t overwrite variable names in recursion (or do so with caution)</li>
<li class="fragment" data-fragment-index="5">If you can write sql queries to fix field collections, do it</li>
</ol>
