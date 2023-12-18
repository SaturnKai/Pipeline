<nav>
    <div class="brand">
        <a href="/">
            <img src="/assets/brand/logo.png" alt="IT Workforce Talent Pipeline Project Logo">
        </a>
    </div>
    <div class="tabs">
        <div class="left">
            <a href="/showcase">
                Showcase
            </a>
            <a href="/events">
                Events
            </a>
            <a href="/roadmap">
                Roadmap
            </a>
            <a href="/about">
                About
            </a>
        </div>
        <div class="right">
            <a href="/portal">
                Portal
            </a>
            <a class="special" href="/apply">
                Apply
            </a>
        </div>
    </div>
</nav>

<style lang="scss">

    nav {
        display: flex;
        justify-content: space-between;
        align-items: center;

        max-width: var(--site-max-width);
        height: 5rem;

        padding: 0 3.5em 0 3.5em;
        margin: 0 auto;

        user-select: none;
    }

    .brand a, .brand img {
        height:28px;
        width:28px;
    }

    .brand {
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .tabs {
        width: 100%;
        display: flex;
        justify-content: space-between;

        padding-left: 2em;
    }

    .tabs a {
        text-decoration: none;
        color: var(--heading);

        padding: 0.5em;
        font-weight: 500;
        font-size: 0.9rem;
    }

    .tabs a:hover {
        color: var(--primary);
    }

    .tabs a.special {
        padding: 0.5rem 1rem 0.5rem 1rem;
        margin-left: 0.5rem;

        font-weight: 600;

        border: 2px solid var(--container-stroke);
        border-radius: 2rem;
        transition: border-color 0.25s;
    }

    .tabs a.special:hover {
        color: var(--heading);
        border-color: var(--primary);
        transition: border-color 0.25s;
    }
</style>