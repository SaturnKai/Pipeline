<nav>
    <div class="brand">
        <a href="/">
            <img src="/assets/brand/logo.png" alt="IT Workforce Talent Pipeline Project Logo">
        </a>
    </div>
    <div class="tabs">
        <div class="left">
            <a href="https://www.google.com">
                Showcase
            </a>
            <a href="https://www.google.com">
                Events
            </a>
            <a href="https://www.google.com">
                About
            </a>
        </div>
        <div class="right">
            <a href="https://www.google.com">
                Portal
            </a>
            <a class="special" href="https://www.google.com">
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
        height: 4rem;

        padding: 0 1.75em 0 1.75em;
        margin: 0 auto;

        user-select: none;
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
    }

    .tabs a:hover {
        color: var(--primary);
    }

    .tabs a.special {
        padding: 0.5rem 1rem 0.5rem 1rem;
        margin-left: 1rem;

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