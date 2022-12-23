<footer>
	<div class="copy-sign">
		<p>Website made by Lewis Jones&copy</p>
	</div>
</footer>

<style>
	footer {
		background-color: rgb(31, 80, 31);

		height: 100px;
		position: absolute;
		bottom: -200px;
		width: 100%;
	}
	footer,
	p {
		font-family: sans-serif;
		font-weight: 600;
		font-size: 12px;
		text-align: right;

		display: flex;
		align-items: flex-end;
		justify-content: end;
	}

	p {
		margin-right: 25px;
	}
	@media (max-width: 480px) {
		footer p {
			font-size: 15px;
		}
	}
	@media (max-width: 480px) {
		footer {
			width: 500px;
		}
	}
	@media (max-width: 1024px) {
		p {
			font-size: px;
		}
	}
	@media (max-width: 1200px) {
		p {
			font-size: 30px;
		}
	}
	@media (max-width: 1200px) {
		footer {
			width: 900px;
		}
	}
</style>
