<script>
	import github from '$lib/images/github.svg';
	import paragraph from '$lib/images/paragraph.png';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>

<pre class="title">scaffold-move-app
</pre>
<a class="paragraph grow" href="https://paragraph.xyz/@0xZOZ/set-up-a-move-developer-environment[sui]">
	<img class="paragraph" src={paragraph} alt="Sui Dev Setup Img" />
</a>




</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	.title {
		font-size: 4em;
		font-weight: bold;
	}

	.paragraph {
		width:70%;
		text-align: center;
		border-radius: 5%;
	}

	.grow { 
	transition: all .2s ease-in-out; 
	}

	.grow:hover { 
	transform: scale(1.1); 
	}



	/* a {
		display: flex;
		align-items: center;
		justify-content: center;
		width: 2em;
		height: 2em;
	} */

	/* .corner img {
		width: 2em;
		height: 2em;
		object-fit: contain;
	} */

</style>
