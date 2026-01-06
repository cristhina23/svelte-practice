<script lang="ts">
	import '../app.css';
	import '@drop-in/graffiti'
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>

<main class="max-w-7xl mx-auto p-4">

	{@render children()}
</main>
