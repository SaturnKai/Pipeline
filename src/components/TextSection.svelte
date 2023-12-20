<script lang="ts">
	export let title: string;
</script>

<div class="section">
	<h2 class="section-title">{title}</h2>
	<p class="description">
		<slot></slot>
	</p>
</div>

<style lang="scss">
    .section {
		display: flex;
		justify-content: space-between;
		flex-direction: column;
		align-items: left;
		margin: 0 0 4em 0;
	}

	.section-title {
		margin-bottom: 20px;
		position: relative;

		&::before {
			content: '';
			position: absolute;
			width: 3px;
			height: 28px;
			background: #b01f24;
			transform: translateX(-20px);
		}
	}

    .description {
		line-height: 1.8;
	}

</style>