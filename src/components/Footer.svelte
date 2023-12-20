<div class="container">
	<div class="footer">
		<div class="columns">
			<div class="column brand">
				<img src="/assets/brand/logo.png" alt="" />
			</div>
			<div class="column">
				<h4>News</h4>
				<a href="/#">Instagram</a>
				<a href="/#">Twitter</a>
			</div>
			<div class="column">
				<h4>Program</h4>
				<a href="/#">Student Showcase</a>
				<a href="/#">Upcoming Events</a>
				<a href="/apply">Application</a>
				<a href="/about">About</a>
			</div>
			<div class="column">
				<h4>UNLV</h4>
				<a target="_blank" href="https://www.unlv.edu/">Website</a>
				<a href="tel:+17028953011">Phone</a>
				<a target="_blank" href="https://www.unlv.edu/parking">Parking</a>
				<a target="_blank" href="https://www.unlv.edu/maps/campus">Map</a>
			</div>
		</div>
		<div class="extra">
			<p class="copyright">
				<a href="https://www.unlv.edu/about/copyright">&copy; 2023 UNLV</a>
				<span>Produced by Ohlin Arellano and Brandon Gardenhire</span>
			</p>

			<a href="https://www.unlv.edu/">
				<img class="logo" src="/assets/brand/unlv-black.png" alt="UNLV Logo" />
			</a>
		</div>
	</div>
</div>

<style lang="scss">
	.container {
		width: 100%;
		background-color: var(--dark);
		height: fit-content;
		display: flex;
		justify-content: center;
		padding: 2em 0 2em 0;
	}

	.container * {
		color: var(--subheading);
	}

	.column a {
		color: #eee;
		margin-top: 0.5em;
		text-decoration: none;
		display: block;
	}

	.column a:hover {
		color: var(--primary);
	}

	.footer {
		display: flex;
		flex-direction: column;
		width: 100%;
		max-width: var(--site-max-width);
		padding: 0 1.75em 0 1.75em;
	}

	.columns {
		display: flex;
		justify-content: space-between;
		width: 100%;
	}

	.column {
		width: fit-content;
		padding: 1.75em;
	}

	.column h4,
	.column a {
		font-weight: 500;
	}

	.brand img {
		filter: invert(1);
	}

	.extra {
		display: flex;
		justify-content: space-between;
		align-items: center;
		padding: 2em 1.75em 0 1.75em;
	}

	.copyright * {
		text-decoration: none;
	}

	.copyright a {
		color: var(--subheading);
	}

	.copyright span {
		font-weight: 400;
		color: var(--text);
		margin-left: 1em;
	}

	.logo {
		height: 2rem;
		filter: invert(1);
	}
</style>
