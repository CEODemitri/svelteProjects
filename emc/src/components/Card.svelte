<div class="col-span-3">
	<img src="../../landing.png" alt="" />
</div>

<style>
	.col-span-3 {
		grid-column: span 1;
		grid-row: span 1;
		margin: auto;
		border: 1px solid #ccc;
		padding: 1em;
		box-sizing: border-box;
		background-color: #fff;
		border-radius: 5px;
		overflow: hidden;
	}

	@media (min-width: 768px) {
		.col-span-3 {
			grid-column: span 3;
		}
	}

	img {
		width: 100%; /* Make image responsive */
		height: auto; /* Maintain aspect ratio */
		max-height: 300px; /* Set a maximum height for images */
		object-fit: cover;
	}
</style>
