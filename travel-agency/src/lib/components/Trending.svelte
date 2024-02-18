<div class="trending-container">
	<section>
		<h2 class="trending-title"><span>Trending</span> Destinations in ElfLand</h2>
		<p class="trending-paragraph">Explore a range of popular accommodations near you. Comfort place for a memorable stay!</p>
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
        height: max-content;
        width: 85%;
        padding: 0 20px;
        margin: auto;
        display: flex;
        flex-direction: column;
        justify-content: space-around;
        align-items: center;
        font-family: Arial, Helvetica, sans-serif;
        background: linear-gradient(180deg, skyblue, silver);
        width: 100%;
        color: whitesmoke;
    }

    .trending-title > span {
        color: steelblue;
    }

    .trending-destinations {
        max-width: max-content;
        display: flex;
        flex-wrap: wrap;
        justify-content: space-around;
        gap: 10px;
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

    button {
        background-color: steelblue;
        border: none;
        border-radius: 10px 0 10px 0;
        color: antiquewhite;
    }
</style>