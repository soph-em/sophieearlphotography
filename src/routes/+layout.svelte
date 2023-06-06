<script>
	// import Header from './header.svelte';
	// import '../app.css';
</script>

<nav>
	<!-- <Header /> -->
</nav>
<slot />

<style>
	:global(body) {
		margin: 0;
	}
	:global(p, h1, h2, h3) {
		font-family: 'Montserrat', sans-serif;
	}
</style>
