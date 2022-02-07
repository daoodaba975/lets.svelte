<script>
	export let name;
</script>

<main>
	<h1>Hello my name is {name}!</h1>
	<p>I'm currently learning Svelte, visit my <a href="https://daooda.dev">website</a> to see what i'm doing.</p>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 250px;
		margin: 0 auto;
	}
	a {
		text-decoration: underline;
	}
	h1 {
		color: #ff3e00;
		font-size: 4em;
		font-weight: 100;
	}
	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>