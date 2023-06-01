<!-- Redundant if using the create_custom_element() workaround (see main.js) -->
<svelte:options
	customElement={{
		tag: 'example-no-shadow',
		shadow: 'none',
	}}
/>

<div class="wrap">
	<h1>Shadow: none</h1>
	<slot name="example">Placeholder</slot>
</div>

<style>
	.wrap {
		border: 1px dotted red;
	}
</style>
