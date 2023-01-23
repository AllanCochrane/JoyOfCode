<script lang="ts">
	import { onDestroy, onMount } from 'svelte';

	onMount(() => {
		console.log('Mounted posts page');
	});
	onDestroy(() => {
		console.log('Destroyed posts page');
	});
</script>

<h1>Posts page</h1>

<style>
	h1 {
		color: aqua;
	}
</style>
