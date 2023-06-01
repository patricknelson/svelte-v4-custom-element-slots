<svelte:options
	customElement={{
		tag: 'example-no-shadow-default',
		shadow: 'none',
	}}
/>

<h2>shadow: 'none' (default slot)</h2>
<p>Default slot:</p>
<slot><p>Fallback content 1</p></slot>

<style>
	p {
		background-color: azure;
	}
</style>
