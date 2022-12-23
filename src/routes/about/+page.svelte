<script>
	import Header from '$lib/+page.svelte';
	import Footer from '$lib/footer.svelte';
</script>

<Header />

<div class="about">
	<h1>About Us</h1>

	<p>
		Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis, ex aperiam! Voluptatem
		nesciunt delectus eius excepturi obcaecati ut provident dolore nobis perferendis modi quas est
		sapiente dolores molestiae, illum voluptates asperiores commodi distinctio reprehenderit ratione
		ducimus. Ad nemo voluptatibus incidunt quo, quae dolorem reprehenderit suscipit laboriosam
		fugiat totam consequatur excepturi, corrupti doloremque aliquam. Tenetur repellendus
		reprehenderit distinctio beatae, architecto, alias delectus impedit aperiam ratione vel soluta
		enim ducimus et accusamus quo laudantium sit molestiae! Earum praesentium repudiandae ipsam
		mollitia, aliquid et sapiente dolor obcaecati porro quam vero. Modi sequi deleniti voluptates,
		id iste iusto repellendus. Provident voluptate sunt explicabo deleniti quidem, impedit
		temporibus laudantium doloremque modi qui repellendus esse debitis illum. Necessitatibus, sunt
		rem, quas repellendus possimus beatae cum corporis ipsam repellat atque ipsa? Architecto
		consequuntur repellendus doloremque iure perspiciatis earum explicabo culpa dolor harum. In
		debitis necessitatibus iste libero aspernatur. Fuga molestiae aut ea at in dicta quae
		doloremque.
	</p>
	<img src="/svelte-logo.png" alt="logo" />
</div>
<Footer />

<style>
	.about {
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

	img {
		width: 150px;
		height: 150px;
		margin-top: 50px;
	}

	@media (max-width: 480px) {
		p {
			font-size: 15px;
		}
	}
	@media (max-width: 1024px) {
		p {
			font-size: 30px;
		}
	}
	@media (max-width: 1200px) {
		p {
			font-size: 30px;
		}
	}
	@media (max-width: 1200px) {
		h1 {
			font-size: 50px;
		}
	}
</style>
