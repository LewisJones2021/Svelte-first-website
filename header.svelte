<script>
	let title = 'Svelte Website';
</script>

<div class="header">
	<div class="logo">
		<a href="https://svelte.dev/" rel="Svelte" target="_">
			<img src="/svelte-logo.png" alt="logo" />
		</a>

		<div class="title">
			<h1>
				{title}
			</h1>
		</div>
	</div>
	<div class="header-links">
		<a href="./index">Homepage </a><strong>|</strong>
		<a href="./about"> &nbsp;About&nbsp; </a>
		<a href="./contact"> <strong>|&nbsp;</strong> Contact</a>
	</div>
</div>

<style>
	.logo,
	.title {
		display: flex;
		align-items: center;
	}
	.header {
		display: flex;
		align-items: center;
		justify-content: space-between;
		letter-spacing: 1px;
	}

	.header-links,
	a {
		margin-right: 5px;
		display: flex;
		align-items: center;
		font-family: sans-serif;
		font-size: 20px;
		text-decoration: none;
		color: rgb(31, 80, 31);
		font-weight: 600;
		letter-spacing: 1px;
	}

	a:hover {
		color: blue;
	}
	.logo img {
		display: inline-block;
		width: 80px;
		height: 80px;
		margin: 20px 10px;
	}

	.header h1 {
		margin-left: 25px;
		font-size: 25px;
		color: rgb(31, 80, 31);
		font-family: sans-serif;
	}
	@media (max-width: 480px) {
		.header {
			flex-direction: column;
		}
	}

	@media (max-width: 480px) {
		.header a {
			font-size: 15px;
			margin-left: 20px;
		}
	}
	@media (max-width: 1200px) {
		.header-links,
		a,
		.title h1 {
			font-size: 40px;
		}
	}
	@media (max-width: 1180px) {
		.header-links a {
			font-size: 25px;
			margin-right: 10px;
		}
	}
	@media (max-width: 1200px) {
		.header-links,
		a,
		.title h1 {
			font-size: 40px;
		}
	}
</style>
