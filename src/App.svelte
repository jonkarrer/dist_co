<script>
  import Header from "./lib/Header/Header.svelte";
  import Hero from "./lib/Hero/Hero.svelte";
  import About from "./lib/About/About.svelte";
</script>

<Header />
<Hero />
<main>
  <About />
</main>

<style>
  main {
    max-width: var(--mobile__max-width);
    padding: var(--mobile__bounds);
    margin: auto;
  }

  /*
***********************************************************
* LG
***********************************************************
*/
  @media (min-width: 1024px) {
    main {
      max-width: var(--desktop__max-width);
      padding: var(--desktop__bounds);
    }
  }

  /*
***********************************************************
* XL
***********************************************************
*/
  @media (min-width: 1280px) {
  }

  /*
***********************************************************
* 2XL
***********************************************************
*/
  @media (min-width: 1536px) {
  }
</style>
