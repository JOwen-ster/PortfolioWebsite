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
<WaveSection header={'About'} content={'Content'} />

<p id="Skills">Skills</p>
<WaveSection header={'Skills'} content={'Content'} />

<p id="Projects">Projects</p>
<WaveSection header={'Projecs'} content={'Content'} />

<p id="Contact">Contact Me</p>
<WaveSection header={'Contact Me'} content={'Content'} />