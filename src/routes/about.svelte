<svelte:head>
	<title>About</title>
	{@html metas}
</svelte:head>

<h1>About this site</h1>

<p>This is the 'about' page. There's not much here.</p>

<script>
	let metas = '<meta name="description" content="Two: A test of svelte head with @html">';
</script>