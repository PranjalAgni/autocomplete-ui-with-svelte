<script lang="ts">
  let count: number = 0;
  const increment = () => {
    count += 1;
  };
  const decrement = () => {
    count -= 1;
  };
</script>

<h3>count is 🔄 {count}</h3>
<button on:click={increment}> Increment </button>

<button on:click={decrement}> Decrement </button>
