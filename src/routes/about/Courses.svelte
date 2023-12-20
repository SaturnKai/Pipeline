<script lang="ts">
	import Benefit from 'components/Benefit.svelte';
	import SectionTitle from 'components/SectionTitle.svelte';
</script>

<SectionTitle>College Courses</SectionTitle>
<div class="benefits">
	<div class="benefits-row">
		<Benefit title="CS135 - Computer Science" iconName="cpu" iconColor="var(--primary)">
			A <b>3-credit</b> course offered in the fall semester.
		</Benefit>
		<Benefit title="EDW135 - Employability Skills" iconName="briefcase" iconColor="var(--secondary)">
			A <b>3-credit</b> course offered in the spring semester.
		</Benefit>
	</div>
</div>

<style lang="scss">
	.benefits {
		margin: 25px 0 50px 0;
	}

	.benefits-row {
		display: flex;
		gap: 1rem;
		justify-content: center;
		margin-bottom: 20px;
	}
</style>