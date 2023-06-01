<svelte:options
	customElement={{
		tag: 'example-no-shadow-default',
		shadow: 'none',
	}}
/>

<h2>shadow: 'none' (default slot)</h2>
<p>Default slot:</p>
<slot><p>Fallback default content</p></slot>

<style>
	p {
		background-color: azure;
	}
</style>
