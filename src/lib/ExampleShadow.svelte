<svelte:options
	customElement={{
		tag: 'example-shadow',
		shadow: 'open',
	}}
/>

<h2>shadow: 'open'</h2>
<p>Slot 1:</p>
<slot name="slot1"><p>Fallback content 1</p></slot>
<p>Slot 2:</p>
<slot name="slot2"><p>Fallback content 1</p></slot>

<style>
	p {
		background-color: azure;
	}
</style>
