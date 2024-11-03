<div class="container grid grid-cols-12  grid-rows-12 gap-4 h-full">
	<article class="col-start-4 col-span-7 row-start-1 row-span-1 bg-blue-500">
		<h1>Hallo!</h1>
		<p>Welcome to My Portfolio of Sveltekit Project. Watch as I progress through Each Project.</p>
	</article>

	<!-- project Tab -->
	<aside class="col-start-1 col-span-3 row-start-1 row-span-full bg-red-400 flex flex-col gap-8">
		<!-- project listing prototype -->
		<article>
			<h2>Travel Business: EMC</h2>
			<p>Completion Percentage</p>
		</article>
		<article>
			<h2>Project Tile</h2>
			<p>Completion Percentage</p>
		</article>
		<article>
			<h2>Project Tile</h2>
			<p>Completion Percentage</p>
		</article>
		<article>
			<h2>Project Tile</h2>
			<p>Completion Percentage</p>
		</article>
	</aside>

	<main class="col-start-4 col-span-7 row-start-2 row-span-11">
		<!-- project listing -->
		 <a href="../../../../emc/src/routes/+page.svelte">
			<article class="card p-4 bg-[url('/projectBG/emc.png')] h-1/3 w-2/5 bg-cover rounded-md">
			<h3>Travel Porftolio: EMC</h3>
		 </article>
		 </a>
	</main>
</div>

<style lang="postcss">
	figure {
		@apply flex relative flex-col;
	}
	figure svg,
	.img-bg {
		@apply w-64 h-64 md:w-80 md:h-80;
	}
	.img-bg {
		@apply absolute z-[-1] rounded-full blur-[50px] transition-all;
		animation: pulse 5s cubic-bezier(0, 0, 0, 0.5) infinite,
			glow 5s linear infinite;
	}
	@keyframes glow {
		0% {
			@apply bg-primary-400/50;
		}
		33% {
			@apply bg-secondary-400/50;
		}
		66% {
			@apply bg-tertiary-400/50;
		}
		100% {
			@apply bg-primary-400/50;
		}
	}
	@keyframes pulse {
		50% {
			transform: scale(1.5);
		}
	}
</style>
