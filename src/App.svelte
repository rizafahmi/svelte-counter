<script>
  let counter = 0;
  function increment() {
    counter = counter + 1;
  }
  function reset() {
    counter = 0;
  }
</script>

<style>
  h1 {
    color: mediumaquamarine;
  }
</style>

<h1>Svelte Counter</h1>
<button on:click={increment}>Clicked {counter}x</button>
<button on:click={reset}>Reset Counter</button>
