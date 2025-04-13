<script>
let count = 0;

const  increment=() =>{
    count += 1;
}

const decrement=() =>{
    count -= 1;
}
</script>

<div>
    <h1>Counter: {count}</h1>
    <button on:click={increment}>Increment</button>
    <button on:click={decrement}>Decrement</button>
</div>

<style>
div {
    text-align: center;
    margin-top: 20px;
}

button {
    margin: 5px;
    padding: 10px 20px;
    font-size: 16px;
    cursor: pointer;
}
</style>
