<!-- thinking to make a component folder for each container to slim down this page but since first run, let just go -->
<div class="above">
	<header>
        <section class="left-nav">
            <article class="logo">
                <p>Trek</p>
            </article>
            <article class="link">
                <ul>
                    <li>Home</li>
                    <li>About</li>
                    <li>Hotels & Villas</li>
                    <li>Flights</li>
                    <li>Blog</li>
                </ul>
            </article>
        </section>
        <section class="right-nav">
            <p>Sign In</p>
            <button>Sign Up</button>
        </section>
    </header>
	<div class="hero-container">
		<section>
			<h1 class="hero-text">Get Started To Book Your Perfect Escape</h1>
			<p class="hero-paragraph">
				Craft your own odyssey with our curated selection of hotels, vilas, and flights. <br />
				Elevate your trave experience with every click.
			</p>

			<!-- how do i make the tab div thingy? -->
			<article></article>
		</section>
	</div>
</div>
<div class="popular-container">
	<section>
		<h1 class="popular-title"><span>Popular</span> Accommodations Near You</h1>
		<p class="popular-paragraph">Explore a range of popular accommodations near you. Comfort place for a memorable stay!</p>
	</section>
	<section class="popular-destinations">
		<article class="box">
            <img src="../elf/elEgypt.jpeg" alt="el Egypt at dusk" class="pop-img">
			<h2>This Place</h2>
			<p>
                <!-- icon -->
                <span class="pop-location">Location</span>
                <article>
                    <!-- icon -->
                    <span class="pop-rating">5.0</span>
                </article>
			<p>BTC 1,000,000</p>
		</article>
		<article class="box">
            <img src="../elf/elArtica.jpeg" alt="ancient buildings of el Artica" class="pop-img">
			<h2>This Place</h2>
			<p>
                <!-- icon -->
                <span class="pop-location">Location</span>
                <article>
                    <!-- icon -->
                    <span class="pop-rating">5.0</span>
                </article>
			<p>BTC 1,000,000</p>
		</article>
		<article class="box">
            <img src="../elf/elGreenLand.jpeg" alt="el GreenLand at late dawn" class="pop-img">
			<h2>This Place</h2>
			<p>
                <!-- icon -->
                <span class="pop-location">Location</span>
                <article>
                    <!-- icon -->
                    <span class="pop-rating">5.0</span>
                </article>
			<p>BTC 1,000,000</p>
		</article>
	</section>
	<button>See More</button>
</div>
<div class="value-container"></div>
<div class="trending-container"></div>
<div class="review-container"></div>
<div class="blog-container"></div>
<div class="subscribe-container"></div>
<footer></footer>


<style>
    * {
        padding: 0;
        margin: 0;
        min-width: 0;
    }

    .above {
        height: 600px;
        background-image: url(../elf/home.jpeg);
        background-position: center;
        background-size: cover;
    }

    /* placeholder for navbar */
    header {
        width: 85%;
        margin: auto;
        margin-bottom: 5rem;
        height: 1rem;
        padding: 10px 0;
        color: white;
        font-family: Helvetica;
        letter-spacing: 0.1em;
        display: flex;
        justify-content: space-between;
    }

    .left-nav {
        display: flex;
        gap: 3rem;
    }

    .logo {
        font-size: 1.1rem;
    }

    .link > ul {
        list-style: none;
        display: flex;
        gap: 2rem;
        font-size: 0.8rem;
    }

    .right-nav {
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 1rem;
    }
    .right-nav > p {
        font-size: 0.8rem;
    }

    button {
        background: linear-gradient(90deg, skyblue, navy);
        height: 1.5rem;
        width: 5rem;
        border: none;
        border-radius: 10px 0 10px 0;
        color: white;
        letter-spacing: 0.1em;
        box-shadow: white 5px 5px 45px;
    }

    button:hover {
        cursor: pointer;
        transform: scaleX(1.1);
    }

    .hero-container {
        color: white;
        width: 85%;
        margin: auto;
    }

    .hero-text {
        font-family: Arial, Helvetica, sans-serif;
        letter-spacing: 0.3em;
        font-size: clamp(3.5vw, 3.5vw, 5.5vw);
        max-width: 65%;
        margin-bottom: 1rem;
    }

    .hero-paragraph {
        font-family: Arial, Helvetica, sans-serif;
        font-size: clamp(1.1vw, 1.4vw, 2vw);
        max-width: 60%;
    }

    .popular-container {
        height: 450px;
        width: 85%;
        margin: auto;
        display: flex;
        flex-direction: column;
        justify-content: space-around;
        align-items: center;
        font-family: Arial, Helvetica, sans-serif;
    }

    .popular-title {
        font-size: clamp(2.2vw, 2.8vw, 3.5vw);
        text-align: center;
    }

    .popular-title > span {
        color: steelblue;
    }

    .popular-paragraph {
        font-size: clamp(1.8vw, 1.6vw, 2vw);
    }

    .popular-destinations {
        width: 100%;
        display: flex;
        gap: 25px;
    }

    .box {
        outline: 1px solid grey;
        padding: 3px;
        border-radius: 10px 0 0 0;
    }

    .pop-img {
        width: 100%;
        border-radius: 10px 0 0 0;
    }
</style>
