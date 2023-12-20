<script lang="ts">
	export let title: string;
	export let iconName: string;
	export let iconColor: string;

	import Icon from './Icon.svelte';
</script>

<div class="benefit">
	<div class="icon">
		<Icon name={iconName} color={iconColor} />
	</div>
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
		margin-top: 0.4em;
	}

	.description {
		font-size: 0.9rem;
		color: #4e4e4e;
		margin-top: 1em;
		line-height: 1.5;
	}
</style>
