<script>
	import Header from '$lib/+page.svelte';
	import Footer from '$lib/footer.svelte';
</script>

<Header />
<main>
	<div class="container">
		<div class="head">
			<div class="contact-form">
				<h1>Contact form</h1>
			</div>
			<form>
				<div class="input-label">
					<label for="fName" id="fNamne">First Name</label>
					<input type="text" placeholder="Last Name" />

					<label for="lName" id="lName">Last Name</label>
					<input type="text" placeholder="Last Name" />

					<label for="email" id="email">Email Address</label>
					<input type="email" placeholder="Email Address" />
				</div>
				<div class="text-area">
					<p>Please enter your message below</p>
					<textarea id="text-area" cols="25" rows="5" />
				</div>
				<button type="submit" id="contactBtn">Submit</button>
			</form>
		</div>
	</div>
</main>
<Footer />

<style>
	main {
		min-height: 100vh;
	}
	.container {
		width: 500px;
		background-color: red;
		display: block;
		margin: auto;
		border-radius: 10px;
	}
	.head {
		background: rgb(2, 0, 36);
		background: linear-gradient(
			90deg,
			rgba(2, 0, 36, 1) 0%,
			rgba(31, 121, 9, 1) 35%,
			rgba(0, 212, 255, 1) 100%
		);
		border-radius: 5px;
		width: 100%;
		height: 60px;
	}
	h1 {
		font-size: 15px;
		margin-top: 20px;
		padding: 20px 20px 0 20px;
		font-family: sans-serif;
		font-weight: 400;
	}

	form {
		display: flex;
		justify-content: center;
		flex-direction: column;
		padding: 10px 20px;
		margin-top: 30px;
	}

	label {
		font-family: sans-serif;
		font-size: 12px;
		padding: 5px;

		margin-top: 20px;
		font-weight: 600;
	}

	input {
		padding: 10px 5px;
		background-color: rgba(4, 15, 42, 0.653);
		border: 2px solid grey;
		border-radius: 5px;
		width: 300px;
		display: block;
		margin: 0 auto;
	}

	.input-label {
		display: flex;
		flex-direction: column;
		margin: 0px auto;
	}
	.text-area {
		display: flex;
		flex-direction: column;
	}

	textarea {
		resize: none;
		padding: 10px 10px;
		border-radius: 10px;
		border: 2px solid grey;
		font-size: 18px;
		background-color: rgba(4, 15, 42, 0.364);
	}
	.text-area p {
		margin-top: 50px;
		margin-bottom: 2px;
		font-size: 12px;
		font-family: sans-serif;
		font-weight: 600;
	}
	button {
		font-size: 15px;
		padding: 10px 5px;
		margin-top: 80px;
		cursor: pointer;
		font-family: sans-serif;
		font-weight: 600;
		width: 250px;
		display: block;
		margin: 50px auto;
		border-radius: 10px;
		background-color: rgba(4, 15, 42, 0.653);
		border: 2px solid gray;
	}
	button:hover {
		background-color: darkgray;
	}

	@media (max-width: 1180px) {
		.container label,
		input,
		h1 {
			font-size: 20px;
			padding: 20px;
			width: 600px;
		}
	}
	@media (max-width: 1180px) {
		.text-area p {
			font-size: 20px;
		}
	}
	@media (max-width: 1180px) {
		textarea {
			width: 620px;
		}
	}
	@media (max-width: 1180px) {
		button {
			font-size: 20px;
			display: block;
			margin-right: 50px;
		}
	}
</style>
