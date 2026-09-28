<script lang="ts">
	import favicon from '$lib/assets/favicon.svg';
	import 'normalize.css/normalize.css';
	import 'fontawesome-free/css/all.min.css';
	import 'bulma/css/bulma.min.css';
	import '../app.css';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

{@render children()}
