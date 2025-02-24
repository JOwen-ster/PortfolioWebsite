<script>
	let { content } = $props();
</script>

<div class="hero-container">
	<div>
		<p class="hero-element">Hello! My name is</p>

		<p class="hero-header">{content}</p>

		<p class="hero-element">I'm a fullstack software engineer.</p>
	</div>

	<div>
		<img src="/favicon.png" alt="Owen Sterling" />
	</div>
</div>

<style>
	.hero-container {
		display: flex;
		flex-direction: row;
		justify-content: space-around;
		align-items: center;
		background: black;
	}

	.hero-element {
		margin: 0;
		color: white;
	}

	.hero-header {
		margin: 0;
		background-image: linear-gradient(#007bff, purple);
		background-clip: text;
		-webkit-text-fill-color: transparent;
	}
</style>
