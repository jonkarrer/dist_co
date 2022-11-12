<script>
  import Button from "../common/Button.svelte";
</script>

<section>
  <div class="wrapper">
    <article>
      <h1>Professional Luxury Extensions</h1>
      <p>
        The best hair you can afford, and installed by an Elite Invisible Bead
        Extension Artist.
      </p>
      <Button text="Consultation" align="center" />
    </article>

    <img
      class="larger"
      src="/extensions/brunette-extensions-distilled-hair-co.jpg"
      alt="stunning brunette extensions"
    />

    <img
      class="smaller"
      src="/about/good-vibes-distilled-hair-co.jpg"
      alt="owner of Distilled Hair Co rocking blonde extensions and a good vibes only shirt"
    />
  </div>
</section>

<style>
  .wrapper {
    display: none;
  }

  /* LG */
  @media (min-width: 1024px) {
    .wrapper {
      display: flex;
      align-items: center;
      justify-content: space-between;

      height: 100vh;
      max-height: 600px;
    }
    article {
      text-align: center;
      display: grid;

      gap: 60px;
    }
    p {
      width: 90%;
      margin: auto;
    }
    img.larger {
      width: 335px;
      padding: 0 20px;
    }
    img.smaller {
      width: 275px;
    }
  }

  /* XL */
  @media (min-width: 1280px) {
    .wrapper {
      display: flex;
      align-items: center;
      justify-content: space-between;

      height: 100vh;
    }
    article {
      text-align: center;
      display: grid;

      gap: 60px;
    }
    p {
      width: 90%;
      margin: auto;
    }
    img.larger {
      width: 380px;
      padding: 0 20px;
    }
    img.smaller {
      width: 315px;
    }
  }
</style>
