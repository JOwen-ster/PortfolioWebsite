<script>
    let { header, content } = $props();
</script>


<style>
    .wave {
        aspect-ratio: 900/450;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        background-repeat: no-repeat;
        background-position: center;
        background-size: cover;
        background-image: url('purplelayeredwaves.svg');
    }
</style>

<section class="wave"></section>