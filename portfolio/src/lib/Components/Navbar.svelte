<script>

</script>

<style>
    .nav-container {
        display: flex;
        position: sticky;
        top: 0;
        z-index: 100;
        flex-direction: row;
        justify-content: center;
        text-decoration: none;
        background-color: #1c1c1c;
        padding: 5px;
    }

    nav {
        display: flex;
        flex-direction: row;
        gap: 20px;
    }

    nav a {
        font-weight: bold;
        position: relative;
        text-decoration: none;
        color: #333;
        padding: 5px 0;
        transition: color 0.3s ease-in-out;
    }

    nav a:hover {
        color: #007BFF;
    }

    nav a::after {
        content: "";
        position: absolute;
        left: 0;
        bottom: 0;
        width: 100%;
        height: 3px;
        background-color: #007BFF;
        transform: scaleX(0);
        transform-origin: right;
        transition: transform 0.3s ease-in-out;
    }

    nav a:hover::after {
        transform: scaleX(1);
        transform-origin: left;
    }
</style>

<div class="nav-container">
    <nav>
        <a href="#home">Home</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
</div>