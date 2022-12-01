<script>
	import github from '$lib/images/github.svg';
	import paragraph from '$lib/images/paragraph.png';
</script>

<svelte:head>
	<title>scaffold-move</title>
	<meta name="description" content="The way to get started building Move apps for all varieties of Move" />
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

	@media (max-width: 800px) {
		.title {
		font-size: 3em;
		}
	}

	@media (max-width: 600px) {
		.title {
		font-size: 2em;
		}

		.paragraph {
		width:80%;
		}
	}

	@media (max-width: 400px) {
		.title {
		font-size: 1.5em;
		}

		.paragraph {
		width:85%;
		}
	}


</style>
