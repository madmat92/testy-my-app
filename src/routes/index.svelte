<script>
	import successkid from 'images/successkid.jpg';
</script>

<style>
	h1, figure, p {
		text-align: center;
		margin: 0 auto;
	}

	h1 {
		font-size: 2.8em;
		text-transform: uppercase;
		font-weight: 700;
		margin: 0 0 0.5em 0;
	}

	figure {
		margin: 0 0 1em 0;
	}

	img {
		width: 100%;
		max-width: 400px;
		margin: 0 0 1em 0;
	}

	p {
		margin: 1em auto;
	}

	@media (min-width: 480px) {
		h1 {
			font-size: 4em;
		}
	}
	.testBtn {
		bottom: 1rem;
		position: absolute;
	}
</style>

<svelte:head>
	<title>Sapper project template</title>
</svelte:head>

<h1>Great success!</h1>
<p>host & deploy by Netlify</p>
<figure>
	<img alt="Success Kid" src="{successkid}">
	<figcaption>Have fun with Sapper!</figcaption>
</figure>

<p><strong>Try editing this file (src/routes/index.svelte) to test live reloading.</strong></p>

<button class="testBtn">Test button</button>

<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur perspiciatis, nihil saepe recusandae corrupti repellat quia ad deserunt beatae inventore aut sequi porro iusto esse, libero id, voluptate fugiat necessitatibus?</p>
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur perspiciatis, nihil saepe recusandae corrupti repellat quia ad deserunt beatae inventore aut sequi porro iusto esse, libero id, voluptate fugiat necessitatibus?</p>
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur perspiciatis, nihil saepe recusandae corrupti repellat quia ad deserunt beatae inventore aut sequi porro iusto esse, libero id, voluptate fugiat necessitatibus?</p>