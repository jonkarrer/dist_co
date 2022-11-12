<script>
  import Button from "../common/Button.svelte";
</script>

<section>
  <div class="wrapper">
    <img src="/training/training.jpg" alt="" />
    <article>
      <h2>Something about IBE Training</h2>
      <p>
        This will be about the training program and how to enroll. Why train
        with amanda and how does it work.
      </p>
      <Button text="Training" align="left" />
    </article>
  </div>
</section>

<style>
  img {
    width: 100%;
  }
  article * {
    margin: 32px 0;
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
    }
  }
</style>
