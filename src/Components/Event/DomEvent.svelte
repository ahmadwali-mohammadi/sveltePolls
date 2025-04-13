<script>
    let message = "";

    function handleClick() {
        message = "Button clicked!";
    }

    function handleMouseOver() {
        message = "Mouse is over the button!";
    }

    function handleMouseOut() {
        message = "Mouse left the button!";
    }
</script>

<div>
    <p>{message}</p>
    <button 
        on:click={handleClick} 
        on:mouseover={handleMouseOver} 
        on:mouseout={handleMouseOut}>
        Hover or Click Me
    </button>
</div>

<style>
    button {
        padding: 10px 20px;
        font-size: 16px;
        cursor: pointer;
    }

    p {
        margin-bottom: 10px;
        font-size: 18px;
    }
</style>