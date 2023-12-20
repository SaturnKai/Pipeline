<script lang="ts">
	export let title: string;
	export let image: string;
</script>

<div class="hero">
	<div class="content">
		<h1 class="title">{title}</h1>
		<p class="description">
            <slot></slot>
        </p>
	</div>
	<div class="media">
		<img src="{image}" alt="main." draggable="false" />
	</div>
</div>

<style lang="scss">
    .hero {
		display: flex;
		justify-content: space-between;
		align-items: center;
		padding: 4em 0 4em 0;
	}

	.hero > .content > .title {
		font-size: 1.75rem;
		margin-bottom: 0.5em;
	}

	.hero > .content > .description {
		font-size: 1.25rem;
		margin-bottom: 0.5em;
        color: #4E4E4E;
	}

	.hero > .media img {
		border-radius: 1rem;
		max-height: 350px;
	}
</style>