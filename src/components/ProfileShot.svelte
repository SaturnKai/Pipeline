<script lang="ts">
	export let name: string;
	export let title: string;
	export let photo: string;
</script>

<div class="profile">
    <img src="{photo}" alt="Photo of {name}">
    <span class="name">{name}</span>
    <span class="title">{title}</span>
</div>

<style lang="scss">
    .profile {
        display:flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        width:fit-content;
        height: fit-content;
        margin: 1em;
    }

    .profile img {
        border-radius: 150%;
        width: 150px;
        height: 150px;
    }

    .name {
        color: var(--heading);
        font-weight: 500;
        font-size: 0.9rem;
        margin-top: 0.75em;
    }

    .title {
        color: var(--subheading);
        font-weight: 300;
        margin-top: 0.5em;
        margin-bottom: 0.5em;
        font-size: 0.8rem;
    }
</style>