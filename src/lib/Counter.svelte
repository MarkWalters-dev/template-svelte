<script>
  let count = $state(0);
  const increment = () => {
    count++;
  }
</script>

<button onclick={increment}>
	clicks: {count}
</button>
