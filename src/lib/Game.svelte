<script>
  let count = 0
  const increment = () => {
    count += 1
  }

  const down = () => {
    count -= 1
  }
</script>

<h1>Clicks: {count}</h1>

<button on:click={increment}>
  +
</button>

<button on:click={down}>
  -
</button>

