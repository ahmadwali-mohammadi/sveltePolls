<script>
  import DomEvent from "./Components/Event/DomEvent.svelte";
  import Reactive from "./Components/Reactive.svelte";
  import Capturing from "./Components/Event/Capturing.svelte";
  import InlineHandler from "./Components/Event/InlineHandler.svelte";


</script>

<main>
	<InlineHandler />
</main>

<style>
	main {
text-align: center;
	padding: 1em;
		max-width: 240px;
	   margin: 0 auto;
	}

	

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>