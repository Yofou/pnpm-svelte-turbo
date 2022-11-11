<script lang="ts">
	let count = 0;

	const inc = () => count++;
	const dec = () => count--;
</script>

<div>
	<button on:click={dec}>dec</button>
	<p>{count}</p>
	<button on:click={inc}>inc</button>
</div>

<style>
	div {
		display: flex;
	}
</style>
