<script lang="ts">
	import '../app.css';
	import favicon from '$lib/assets/zenko_icon.svg';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

{@render children?.()}
