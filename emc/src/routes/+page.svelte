<script>
	import Logo from '../components/icons/Logo.svelte';

	let links = {
		Home: '/',
		About: '/About'
	};

	console.log({ links });
</script>

<div>
	<!-- hero section -->
	<div class="hero">
		<section class="hero-text">
			<!-- navigation -->
			<nav>
				<a href="/">
					<Logo />
				</a>

				<ul>
					<!-- fix this ASAP -->
					{#each links as link}
						<li><a href={link.value}>{link.key}</a></li>
					{/each}
				</ul>
			</nav>
			<!-- hero text -->
			<h1 class="">Explore Your dream extraterrestrial escape</h1>
			<p>
				Gather your imagination and bring it to life with our outer-worldly experiences. We bring
				adventure and escape to your fingertips. See what we have to offer.
			</p>
		</section>

		<!-- search bar -->
	</div>
</div>

<style>
	* {
		padding: 0;
		margin: 0;
		box-sizing: border-box;
	}

	.hero {
		width: 100%;
		height: 100lvh;
		background: url('../1.png');
		background-position: center;
		background-size: cover;
		position: relative;
		display: grid;
		grid-template-columns: repeat(12, 1fr);
		grid-template-rows: repeat(12, 1fr);
	}

	.hero:after {
		position: absolute;
		background-color: black;
		content: '';
		top: 0;
		left: 0;
		width: 100%;
		height: 100%;
		opacity: 40%;
	}

	.hero-text {
		grid-column: 1/-1;
		grid-row: 1/5;
		background-color: #a8a598;
		display: subgrid;
	}

	.hero-text > h1 {
		text-transform: uppercase;
		font-size: 1.6em;
		text-align: center;
		letter-spacing: 1.1em;
		color: white;
		/* grid-column: 3/10;
		grid-row: 3/5; */
	}

	.hero-text > p {
		color: white;
		/* grid-column: 4/9;
		grid-row: 3/5; */
	}

	nav {
		grid-column: 3/8;
		grid-row: 1/2;
	}

	ul {
		background-color: #a8a598;
	}

	li a {
		font-size: 3em;
	}
</style>
