<script>
  import Header from "./lib/Header/Header.svelte";
  import Hero from "./lib/Hero/Hero.svelte";
  import Extensions from "./lib/Extensions/Extensions.svelte";
  import About from "./lib/About/About.svelte";
</script>

<Header />
<Hero />
<main>
  <Extensions />
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
      max-width: unset;
      padding: 0 var(--desktop__bounds);
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
