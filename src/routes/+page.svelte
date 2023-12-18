<script lang="ts">
	import Benefit from 'components/Benefit.svelte';
	import SectionTitle from 'components/SectionTitle.svelte';
</script>

<div class="hero">
	<div class="content">
		<img class="logo" src="/assets/brand/unlv.png" alt="UNLV logo." draggable="false" />
		<h1 class="title">IT Workforce Talent<br>Pipeline Project</h1>
		<p class="subtitle">Young Minds, Bright Futures.</p>
	</div>
	<div class="media">
		<img src="/assets/img/main-image.png" alt="main." draggable="false" />
	</div>
</div>

<div class="section">
	<div class="c1">
		<h2 class="section-title">What do we have to offer?</h2>
		<p class="description">
			This <b>year-long</b> program accelerates learning for high school juniors and seniors with
			<b>IT experience</b>, guiding them towards advanced education and <b>IT careers</b>. Aligned
			with the national <b>IT Competency Model</b>, it focuses on foundational, technical, and
			job-specific skills through internships. Our <b>2023-2024</b> cohort features
			<b>30 Grade 11 & 12 students</b> poised for success.
		</p>
	</div>
	<div class="c2">
		<img
			class="image"
			src="/assets/img/cat-bread.png"
			alt="cat eating bread placeholder."
			draggable="false"
		/>
	</div>
</div>

<SectionTitle>Benefits</SectionTitle>
<div class="benefits">
	<div class="benefits-row">
		<Benefit title="Training and Credits" color="var(--primary)">
			Technical & employability skills training, resulting in <b>6 UNLV</b> credits and
			<b>1 high school</b> credit.
		</Benefit>
		<Benefit title="Mentorship and Tutoring" color="var(--secondary)">
			Online assistance with <b>course material</b> and <b>general questions</b>.
		</Benefit>
		<Benefit title="Interview and Internships" color="var(--primary)">
			A <b>guaranteed interview</b> for program completers, including a <b>full-time paid</b> internship.
		</Benefit>
	</div>
	<div class="benefits-row">
		<Benefit title="Paid Certification Fees" color="var(--secondary)">
			Technical & employability skills training, resulting in <b>6 UNLV</b> credits and
			<b>1 high school</b> credit.
		</Benefit>
		<Benefit title="Full-Time Summer Internship" color="var(--primary)">
			Online assistance with <b>course material</b> and <b>general questions</b>.
		</Benefit>
		<Benefit title="Over 4,000$ in Value" color="var(--secondary)">
			A <b>guaranteed interview</b> for program completers, including a <b>full-time paid</b> internship.
		</Benefit>
	</div>
</div>

<style lang="scss">

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

	.benefits {
		margin-top: 50px;
		margin-bottom: 100px;
	}

	.benefits-row {
		display: flex;
		gap: 1rem;
		justify-content: center;
		margin-bottom: 20px;
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
		margin-bottom: 0.5em;
	}

	.hero > .media img {
		border-radius: 1rem;
		max-height: 350px;
	}
</style>
