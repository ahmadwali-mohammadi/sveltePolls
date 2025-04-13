<script>
    function handleOuterClick() {
      console.log("Outer clicked (capturing)");
    }
  
    function handleInnerClick() {
      console.log("Inner clicked");
    }
  </script>
  
  <div on:click|capture={handleOuterClick}>
    Outer
    <button on:click={handleInnerClick}>Inner</button>
  </div>
  