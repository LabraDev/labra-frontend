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
		--bg-color: #181825;
		--hr-color: #313244;
		--text-color: #cdd6f4;
		--crust: #11111b;
	}
	:global(*) {
    	margin: 0;
    	padding: 0;
  	}
	main {
		background-color: var(--bg-color);
		min-height: 100vh;
		color: var(--text-color);
	}
</style>