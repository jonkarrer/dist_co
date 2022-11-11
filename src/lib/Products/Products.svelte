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
    </article>
    <Button text="Guide" align="right" />
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
</style>
