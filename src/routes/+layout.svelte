<script lang="ts">
	import Header from '$lib/components/Header/Header.svelte';
	import '../app.css';
</script>

<Header />

<main class="container mx-auto">
	<slot />
</main>
