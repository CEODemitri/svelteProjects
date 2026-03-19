<script>
</script>

<div class="page">
	<header>
		<article>
			<h1>The Finest <span class="kinetic">Kinetic</span> Output Seen this Lifetime</h1>
			<p>
				Your trusted orgon partner for all electrical needs. We provide top-notch services to ensure
				your home and business are powered safely and efficiently. Explore our services and get in
				touch with us for reliable electrical solutions.
			</p>
		</article>

		<section class="book-consult">
			<h2>Book A Consultation today</h2>

			<form method="post" class="main-form">
				<div class="user-type">
					<fieldset>
						<legend>Service Type</legend>
						<label>
							<input type="radio" name="service" value="residential" required />
							Residential
						</label>
						<label>
							<input type="radio" name="service" value="commercial" required />
							Commercial
						</label>
						<label>
							<input type="radio" name="service" value="industrial" required />
							Industrial
						</label>
					</fieldset>
					<fieldset>
						<legend>Service Required</legend>
						<label>
							<input type="checkbox" name="service_required" value="installation" />
							Installation
						</label>
						<label>
							<input type="checkbox" name="service_required" value="repair" />
							Repair
						</label>
						<label>
							<input type="checkbox" name="service_required" value="maintenance" />
							Maintenance
						</label>
					</fieldset>
				</div>

				<div class="user-info">
					<fieldset>
						<legend>Personal Information</legend>
						<label for="name">Name:</label>
						<input type="text" id="name" name="name" required />
					</fieldset>
					<fieldset>
						<legend>Contact Information</legend>
						<label for="email">Email Address:</label>
						<input type="email" id="email" name="email" required />
					</fieldset>
				</div>

				<div class="user-date">
					<fieldset>
						<label for="date">Choose Date:</label>
						<input type="date" id="date" name="date" required />
					</fieldset>
					<fieldset>
						<label for="time">Choose Time:</label>
						<input type="time" id="time" name="time" required />
					</fieldset>
				</div>

				<fieldset>
					<legend>Address</legend>
					<input type="text" name="location" required />
				</fieldset>

				<button type="submit">Book Now</button>
			</form>
		</section>
	</header>
</div>

<style>
	h1 {
		font-size: 2.8rem;
		margin-bottom: 1rem;
		width: 25ch;
	}

	.kinetic {
		color: #aaae67;
		font-weight: bold;
		font-style: italic;
	}

	article p {
		font-size: 0.95rem;
		line-height: 1.5;
		max-width: 500px;
		text-align: justify;
	}

	/* --------------------------- */
	/* form */
	.book-consult {
		margin-top: 2rem;
		padding: 1rem;
		border: 1px solid #ccc;
		border-radius: 8px;
		display: flex;
		flex-direction: column;
		width: 60vw;
	}

	.book-consult form {
		display: flex;
		flex-direction: column;
	}

	.main-form {
		display: flex;
		flex-direction: column;
		gap: 1rem;
	}

	fieldset {
		border: 1px solid #ccc;
		border-radius: 8px;
		padding: 1rem;
		margin-bottom: 1rem;
		width: 50%;
	}

	input[type='text'],
	input[type='email'] {
		width: 90%;
		padding: 0.5rem;
		border: 1px solid #ccc;
		border-radius: 4px;
	}

	.user-type,
	.user-info,
	.user-date {
		display: flex;
		gap: 2rem;
	}

	form button {
		margin-top: 1rem;
		padding: 0.5rem 1rem;
		background-color: #d4dc3ba7;
		color: rgb(0, 0, 0);
		border: none;
		border-radius: 4px;
		cursor: pointer;
		display: block;
		text-transform: uppercase;
		font-weight: bold;
		transition: background-color 0.3s ease;
		letter-spacing: 1.5em;
	}

	form button:hover {
		background-color: #aaae67;
		color: #fff;
	}
</style>
