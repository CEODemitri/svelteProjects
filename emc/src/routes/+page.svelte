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
		grid-row: 1/6;
		background-color: #a8a598;
		opacity: 48%;
		filter: blur(1px);
		display: subgrid;
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
