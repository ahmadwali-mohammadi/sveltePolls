<script>
    let eventType = '';
    function handleClick(e) {
        eventType = e.type;
    }
</script>


<button on:click={handleClick}> Please Click me</button>
<p>Event Type: {eventType}</p>