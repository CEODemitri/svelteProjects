<div class="above">
	<header>
        <section class="left-nav">
            <article>
                <p class="logo">Trek</p>
            </article>
            <span class="material-symbols-outlined menu">
                menu
            </span>
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

<style>
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
        padding: 0;
        margin: 0;
    }

    .menu {
        display: block;
    }

    @media (min-width: 756px) {
        .menu {
            display: none;
        }
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
        font-size: clamp(1rem, 2.3rem, 5.5vw);
        max-width: 65%;
        margin-bottom: 1rem;
    }

    .hero-paragraph {
        font-family: Arial, Helvetica, sans-serif;
        font-size: clamp(0.5rem, 0.8rem, 1rem);
        max-width: 70%;
    }
</style>