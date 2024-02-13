<!-- thinking to make a component folder for each container to slim down this page but since first run, let just go -->
<script>
    import Review from "../lib/components/Review.svelte";
    import Inspirations from "../lib/components/Inspirations.svelte";
</script>

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
		<h2 class="popular-title"><span>Popular</span> Accommodations Near You</h2>
		<p class="popular-paragraph">Explore a range of popular accommodations near you. Comfort place for a memorable stay!</p>
	</section>
	<section class="popular-destinations">
		<article class="box">
            <img src="../elf/elEgypt.jpeg" alt="el Egypt at dusk" class="pop-img">
			<h2>Thoth Trail</h2>
			<div class="pop-details">
                <!-- icon -->
                <span class="pop-location">el Egypt</span>
                <article>
                    <!-- icon -->
                    <span class="pop-rating">4.91</span>
                </article>
            </div>
			<p class="price">BTC 3.96</p>
		</article>
		<article class="box">
            <img src="../elf/elArtica.jpeg" alt="ancient buildings of el Artica" class="pop-img">
			<h2>People's Library</h2>
			<div class="pop-details">
                <!-- icon -->
                <span class="pop-location">el Artica</span>
                <article>
                    <!-- icon -->
                    <span class="pop-rating">4.87</span>
                </article>
            </div>
			<p class="price">BTC 0.0143</p>
		</article>
		<article class="box">
            <img src="../elf/elGreenLand.jpeg" alt="el GreenLand at late dawn" class="pop-img">
			<h2>Split River</h2>
			<div class="pop-details">
                <!-- icon -->
                <span class="pop-location">el GreenLand</span>
                <article>
                    <!-- icon -->
                    <span class="pop-rating">4.96</span>
                </article>
            </div>
			<p class="price">BTC 0.06118</p>
		</article>
	</section>
	<button class="see-more">See More</button>
</div>
<div class="value-container">
    <!-- image section -->
    <section>
        <img src="../elf/sight-seeing.png" alt="family using Trek sight seeing, enjoying the view" width="400px">
    </section>

    <!-- text section -->
    <section class="right-value">
        <article>
            <h2>Why <span>Choose</span> Us</h2>
            <p>We offer unbeatable prices and personalized experiences.</p>
        </article>

        <article class="highlight">
            <!-- each span is an icon -->
            <span></span>
            <div>
                <h3>Wide Range Options</h3>
                <p>Offers a diverse selection of accommodations.</p>
            </div>
        </article>
        <article>
            <span></span>
            <div>
                <h3>Best Prices and Special Offers</h3>
                <p>Guarantee the best prices for every booking.</p>
            </div>
        </article>
        <article>
            <span></span>
            <div>
                <h3>Flexible Cancellation</h3>
                <p>User has flexibility to modify at request.</p>
            </div>
        </article>
    </section>
</div>
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
<div class="review-container">
    <Review />
</div>
<div class="blog-container">
    <Inspirations />
</div>
<div class="subscribe-container"></div>
<footer></footer>


<style>
    /* beginning of every project, i forget how much i use flex. remember to add css variable or one class name to share */
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

    @media screen and (max-width: 755px) {
        .link > ul > li {
            display: none;
        }
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

    .popular-container, .trending-container {
        height: 500px;
        width: 85%;
        margin: auto;
        display: flex;
        flex-direction: column;
        justify-content: space-around;
        align-items: center;
        font-family: Arial, Helvetica, sans-serif;
    }

    .popular-title {
        font-size: clamp(2.5vw, 3.2vw, 3.7vw);
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
        padding: 5px;
        border-radius: 10px 0 0 0;
        display: flex;
        flex-direction: column;
        gap: 7px;
    }

    .pop-details {
        display: flex;
        justify-content: space-between;
        font-size: 0.8rem;
    }

    .pop-img {
        width: 100%;
        border-radius: 10px 0 0 0;
    }

    .see-more {
        height: 1.8rem;
        width: 8rem;
    }

    .price {
        color: lightseagreen;
        font-weight: bold;
        margin-top: 5px;
    }

    .value-container {
        height: 500px;
        width: 75%;
        display: flex;
        justify-content: space-around;
        align-items: center;
        margin: auto;
    }
     
    /* for screens smaller than 750px */
    @media (max-width: 825px) {
        .value-container {
            flex-direction: column;
            height: 700px;
            justify-content: center;
        }
    }

    .right-value {
        display: flex;
        flex-direction: column;
        gap: 20px;
    }

    .right-value > article > h2 {
        font-size: 1.8rem;
        font-family: Arial, Helvetica, sans-serif;
        margin-bottom: 0.7rem;
    }

    .right-value > article > h2 > span {
        color: seagreen;
    }

    .trending-container {
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
