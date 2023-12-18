<script lang="ts">
	import Benefit from 'components/Benefit.svelte';
</script>

<div class="section">
	<h2 class="section-title">What do we have to offer?</h2>
	<p class="description">
		This <b>year-long</b> program accelerates learning for high school juniors and seniors with
		<b>IT experience</b>, guiding them towards advanced education and <b>IT careers</b>. Aligned
		with the national <b>IT Competency Model</b>, it focuses on foundational, technical, and
		job-specific skills through internships. Our <b>2023-2024</b> cohort features
		<b>30 Grade 11 & 12 students</b> poised for success.
	</p>
	<img class="image" src="/assets/cat-bread.png" alt="cat eating bread placeholder." />
</div>

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

<style lang="scss">
	.section {
		margin-left: 180px;
		margin-top: 80px;
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
