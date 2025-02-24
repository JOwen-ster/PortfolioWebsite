<script>
    let { header, content } = $props();
    import Window from "./Window.svelte";
</script>

<style>
    .wave {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        aspect-ratio: 900/450;
        background-repeat: no-repeat;
        background-position: center;
        background-size: cover;
        background-image: url('bluelayeredwaves.svg');
    }
</style>

<section class="wave">
    <Window header={header} content={content}/>
</section>