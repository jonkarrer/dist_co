<script>
  import Button from "../common/Button.svelte";
</script>

<div class="wrapper">
  <img
    src="/hero/brunette-extensions-distilled-hair-co.jpeg"
    alt="stunning brunette extensions"
  />
  <article>
    <h2>This will be about extensions</h2>
    <p>
      This will be about the extensions. Focused on the sales pitch of the
      extensions.
    </p>
    <Button text="Consultation" align="center" />
  </article>
</div>

<style>
  .wrapper {
    max-width: var(--mobile__max-width);
    padding: var(--mobile__bounds);
    margin: auto;
    margin-bottom: 100px;
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
