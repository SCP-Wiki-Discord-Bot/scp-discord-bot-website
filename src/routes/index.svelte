<script>
	import Navbar from "../components/Nav.svelte"
	import Main from "../components/Main.svelte"
	import "bulma/css/bulma.min.css"
</script>

<style>
	.title {
		text-align: center;
		font-size: 3em;
		font-family: sans-serif;
		font-weight: 100;
		text-transform: uppercase;
	} 
</style>

<Navbar />
<Main>
	<h1 class="title"> Hello World </h1>
</Main>
