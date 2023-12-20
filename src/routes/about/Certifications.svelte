<script lang="ts">
	import SectionTitle from 'components/SectionTitle.svelte';
</script>

<SectionTitle>Certifications</SectionTitle>
<div class="certifications">
	<div class="certifications-row">
		<img src="/assets/img/certs/aws.webp" alt="AWS Cloud Practitioner">
		<img src="/assets/img/certs/itfundamentals.webp" alt="AWS Cloud Practitioner">
		<img src="/assets/img/certs/aplus.webp" alt="AWS Cloud Practitioner">
		<img src="/assets/img/certs/networkplus.webp" alt="AWS Cloud Practitioner">
	</div>
	<div class="certifications-row">
		<img src="/assets/img/certs/cloudplus.webp" alt="AWS Cloud Practitioner">
		<img src="/assets/img/certs/securityplus.webp" alt="AWS Cloud Practitioner">
	</div>
</div>

<style lang="scss">
	.certifications {
		margin: 25px 0 50px 0;
	}

	.certifications-row {
		display: flex;
		gap: 1rem;
		justify-content: center;
		margin-bottom: 20px;
	}

	.certifications-row img {
		width:100px;
		height: 100px;
	}
</style>