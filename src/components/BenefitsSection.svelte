<script lang="ts">
	import Benefit from 'components/Benefit.svelte';
	import SectionTitle from 'components/SectionTitle.svelte';
</script>

<SectionTitle>Benefits</SectionTitle>
<div class="benefits">
	<div class="benefits-row">
		<Benefit title="Training and Credits" iconName="graduation-cap" iconColor="var(--primary)">
			Technical & employability skills training, resulting in <b>6 UNLV</b> credits and
			<b>1 high school</b> credit.
		</Benefit>
		<Benefit
			title="Mentorship and Tutoring"
			iconName="heart-handshake"
			iconColor="var(--secondary)"
		>
			Online assistance with <b>course material</b> and <b>general questions</b>.
		</Benefit>
		<Benefit title="Interview and Internships" iconName="file-check" iconColor="var(--primary)">
			A <b>guaranteed interview</b> for program completers, including a <b>full-time paid</b> internship.
		</Benefit>
	</div>
	<div class="benefits-row">
		<Benefit title="Paid Certification Fees" iconName="shield-check" iconColor="var(--secondary)">
			Technical & employability skills training, resulting in <b>6 UNLV</b> credits and
			<b>1 high school</b> credit.
		</Benefit>
		<Benefit title="Full-Time Summer Internship" iconName="building-2" iconColor="var(--primary)">
			Online assistance with <b>course material</b> and <b>general questions</b>.
		</Benefit>
		<Benefit
			title="Over $4,000 in Value"
			iconName="circle-dollar-sign"
			iconColor="var(--secondary)"
		>
			A <b>guaranteed interview</b> for program completers, including a <b>full-time paid</b> internship.
		</Benefit>
	</div>
</div>

<style lang="scss">
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
</style>