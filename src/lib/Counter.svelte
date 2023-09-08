<script lang="ts">
  let count: number = 0;
  const increment = () => {
    count += 1;
  };
  const minus = () => {
    count -= 1;
  };
</script>

<button on:click={increment}> add </button>
<h3>
  count is {count}
</h3>
<button on:click={minus}>minus</button>
