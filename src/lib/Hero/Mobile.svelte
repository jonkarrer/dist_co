<script>
  import Button from "../common/Button.svelte";
</script>

<div class="wrapper">
  <img
    src="/hero/brunette-extensions-distilled-hair-co.jpg"
    alt="stunning brunette extensions"
  />
  <article>
    <h2>Professional Luxury Color and Extensions</h2>
    <p>
      We’ve taken the art of color and hair extensions to the next level. We
      achieve high end looks for our guests by making extensions and color blend
      with your natural beauty.
    </p>
    <Button text="Consultation" align="center" />
  </article>
</div>

<style>
  .wrapper {
    max-width: var(--mobile__max-width);
    padding: var(--mobile__bounds);
    margin: auto;
  }
  img {
    width: 100%;
    border-radius: var(--image_radius);
  }
  article {
    --gap: 32px;
    display: grid;
    place-items: center;
    text-align: center;
    gap: var(--gap);

    margin: var(--gap) 0;
  }
  /*
***********************************************************
* LG
***********************************************************
*/
  @media (min-width: 1024px) {
    .wrapper {
      display: none;
    }
  }
</style>
