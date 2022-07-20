<script>
	let count = 0;
</script>

<body>
	<div>
		<p>Counter on click</p>
		<input type=number bind:value={count}>
		<button on:click="{() => count += 1}">count</button>
	</div>
</body>

<style>
	div {
		margin: 50px;
	}
</style>