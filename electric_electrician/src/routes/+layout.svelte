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

			<p>Electric Electrician</p>
		</nav>
	</header>
	<main>
		<slot />
	</main>
</div>

<style></style>
