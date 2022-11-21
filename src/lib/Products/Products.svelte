<script>
  import Button from "../common/Button.svelte";
</script>

<section>
  <div class="wrapper">
    <img src="/products/products.jpg" alt="" />
    <article>
      <h2>Products play a key role in your investment</h2>
      <p>
        Wether you are receiving a color service or getting a fresh install of
        extensions, home care products can protect your investment. We carry
        Goldie Locks and Kevin Murphy, each are salon grade products we use
        everyday.
      </p>
      <Button text="Guide" align="right" />
    </article>
  </div>
</section>

<style>
  img {
    width: 100%;
    margin-bottom: 20px;
  }
  article {
    text-align: right;
  }
  p {
    margin: 24px 0;
  }
  /* LG */
  @media (min-width: 1024px) {
    article {
      max-width: 470px;
    }
    .wrapper {
      display: flex;
      align-items: center;
      gap: 40px;
    }
    img {
      order: 2;
      min-width: 450px;
      margin-bottom: 0;
    }
  }
</style>
