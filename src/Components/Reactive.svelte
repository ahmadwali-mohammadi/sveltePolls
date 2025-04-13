<script>
    let firstName ='Ahmad wali';
    let lastName = 'Mohammadi';
    let beltColor='black';


   

    const handleChange = (event) => {
        beltColor = event.target.value;
    }

</script>


<div class="container">
    <h1>Reactive Variables</h1>
    <p>First Name: {firstName}</p>
    <p>Last Name: {lastName}</p>
    <p>Belt Color: {beltColor}</p>

    <label for="beltColor">Choose a belt color:</label>
    <select id="beltColor" on:change={handleChange}>
        <option value="black">Black</option>
        <option value="blue">Blue</option>
        <option value="red">Red</option>
        <option value="green">Green</option>
    </select>

    </div>