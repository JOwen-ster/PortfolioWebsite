<script>

</script>


<style>
	nav {
		display: flex;
		position: sticky;
		top: 2.5vh;
		z-index: 100;
		flex-direction: row;
		justify-content: center;
		background-color: rgba(25, 25, 25, 0.5); /* Slight transparency */
		backdrop-filter: blur(10px);
		padding: 10px;
		gap: 20px;
		margin: 2.5vh 25vw 2.5vh 25vw;
		border-radius: 50px;
		box-shadow: 0 0 10px rgba(255, 0, 255, 0.3);
	}

	nav a {
		font-weight: bold;
		font-size: 1rem;
		position: relative;
		text-decoration: none;
		text-shadow: 0 0 5px black;
		color: #333;
		transition: color 0.3s ease-in-out;
	}

	nav a:hover {
		color: #aa00ff;
	}

	nav a::after {
		content: '';
		position: absolute;
		left: 0;
		bottom: 0;
		width: 100%;
		height: 2px;
		background-color: #aa00ff;
		transform: scaleX(0);
		transform-origin: right;
		transition: transform 0.3s ease-in-out;
	}

	nav a:hover::after {
		transform: scaleX(1);
		transform-origin: left;
	}
</style>

<nav>
	<a href="./">Home</a>
	<a href="#About">About</a>
	<a href="#Skills">Skills</a>
	<a href="#Projects">Projects</a>
	<a href="#Contact">Contact</a>
</nav>
