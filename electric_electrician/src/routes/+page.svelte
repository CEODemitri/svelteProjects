<script>
</script>

<div class="page">
	<header>
		<article>
			<h1>The Finest <span>Kinetic</span> Output Seen this Lifetime</h1>
			<p>
				Your trusted orgon partner for all electrical needs. We provide top-notch services to ensure
				your home and business are powered safely and efficiently.
			</p>
			<p>Explore our services and get in touch with us for reliable electrical solutions.</p>
		</article>

		<section class="book-consult">
			<h2>Book A Consultation today</h2>

			<form method="post">
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

				<div>
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
					<legend>City</legend>
					<input type="text" name="location" required />
				</fieldset>

				<button type="submit">Book Now</button>
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
