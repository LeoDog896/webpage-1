<script lang="ts">
	import './style.css';
	import Header from '$lib/Header.svelte';
	import Footer from '$lib/Footer.svelte';
</script>

<Header />
<main>
	<slot />
</main>
<Footer />
