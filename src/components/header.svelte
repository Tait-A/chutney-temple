<script>
	import github from '$lib/github.svg';
</script>

<header>
	<div class="corner">
		<a href="https://github.com/Tait-A">
			<img src={github} alt="GitHub" />
		</a>
	</div>
</header>

<style>
	.corner {
		width: 3em;
		height: 3em;
	}

	.corner a {
		display: flex;
		align-items: center;
		justify-content: center;
		width: 100%;
		height: 100%;
	}

	.corner img {
		width: 2em;
		height: 2em;
		object-fit: contain;
	}
</style>
