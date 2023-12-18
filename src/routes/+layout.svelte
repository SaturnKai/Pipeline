<script lang="ts">
	import Navbar from 'components/Navbar.svelte';
	import Footer from 'components/Footer.svelte';
	import '../app.scss';
</script>

<header>
	<Navbar />
</header>
<main>
	<slot />
</main>
<footer>
	<Footer />
</footer>
