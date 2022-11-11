<script>
  export let image;
  export let content;
  export let cite;
</script>

<div>
  <img src={image} alt="of a customer" />
  <p>"{content}"</p>
  <cite>{cite}</cite>
</div>

<style>
  div {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-auto-flow: row;
    align-items: center;

    width: 265px;
    margin: 100px auto;
  }
  img {
    width: 90px;
    grid-row: 1 / span 2;
  }
  p {
    font-size: 12px;
    width: 150px;
  }
  cite {
    font-size: 11px;
  }
</style>
