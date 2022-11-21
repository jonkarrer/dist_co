<script>
  import Button from "../common/Button.svelte";
</script>

<section>
  <div class="wrapper">
    <img src="/training/training.jpg" alt="" />
    <article>
      <h2>Certified IBE Stylist</h2>
      <p>
        Our goal is for all guest coming into the suite to receive the best
        experience from the most knowledgeable stylist. All of our extension
        specialist have gone through the full IBE certification program, and
        have been professionally trained under myself, an Elite IBE aritist.
      </p>
      <Button text="Consultation" align="left" />
    </article>
  </div>
</section>

<style>
  img {
    width: 100%;
    margin-bottom: 20px;
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
      min-width: 450px;
      margin-bottom: 0px;
    }
  }
</style>
