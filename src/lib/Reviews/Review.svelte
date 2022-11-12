<script>
  export let image;
  export let content;
  export let cite;
</script>

<div>
  <img src={image} alt="of a customer reviewing" />
  <p>"{content}"</p>
  <cite>{cite}</cite>
</div>

<style>
  div {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-auto-flow: row;
    align-items: center;

    width: 250px;
    margin: 80px auto;
  }
  img {
    width: 80px;
    grid-row: 1 / span 2;
  }
  p {
    font-size: 12px;
    width: 150px;
  }
  cite {
    font-size: 11px;
  }

  @media (min-width: 1024px) {
    div {
      place-items: center;

      flex: 1;
      margin: 80px auto;
    }
    img {
      width: 100px;
    }
    p {
      font-size: 14px;
      width: 190px;
    }
    cite {
      font-size: 16px;
      width: 100%;
    }
  }
</style>
