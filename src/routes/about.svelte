<script>
	import Nav from "../components/Nav.svelte";
	import Footer from "../components/Footer.svelte";
</script>

<svelte:head>
	<title>About Page</title>
</svelte:head>

<Nav page="/about/"/>

<main>
    <h1>This is the About Page</h1>
    <p> JungleJS is Easy to use!</p>
</main>
<Footer/>
<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #859A00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>