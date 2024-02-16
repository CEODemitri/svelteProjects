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

<style>
    .popular-container {
        height: 500px;
        width: 85%;
        margin: auto;
        margin-top: 10px;
        display: flex;
        flex-direction: column;
        gap: 25px;
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
        gap: 3px;
    }

    .pop-details {
        display: flex;
        justify-content: space-between;
        font-size: 0.8rem;
    }

    .pop-img {
        width: 85%;
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
</style>