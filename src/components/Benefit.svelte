<script lang="ts">
	export let title: string;
	export let color: string;
</script>

<div class="benefit">
	<svg
		xmlns="http://www.w3.org/2000/svg"
		viewBox="0 0 24 24"
		fill="none"
		stroke="currentColor"
		stroke-width="2"
		stroke-linecap="round"
		stroke-linejoin="round"
		class="icon lucide lucide-graduation-cap"
		style="stroke: {color};"
		><path d="M22 10v6M2 10l10-5 10 5-10 5z" /><path d="M6 12v5c3 3 9 3 12 0v-5" /></svg
	>
	<h2 class="title">{title}</h2>
	<p class="description"><slot /></p>
</div>

<style lang="scss">
	.benefit {
		background: #fbfbfb;
		border: 1px solid #ededed;
		border-radius: 10px;
		padding: 1em 1.2em;
		width: 350px;
		transition: background 100ms ease;

		&:hover {
			background: #f4f4f4;
		}
	}

	.icon {
		width: 2.2rem;
	}

	.title {
		font-size: 1.1rem;
		margin-top: 0.3em;
	}

	.description {
		font-size: 0.9rem;
		color: #4e4e4e;
		margin-top: 1em;
		line-height: 1.5;
	}
</style>
