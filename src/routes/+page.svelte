<script>
    function handleClick() {
        window.document.body.classList.toggle('dark-mode');
        light = !light;
        mode = light ? "Change to DARK mode" : "Change to LIGHT mode";
    }

    let mode = "Change to DARK mode";
    let light = true;
    
</script>

<!-- <button on:click={handleClick}>{mode}</button> -->

<h1>WELCOME</h1>

<style>
    :global(body.dark-mode) {
        background-color: #1d3040;
        color: #bfc2c7;
    }
</style>