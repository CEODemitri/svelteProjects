<script>
	import Flight from '../components/icons/Flight.svelte';
	import Hotel from '../components/icons/Hotel.svelte';
	import Logo from '../components/icons/Logo.svelte';
	import Location from '../components/icons/Location.svelte';
	import Down from '../components/icons/Down.svelte';
</script>

<div>
	<div class="home">
		<header>
			<nav class="flex">
				<a href="/" class="flex">
					<Logo />
					<p>emc</p>
				</a>

				<section class="flex">
					<ul class="flex">
						<li>Home</li>
						<li>About</li>
						<li>Flights</li>
						<li>Stay</li>
					</ul>

					<div class="flex">
						<p>Find Deals</p>
						<button>Sign In</button>
					</div>
				</section>
			</nav>
		</header>

		<section>
			<div>
				<h1><span>E</span>xplore Your Dream <span>E</span>xtraTerrestrial <span>E</span>scape</h1>
				<p>
					Gather your imagination and bring it to life with our outer-worldly experiences. We bring
					adventure and escape to your fingertips. See what we have to offer.
				</p>
			</div>
		</section>

		<section>
			<ul class="tabs">
				<li>
					<span class="svg"><Hotel /></span>
					<p>Stay</p>
				</li>
				<li>
					<span class="svg"><Flight /></span>
					<p>Flights</p>
				</li>
			</ul>
			<div class="bar">
				<article>
					<section>
						<h1>
							<p>Location</p>
							<span><Location /></span>
						</h1>
						<p>Destination</p>
					</section>
					<section><a href=""></a></section>
				</article>
				<article>
					<section>
						<h1>
							<p>Leaving</p>
							<span><Down /></span>
						</h1>
						<p>Depature</p>
					</section>
					<section><a href=""></a></section>
				</article>
				<article>
					<section>
						<h1>
							<p>Returning</p>
							<span><Down /></span>
						</h1>
						<p>Arrival</p>
					</section>
					<section><a href=""></a></section>
				</article>
				<article>
					<section>
						<h1>
							<p>Guests</p>
							<span><Down /></span>
						</h1>
						<p>Total</p>
					</section>
					<section><a href=""></a></section>
				</article>
				<button class="search">Search</button>
			</div>
		</section>
	</div>

	<div class="popular"></div>
</div>

<style>
	* {
		margin: 0;
		padding: 0;
		box-sizing: border-box;
	}

	/* utility */
	.flex {
		display: flex;
	}

	button {
		padding: 5px 2em;
		font-size: 1rem;
	}

	/* hero start */

	.home {
		height: 90vh;
		min-height: 600px;
		background: url('../landing.png');
		background-size: 100% 100%;
		background-repeat: no-repeat;
		color: white;
		font-family: 'Josefin Sans', sans-serif;
		display: flex;
		flex-direction: column;
		gap: 15vh;

		padding: 1em 3em;
	}

	.home * {
		position: relative;
		z-index: 2;
	}

	nav {
		align-items: center;
		gap: 4em;
	}

	nav > a {
		align-items: center;
		text-decoration: none;
		gap: 0.4em;
	}

	a > p {
		font-size: 1.5em;
		text-decoration: none;
		color: white;
	}

	ul {
		gap: 2.3em;
		list-style: none;
		color: #a6a6a6;
	}

	ul > li:hover {
		color: aliceblue;
		text-decoration: underline;
		transform: scale(115%);
	}

	@media (max-width: 760px) {
		ul > li {
			display: none;
		}
	}

	nav > section {
		width: 83%;
		justify-content: space-between;
		align-items: center;
	}

	nav > section > div {
		gap: 1em;
		justify-content: space-between;
		align-items: center;
	}

	button {
		width: fit-content;
		padding: 0.4em 1em;
		border: none;
		border-radius: 0.3em;
		background-color: #185fb2;
		color: aliceblue;
		letter-spacing: 0.3em;
		font-family: 'Racing Sans One', sans-serif;
	}

	/* nav bar style end */

	/* hero section begin */

	h1 {
		font-family: 'Racing Sans One', sans-serif;
		font-size: clamp(2em, 6vh, 6em);
		width: 75%;
		letter-spacing: 0.1em;
		text-shadow: -10px -10px -2px rgba(0, 0, 0, 0.5);
		text-overflow: ellipsis;
	}

	h1 > span {
		color: #f5db51;
	}

	h1 + p {
		width: 65%;
		font-size: larger;
		color: #a6a6a6;
		line-height: 1.5em;
		margin-top: 1.3em;
	}

	/* hero ends */

	/* cta begins */
	.home > section:last-of-type {
		width: 90%;
		height: 13vh;
		margin: 0 auto;
		anchor-name: --cta;
	}

	@media (max-width: 600px) {
		.home > section:last-of-type {
			display: none;
		}
	}

	.home > section:last-of-type > ul {
		width: fit-content;
		display: flex;
		font-weight: bold;
		height: 4em;
		z-index: -100;
		gap: 0;
		position: relative;
		top: 1em;
	}

	.home > section:last-of-type > ul > li:first-of-type {
		background-color: #185fb2;
		padding: 1em 3em;
		color: white;
		border-radius: 16px 16px 0 0;
	}

	.home > section:last-of-type > ul > li:last-of-type {
		background-color: #a6a6a660;
		padding: 0.4em 3em;
		color: rgb(34, 34, 34);
		border-radius: 16px 16px 0 0;
	}

	.tabs > li {
		display: flex;
		gap: 5px;
		justify-content: center;
		align-items: center;
	}

	.svg {
		font-size: 1.52em;
		fill: currentColor;
	}

	.home > section:last-of-type > div {
		display: flex;
		height: 100%;
		justify-content: space-around;
		align-items: center;
		text-align: left;
		background-color: #395a7d9a;
		border-radius: 1.3em;
		z-index: 100;
		backdrop-filter: blur(50px);
		-ms-filter: blur(4px);
		-moz-filter: blur(4px);
		-webkit-backdrop-filter: blur(09px);
	}

	.search {
		font-size: 1.3em;
	}

	.home > section:last-of-type > div > article > section > h1 {
		color: black;
		font-size: 1rem;
		display: flex;
		gap: 0.4em;
		align-items: center;
	}

	article > section > p {
		color: black;
		font-size: 0.8rem;
		text-align: center;
	}

	.popular {
		height: 90vh;
	}
</style>
