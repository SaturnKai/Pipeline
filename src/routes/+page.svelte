<script lang="ts">
	import Benefit from 'components/Benefit.svelte';
</script>

<div class="main-layout">
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
				src="/assets/cat-bread.png"
				alt="cat eating bread placeholder."
				draggable="false"
			/>
		</div>
	</div>

	<h2 class="benefits-title">Benefits</h2>
	<div class="separator" />
	<div class="benefits">
		<div class="benefits-row">
			<Benefit title="Training and Credits" color="#B01F24">
				Technical & employability skills training, resulting in <b>6 UNLV</b> credits and
				<b>1 high school</b> credit.
			</Benefit>
			<Benefit title="Mentorship and Tutoring" color="#888CBA">
				Online assistance with <b>course material</b> and <b>general questions</b>.
			</Benefit>
			<Benefit title="Interview and Internships" color="#B01F24">
				A <b>guaranteed interview</b> for program completers, including a <b>full-time paid</b> internship.
			</Benefit>
		</div>
		<div class="benefits-row">
			<Benefit title="Paid Certification Fees" color="#888CBA">
				Technical & employability skills training, resulting in <b>6 UNLV</b> credits and
				<b>1 high school</b> credit.
			</Benefit>
			<Benefit title="Full-Time Summer Internship" color="#B01F24">
				Online assistance with <b>course material</b> and <b>general questions</b>.
			</Benefit>
			<Benefit title="Over 4,000$ in Value" color="#888CBA">
				A <b>guaranteed interview</b> for program completers, including a <b>full-time paid</b> internship.
			</Benefit>
		</div>
	</div>
</div>

<style lang="scss">
	.main-layout {
		max-width: var(--site-max-width);
		margin: 0 auto;
	}

	.section {
		display: flex;
		justify-content: space-between;
		margin-top: 80px;
		margin-inline: 10px;
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

	.benefits-title {
		color: #777777;
	}

	.benefits {
		margin-top: 80px;
	}

	.benefits-row {
		display: flex;
		gap: 1rem;
		justify-content: center;
		margin-bottom: 20px;
	}
</style>
