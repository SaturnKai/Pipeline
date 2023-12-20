<script lang="ts">
	import BenefitsSection from 'components/BenefitsSection.svelte';
import SectionTitle from 'components/SectionTitle.svelte';
</script>

<svelte:head>
	<title>Home | IT Workforce Pipeline</title>
</svelte:head>

<div class="hero">
	<div class="content">
		<img class="logo" src="/assets/brand/unlv.png" alt="UNLV logo." draggable="false" />
		<h1 class="title">IT Workforce Talent<br />Pipeline Project</h1>
		<p class="subtitle">Young Minds, Bright Futures.</p>
	</div>
	<div class="media">
		<img src="/assets/img/main-image.png" alt="main." draggable="false" />
	</div>
</div>

<div class="section">
	<div>
		<h2 class="section-title">What do we have to offer?</h2>
		<p class="description">
			This <b>year-long</b> program accelerates learning for high school juniors and seniors with
			<b>IT experience</b>, guiding them towards advanced education and <b>IT careers</b>. Aligned
			with the national <b>IT Competency Model</b>, it focuses on foundational, technical, and
			job-specific skills through internships. Our <b>2023-2024</b> cohort features
			<b>30 Grade 11 & 12 students</b> poised for success.
		</p>
	</div>
	<div>
		<img
			class="image"
			src="/assets/img/cat-bread.png"
			alt="cat eating bread placeholder."
			draggable="false"
		/>
	</div>
</div>

<BenefitsSection></BenefitsSection>

<SectionTitle>Our Sponsors</SectionTitle>
<div class="sponsors">
	<div class="sponsors-row">
		<img src="/assets/img/sponsors/ccsd.png" alt="ccsd" />
		<img src="/assets/img/sponsors/cte.png" alt="cte" />
		<img src="/assets/img/sponsors/comptia.png" alt="comptia" />
		<img src="/assets/img/sponsors/city-north-las-vegas.svg" alt="city of las vegas" />
		<img src="/assets/img/sponsors/water-district.png" alt="water district" />
	</div>
	<div class="sponsors-row">
		<img src="/assets/img/sponsors/osit.png" alt="osit" />
		<img src="/assets/img/sponsors/codingscape.png" alt="codingscape" />
		<img src="/assets/img/sponsors/aristocrat.png" alt="aristocrat" />
		<img src="/assets/img/sponsors/unlv.png" alt="unlv" />
	</div>
</div>

<style lang="scss">
	.sponsors {
		margin-top: 40px;
		margin-bottom: 80px;
	}

	.sponsors-row {
		display: flex;
		flex-wrap: wrap;
		align-items: center;
		justify-content: center;
		gap: 40px;
		max-width: 80vw;
		margin: 0 auto;
	}

	.sponsors-row img {
		filter: saturate(0) contrast(0.75);
		opacity: 0.75;
		transition: 100ms ease;
		width: 150px;
		height: 150px;
		object-fit: contain;

		&:hover {
			filter: saturate(1);
			opacity: 1;
		}
	}

	.section {
		display: flex;
		justify-content: space-between;
		align-items: center;
		margin: 4em 0 4em 0;
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

	.subtitle {
		font-weight: 500;
		color: #848484;
	}

	.description {
		line-height: 1.8;
		max-width: 500px;
	}

	.image {
		width: 200px;
		border-radius: 8px;
		box-shadow: 5px 5px 15px 8px rgba($color: #000000, $alpha: 0.25);
		transform: rotate(10deg);
	}

	.hero {
		display: flex;
		justify-content: space-between;
		align-items: center;
		padding: 4em 0 4em 0;
	}

	.hero > .content > .logo {
		height: 2rem;
		margin-bottom: 1em;
	}

	.hero > .content > .title {
		font-size: 2.5rem;
		margin-bottom: 0.5em;
	}

	.hero > .media img {
		border-radius: 1rem;
		max-height: 350px;
	}
</style>
