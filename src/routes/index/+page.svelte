<script>
	import Header from '$lib/+page.svelte';
	import Footer from '$lib/footer.svelte';
</script>

<Header />

<div class="index">
	<h1>Welcome to the website for everything Svelte!</h1>

	<p>
		Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ut, esse quisquam asperiores neque
		iste ducimus magnam eveniet, at illo saepe ad fugiat pariatur quod dolorum adipisci excepturi
		possimus deleniti recusandae facere explicabo facilis praesentium, suscipit quo. Recusandae odio
		aspernatur cupiditate consequuntur. Atque cumque libero ipsa repellendus magnam tempore! Quaerat
		optio obcaecati molestias placeat maiores. Ipsa voluptas cupiditate animi neque obcaecati et
		molestias, quod perspiciatis quaerat. Laboriosam maiores perspiciatis esse, recusandae aperiam
		nihil fugiat fuga praesentium eos ex necessitatibus ea ipsam omnis. In magni blanditiis
		exercitationem, nihil eos reiciendis sed praesentium earum, ipsam magnam amet distinctio
		officiis explicabo nisi? Optio, adipisci.
	</p>

	<div class="code-example">
		<p>Here is an example of Svelte!</p>
		<img src="/code-example.png" alt="Code Example" />
	</div>
</div>
<Footer />

<style>
	.index {
		text-align: center;
		display: block;
		margin: 50px auto;
		font-family: sans-serif;
		max-width: 80%;
		min-height: 100vh;
	}

	h1 {
		color: rgb(31, 80, 31);
	}

	p {
		font-size: 20px;
		margin-top: 50px;
	}

	.code-example p {
		color: rgb(31, 80, 31);
		margin-left: 40px;
		font-size: 18px;
		margin-top: 50px;
	}
	.code-example img {
		margin-top: 50px;
	}
	@media (max-width: 500px) {
		h1,
		p {
			font-size: 15px;
			display: flex;
			justify-content: center;
		}
	}

	@media (max-width: 1024px) {
		h1,
		p {
			font-size: 20px;
			margin-left: 80px;
		}
	}
</style>
