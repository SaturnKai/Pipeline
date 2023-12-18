<script lang="ts">
	import Navbar from 'components/Navbar.svelte';
	import Footer from 'components/Footer.svelte';
	import '../app.scss';
</script>

<header>
	<Navbar />
</header>
<main>
	<div class="layout">
		<slot />
	</div>
</main>
<footer>
	<Footer />
</footer>


<style lang="scss">
	.layout {
		max-width: var(--site-max-width);
		margin: 0 auto;
	}
	main, .layout {
		padding: 0 2.5em 0 2.5em;
	}
</style>