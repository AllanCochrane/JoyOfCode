<script lang="ts">
	import { onDestroy, onMount } from 'svelte';

	let a = 2;
	console.log(`Hello ${a}`);
	onMount(() => {
		console.log('Mounted home page');
	});
	onDestroy(() => {
		console.log('Destroyed home page');
	});
</script>

<h1>Home page</h1>
