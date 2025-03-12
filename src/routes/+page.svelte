<script>
	import './global.css';
	import Navbar from '$lib/Components/Navbar.svelte';
	import Hero from '$lib/Components/Hero.svelte';
	import WaveSection from '$lib/Components/WaveSection.svelte';
</script>

<style>
	p {
		padding-top: 80px; /* Adjust based on navbar height */
	}
</style>

<Navbar />
<Hero content={'Owen Sterling'} />
<p id="About">About</p>

<p id="Skills">Skills</p>

<p id="Projects">Projects</p>

<p id="Contact">Contact Me</p>
<WaveSection header={'Contact Me'} content={'Content'} />