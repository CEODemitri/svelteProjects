<script>
	const links = [
		{ href: '/', text: 'Home' },
		{ href: '/about', text: 'About' },
		{ href: '/services', text: 'Services' },
		{ href: '/contact', text: 'Contact' }
	];
</script>

<div class="app">
	<header>
		<nav>
			<ul>
				{#each links as link}
					<li><a href={link.href}>{link.text}</a></li>
				{/each}
			</ul>

			<p class="logo">Electric Electrician</p>
		</nav>
	</header>
	<main>
		<slot />
	</main>
</div>

<style>
	ul {
		list-style: none;
		display: flex;
		gap: 1rem;
		padding: 0;
	}

	nav {
		display: flex;
		justify-content: space-between;
		align-items: center;
		background-color: #f8f8f8;
		border-bottom: 1px solid #ccc;
	}

	.logo {
		font-size: 1.5rem;
		font-weight: bold;
		color: #333;
	}
</style>
