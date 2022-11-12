<script>
  import Button from "../common/Button.svelte";
</script>

<section>
  <div class="wrapper">
    <img src="/products/products.jpg" alt="" />
    <article>
      <h2>Something about the products</h2>
      <p>
        This will be about the salon products and how important hair care is.
        Sell the products and invite them in..
      </p>
      <Button text="Guide" align="right" />
    </article>
  </div>
</section>

<style>
  img {
    width: 100%;
  }
  article * {
    margin: 32px 0;
    text-align: right;
  }
  /* LG */
  @media (min-width: 1024px) {
    article * {
      margin: 38px 0;
    }
    .wrapper {
      display: flex;
      align-items: center;
      gap: 40px;
    }
    img {
      width: 60%;
      order: 2;
    }
  }
</style>
