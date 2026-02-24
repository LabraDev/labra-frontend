<script lang="ts">
	import favicon from '$lib/assets/favicon.svg';
    import Header from '$lib/components/header.svelte';
    import Footer from '$lib/components/footer.svelte';

</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

<Header />
<!-- svelte-ignore slot_element_deprecated -->
<main><slot /></main>
<Footer />

<style>
	:root {
		--bg-color: #0d001a;
		--hr-color: #241236;
	}
	:global(*) {
    	margin: 0;
    	padding: 0;
  	}
	main {
		background-color: var(--bg-color);
		min-height: 100vh;
		color: white;
	}
</style>