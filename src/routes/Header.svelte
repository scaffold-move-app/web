<script>
	import { page } from '$app/stores';
	import logo from '$lib/images/scaffold-move-logo.svg';
	import github from '$lib/images/github.svg';
</script>

<header>

	<div class="corner-left">
		<a href="https://github.com/scaffold-move-app">
			<img src={logo} alt="scaffold-move logo" />
		</a>
	</div>
	
	<div class="corner">
		<a href="https://github.com/scaffold-move-app">
			<img src={github} alt="GitHub" />
		</a>
	</div>
</header>

<style>
	header {
		display: flex;
		justify-content: space-between;
		margin: 1%;
	}

	.corner {
		width: 5em;
		height: 5em;
	}

	.corner a {
		display: flex;
		width: 100%;
		height: 100%;
		align-items: right;
		justify-content: right;
	}

	.corner img {
		width: 3em;
		height: 3em;
		object-fit: contain;
	}

	.corner-left {
		width: 5em;
		height: 5em;
	}

	.corner-left a {
		display: flex;
		width: 100%;
		height: 100%;
		align-items: left;
		justify-content: left;
	}

	.corner-left img {
		width: 3em;
		height: 3em;
		object-fit: contain;
	}



	a:hover {
		transform: scale(1.1);
	}
</style>
