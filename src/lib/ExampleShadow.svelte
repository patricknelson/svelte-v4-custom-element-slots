<!-- Redundant if using the create_custom_element() workaround (see main.js) -->
<svelte:options
	customElement={{
		tag: 'example-shadow',
		shadow: 'open',
	}}
/>

<div class="wrap">
	<h1>Shadow: open</h1>
	<slot name="example">Placeholder</slot>
</div>

<style>
	.wrap {
		border: 1px dotted red;
	}
</style>
