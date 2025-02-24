<script>
    let { header, content } = $props();
</script>

<style>
    .window {
        display: flex;
        flex-direction: column;
        width: 40%;
        height: 40%;
        background-color: #2d2d2d;
        border-radius: 20px;
        overflow: hidden;
        margin-top: 350px;
    }

    .window-header {
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding: 8px;
        background-color: #4d4d4d;
    }

    .window-header-buttons {
        display: flex;
        gap: 8px;
    }

    .nav-button {
        width: 12px;
        height: 12px;
        border-radius: 50%;
    }

    .close { background-color: #ff5f57; } /* Red */
    .minimize { background-color: #ffbd2e; } /* Yellow */
    .maximize { background-color: #28c840; } /* Green */

    .window-header-title {
        color: white;
        font-size: 14px;
        flex: 1;
        text-align: center;
    }

    .window-content {
        flex-grow: 1;
        padding: 15px;
        color: white;
    }
</style>

<div class="window">
    <div class="window-header">
        <div class="window-header-buttons">
            <span class="nav-button close"></span>
            <span class="nav-button minimize"></span>
            <span class="nav-button maximize"></span>
        </div>
        <div class="window-header-title">
            {header}
        </div>
    </div>
    <div class="window-content">
        {content}
    </div>
</div>
