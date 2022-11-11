<script>
  export let text;
  export let align;

  function alignButton() {
    if (align === "center") {
      return "center";
    }
    if (align === "right") {
      return "right";
    }
    return "left";
  }
</script>

<button class={alignButton()}>
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
  .center {
    margin: auto;
  }
  .right {
    float: right;
  }
</style>
