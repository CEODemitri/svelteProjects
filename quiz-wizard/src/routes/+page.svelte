<div class="container">
	<section class="img">
		<img src="home.png" alt="" />
	</section>

	<section class="text">
		<article>
			<h1>Quiz Wizard</h1>
			<p>
				Test your luck and wits. Work your way up the ranks and prove the smartest in this realm.
			</p>
		</article>

		<article class="btns">
			<button class="sea">
				<a href="/Categories">See Categories</a>
			</button>
			<button class="stats">Stats</button>
		</article>
	</section>
</div>

<style>
	.container {
		background-color: #0c1019;
		color: white;
		margin: auto;
		overflow: hidden;
		display: flex;
		flex-direction: column;
	}

	.img {
		height: 50%;
	}

	img {
		height: 414px;
	}

	.text {
		height: 50vh;
		display: flex;
		flex-direction: column;
	}

	h1 {
		padding: 0;
		margin: 0;
		margin-bottom: 1.3rem;
		font-size: 2.6rem;
		text-align: center;
		font-family: Helvetica, sans-serif;
	}

	p {
		font-size: 1.3rem;
		max-width: 80%;
		margin: auto;
	}

	.btns {
		display: flex;
		flex-direction: column;
		margin-top: 7rem;
		justify-content: center;
		align-items: center;
		gap: 1rem;
	}

	.sea {
		background-color: #531cc8;
		border: none;
		width: 80%;
		height: 2.6rem;
		font-size: 1.5rem;
		color: #fefdfd;
		border-radius: 10px 0;
	}

	a {
		color: #fefdfd;
	}

	a:hover,
	a:visited {
		color: #faabab;
	}

	.stats {
		background-color: #493e60;
		border: none;
		width: 30%;
		height: 2.6rem;
		font-size: 1.5rem;
		color: #fefdfd;
		border-radius: 10px 0;
	}
</style>
