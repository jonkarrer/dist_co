<script>
  export let text;
  export let margin;
</script>

<button style={`margin:${margin}`}>
  <a href="/">{text}</a>
</button>

<style>
  button {
    width: 137px;
    height: 44px;

    background-color: var(--light_shade);
    border: 1px solid var(--accent);
    border-radius: 3px;

    display: flex;
    align-items: center;
    justify-content: center;
  }
  a {
    color: var(--super_dark);
    font-size: 18px;
  }
</style>
