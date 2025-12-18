<script>
	import Logo from '../components/icons/Logo.svelte';
	import Navbar from '../components/Navbar.svelte';

	let links = {
		Home: '/',
		About: '/About'
	};

	console.log({ links });
</script>

<div>
	<!-- nav -->
	<Navbar />

	<!-- Hero Section -->
	<header class="hero">
		<div class="hero-content">
			<h1>Fast & Reliable Delivery Service</h1>
			<p>Get your packages delivered quickly and safely to your doorstep.</p>
			<a href="#book" class="cta-btn">Book a Delivery</a>
		</div>
	</header>

	<!-- Book a Delivery Section -->
	<section id="book" class="book-section">
		<div class="section-content">
			<h2>Book Your Delivery Now</h2>
			<p>Choose a delivery option and we'll take care of the rest.</p>
			<form action="#">
				<input type="text" placeholder="Your Name" required />
				<input type="text" placeholder="Package Details" required />
				<input type="text" placeholder="Destination" required />
				<button type="submit">Book Now</button>
			</form>
		</div>
	</section>

	<!-- Value Section -->
	<section class="value-section">
		<div class="section-content">
			<h2>Why Choose Us?</h2>
			<div class="value-cards">
				<div class="card">
					<h3>Fast Delivery</h3>
					<p>We guarantee timely delivery for all your packages.</p>
				</div>
				<div class="card">
					<h3>Affordable Rates</h3>
					<p>Enjoy competitive pricing without compromising on service.</p>
				</div>
				<div class="card">
					<h3>Safe & Secure</h3>
					<p>We prioritize the safety and security of your items.</p>
				</div>
			</div>
		</div>
	</section>

	<!-- About Us Section -->
	<section class="about-us">
		<div class="section-content">
			<h2>About Us</h2>
			<p>
				We are a leading delivery service provider, offering fast, affordable, and secure solutions
				for all your delivery needs. Our team is committed to ensuring your packages reach their
				destination safely and on time.
			</p>
		</div>
	</section>

	<!-- Footer Section -->
	<footer class="footer">
		<p>&copy; 2025 Delivery Service | All rights reserved.</p>
	</footer>
</div>

<style>
	* {
		margin: 0;
		padding: 0;
		box-sizing: border-box;
		font-family: 'Arial', sans-serif;
	}

	body {
		background-color: #f7f7f7;
		color: #333;
	}

	h1,
	h2,
	h3,
	p {
		margin-bottom: 1rem;
	}

	/* Hero Section */
	.hero {
		background-color: #2d333b;
		color: white;
		text-align: center;
		padding: 6rem 2rem; /* Slightly increased padding for a larger section */
		display: flex;
		flex-direction: column;
		justify-content: center; /* Center the content vertically */
		align-items: center;
		height: 80vh; /* Adjusted height to be a bit smaller */
	}

	.hero h1 {
		font-size: 3.5rem; /* Larger font for the heading */
		margin-bottom: 1.5rem;
	}

	.hero p {
		font-size: 1.3rem; /* Slightly larger font size */
		margin-bottom: 2rem;
		max-width: 800px; /* Keeping max-width for readability */
	}

	.cta-btn {
		padding: 12px 24px; /* Slightly bigger button */
		background-color: #2e9fff;
		color: white;
		text-decoration: none;
		border-radius: 5px;
		font-weight: bold;
		font-size: 1.1rem; /* Slightly bigger text */
	}

	.cta-btn:hover {
		background-color: #1f76c1;
	}

	/* Responsive styles for smaller screens */
	@media (max-width: 768px) {
		.hero {
			padding: 4rem 2rem; /* Less padding for smaller screens */
			height: auto; /* Allow height to adjust based on content */
		}

		.hero h1 {
			font-size: 2.5rem; /* Smaller font size for smaller screens */
		}

		.hero p {
			font-size: 1.1rem; /* Adjust paragraph size */
			max-width: 90%; /* Allow more width for text on smaller screens */
		}

		.cta-btn {
			padding: 10px 20px; /* Slightly smaller button for small screens */
			font-size: 1rem; /* Adjust button text size */
		}
	}

	/* Additional media query for extra small devices (e.g., phones) */
	@media (max-width: 480px) {
		.hero h1 {
			font-size: 2rem; /* Even smaller heading size */
		}

		.hero p {
			font-size: 1rem; /* Further adjust paragraph size */
		}

		.cta-btn {
			padding: 8px 16px; /* Make the button even smaller */
			font-size: 0.9rem; /* Reduce button text size */
		}
	}

	/* Book a Delivery Section */
	.book-section {
		background-color: white;
		padding: 3rem 2rem;
		text-align: center;
	}

	.book-section h2 {
		font-size: 2rem;
	}

	.book-section form {
		display: flex;
		flex-direction: column;
		align-items: center;
		gap: 1rem;
	}

	.book-section input {
		padding: 10px;
		width: 300px;
		border: 1px solid #ccc;
		border-radius: 5px;
	}

	.book-section button {
		padding: 10px 20px;
		background-color: #2e9fff;
		color: white;
		border: none;
		border-radius: 5px;
		font-weight: bold;
		cursor: pointer;
	}

	.book-section button:hover {
		background-color: #1f76c1;
	}

	/* Value Section */
	.value-section {
		background-color: #f7f7f7;
		padding: 3rem 2rem;
		text-align: center;
	}

	.value-section h2 {
		font-size: 2rem;
		margin-bottom: 2rem;
	}

	.value-cards {
		display: flex;
		justify-content: center;
		gap: 2rem;
	}

	.card {
		background-color: white;
		padding: 2rem;
		width: 250px;
		border: 1px solid #ddd;
		border-radius: 5px;
		box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
	}

	.card h3 {
		font-size: 1.5rem;
		margin-bottom: 1rem;
	}

	.card p {
		font-size: 1rem;
	}

	/* About Us Section */
	.about-us {
		background-color: white;
		padding: 3rem 2rem;
		text-align: center;
	}

	.about-us p {
		font-size: 1.1rem;
		max-width: 800px;
		margin: 0 auto;
	}

	/* Footer Section */
	.footer {
		background-color: #2d333b;
		color: white;
		text-align: center;
		padding: 1rem;
		margin-top: 2rem;
	}

	.footer p {
		font-size: 1rem;
	}
</style>
