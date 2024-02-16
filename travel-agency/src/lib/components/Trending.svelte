<div class="trending-container">
	<section>
		<h2 class="popular-title"><span>Trending</span> Destinations in ElfLand</h2>
		<p class="popular-paragraph">Explore a range of popular accommodations near you. Comfort place for a memorable stay!</p>
	</section>
	<section class="trending-destinations">
		<article>
            <img src="../elf/elHogwartsElem.jpeg" alt="el Hogwarts Elementary">
            <button>el Hogwarts Elem</button>
		</article>
		<article>
            <img src="../elf/elTokyo.jpeg" alt="el Tokyo city walls">
            <button>el Tokyo</button>
		</article>
		<article>
            <img src="../elf/elEgypt3.jpeg" alt="el Egypt at early dawn">
            <button>el Egypt early morning</button>
		</article>
        <article>
            <img src="../elf/elLion2.jpeg" alt="el Lion pathway">
            <button>el Lion</button>
		</article>
	</section>
</div>

<style>
    .trending-container {
        height: 500px;
        width: 85%;
        margin: auto;
        display: flex;
        flex-direction: column;
        justify-content: space-around;
        align-items: center;
        font-family: Arial, Helvetica, sans-serif;
        background: rgb(2,0,36);
        background: radial-gradient(ellipse, rgb(23, 21, 54) 0%, rgba(13, 13, 42, 0.6) 35%, rgba(0,212,255,0.4) 100%);
        width: 100%;
        color: whitesmoke;
    }

    .trending-destinations {
        max-width: 75%;
        display: flex;
        justify-content: space-between;
        gap: 15px;
    }

    .trending-destinations > article {
        position: relative;
    }

    .trending-destinations > article > img {
        height: 250px;
        width: 150px;
    }

    .trending-destinations > article > button {
        position: absolute;
        bottom: 20px;
        left: 15px;
        height: 1.8rem;
        width: 120px;
    }
</style>