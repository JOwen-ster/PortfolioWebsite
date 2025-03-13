<script>
	let { content } = $props();
</script>


<style>
	.hero-container {
		display: flex;
		flex-direction: row;
		justify-content: space-around;
		align-items: center;
		background: #121212;
		margin: 2.5vh 10vw;
		border-radius: 50px;
	}

	.hero-text-container {
		display: flex;
		flex-direction: column;
		line-height: 1;
		color: white;
	}

	.hero-text {
		margin: 0;
		padding: 0;
	}

	.hero-header {
		background-image: linear-gradient(#007bff, purple);
		background-clip: text;
		-webkit-text-fill-color: transparent;
		font-size: 40px;
		font-weight: bold;
		margin: 0;
		padding: 10px 0
	}
</style>


<div class="hero-container">
	<div class="hero-text-container">
		<p class="hero-text">Hello! My name is</p>
		<p class="hero-header">{content}</p>
		<p class="hero-text">I'm a fullstack software engineer.</p>
	</div>

	<img src="/favicon.png" alt="Name Header"/>
</div>