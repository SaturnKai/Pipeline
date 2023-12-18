<script lang="ts">
	import Navbar from 'components/Navbar.svelte';
	import Footer from 'components/Footer.svelte';
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
