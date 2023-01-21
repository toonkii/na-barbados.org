<script lang="ts">
	import '@picocss/pico';
	import '../app.css';
	import MainMenu from '../components/MainMenu.svelte';
	import Footer from '../components/Footer.svelte';
</script>

<main class="container">
		
	<MainMenu />
	
	<slot />

	<Footer />
	
<!-- 
	<div class="grid">
		<div>1</div>
		<div>2</div>
		<div>3</div>
		<div>4</div>
	</div>

	<a href="#top" class="warning" role="button">Link</a>

	<details>
		<summary>Accordion 1</summary>
		<p>
			Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus blanditiis consequuntur
			possimus fuga quos dolorem saepe aliquam! Nisi sunt nam vitae assumenda aut, modi porro,
			incidunt quisquam laudantium, adipisci ipsa!
		</p>
	</details>

	<article>
		<header>
			<h1>I'm a card!</h1>
		</header>
		<p>
			Lorem, ipsum dolor sit amet consectetur adipisicing elit. Assumenda modi voluptatibus amet
			praesentium omnis necessitatibus unde? Neque repellendus totam minima ducimus quibusdam
			delectus nam laudantium fuga fugiat inventore nostrum incidunt laboriosam, et tempora id illo
			dolor, libero possimus reiciendis accusantium sequi dolorum. Molestiae laboriosam odio eum!
			Soluta commodi dolorum sequi dolore nulla iure nihil neque est facere quidem. Modi harum fugit
			excepturi aliquid qui vero asperiores vitae ratione voluptatibus quasi nostrum distinctio,
			voluptatum voluptate necessitatibus culpa odio sapiente officia consequatur laudantium illum
			nesciunt. Esse voluptatem iusto soluta excepturi unde molestias quasi dolorum assumenda
			consectetur aspernatur? Ducimus quis cum amet consequatur officiis. Modi magnam vitae totam
			nesciunt repudiandae, aut quis nihil mollitia iste voluptatem! Unde, deserunt mollitia?
			Laborum sint ullam facere autem quae nisi fuga deleniti.
		</p>
		<footer><h2>Footer</h2></footer>
	</article> -->

</main>
