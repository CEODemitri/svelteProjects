<script>
</script>

<div class="page">
	<header>
		<article>
			<h1>Welcome to Electric Electrician</h1>
			<p>
				Your trusted partner for all electrical needs. We provide top-notch services to ensure your
				home and business are powered safely and efficiently.
			</p>
			<p>Explore our services and get in touch with us for reliable electrical solutions.</p>
		</article>

		<section class="book-consult">
			<h2>Book A Consultation today</h2>

			<form method="post">
				<div>
					<label for="name">Name:</label>
					<input type="text" id="name" name="name" required />

					<label for="email">Email Address:</label>
					<input type="email" id="email" name="email" required />

					<div>
						<label for="date">Choose Date:</label>
						<input type="date" id="date" name="date" required />

						<label for="time">Choose Time:</label>
						<input type="time" id="time" name="time" required />
					</div>

					<button type="submit">Book Now</button>
				</div>
			</form>
		</section>
	</header>
</div>

<style>
	.book-consult {
		margin-top: 2rem;
		padding: 1rem;
		border: 1px solid #ccc;
		border-radius: 8px;
		display: flex;
		flex-direction: column;
	}

	.book-consult form {
		display: flex;
		flex-direction: column;
	}

	button {
		margin-top: 1rem;
		padding: 0.5rem 1rem;
		background-color: #007bff;
		color: white;
		border: none;
		border-radius: 4px;
		cursor: pointer;
		display: block;
	}
</style>
