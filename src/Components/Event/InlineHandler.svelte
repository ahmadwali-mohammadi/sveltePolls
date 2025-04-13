<script>
    let count = 0;

    function handleClick() {
        count += 1;
    }
</script>

<div>
    <p>Count: {count}</p>
    <button on:click={handleClick}>Increment</button>
</div>