<script>
	let { content } = $props();
</script>


<style>
	.hero-container {
		display: flex;
		flex-direction: row;
		justify-content: space-around;
		align-items: center;
		background: #1a1a1a;
		margin: 2.5vh 10vw;
		border-radius: 50px;
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


<div class="hero-container">
	<p class="hero-element">Hello! My name is</p>
	<p class="hero-header">{content}</p>
	<p class="hero-element">I'm a fullstack software engineer.</p>

	<img src="/favicon.png" alt="Owen Sterling"/>
</div>