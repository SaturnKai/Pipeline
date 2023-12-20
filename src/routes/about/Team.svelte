<script>
	import ProfileShot from "components/ProfileShot.svelte";
	import SectionTitle from "components/SectionTitle.svelte";

</script>

<SectionTitle>Meet the Team</SectionTitle>

<div class="team">
    <div class="row">
        <ProfileShot 
            name="Dr. Xue Xing" 
            title="Project Lead"
            photo="/assets/img/team/xue.webp" 
        />
        <ProfileShot 
            name="Dr. Yingtao Jiang" 
            title="Team Member"
            photo="/assets/img/team/yingtao.webp" 
        />
        <ProfileShot 
            name="Dr. Mei Yang" 
            title="Team Member"
            photo="/assets/img/team/mei.webp" 
        />
        <ProfileShot 
            name="Dr. Hasan Deniz" 
            title="Team Member"
            photo="/assets/img/team/hasan.webp" 
        />
        <ProfileShot 
            name="Dr. Sebern Coleman" 
            title="Team Member"
            photo="/assets/img/team/sebern.webp" 
        />
    </div>
    <div class="row">
        <ProfileShot 
            name="Snehal Bhakta" 
            title="Team Member"
            photo="/assets/img/team/snehal.webp" 
        />
        <ProfileShot 
            name="Jimmy Jacobson" 
            title="Team Member"
            photo="/assets/img/team/jimmy.webp" 
        />
        <ProfileShot 
            name="Craig von Collenberg" 
            title="Team Member"
            photo="/assets/img/team/craig.webp" 
        />
        <ProfileShot 
            name="Dr. Mihee Park" 
            title="Learning Coordinator"
            photo="/assets/img/team/mihee.webp" 
        />
    </div>
</div>


<style>
    .team {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        margin: 2em;
    }

    .row {
        display: flex;
        justify-content: center;
        align-items: center;
    }
</style>
