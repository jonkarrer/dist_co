<div class="wrapper">
  <article class="title">
    <h3>
      I love making woman happy about their hair from my cozy private suite.
    </h3>
    <img
      src="/about/good-vibes-distilled-hair-co.jpg"
      alt="owner of Distilled Hair Co rocking blonde extensions and a good vibes only shirt"
    />
  </article>

  <article class="bio">
    <img
      src="/about/amanda-gautreau-distilled-hair-co.jpg"
      alt="owner of Distilled Hair Co styling brunette hair"
    />

    <div>
      <p>
        This will be a paragraph describing amanda, how she got here, where she
        has been. This will also describe the salon and why it is so nice. Maybe
        even where it is. this will be a bit longer than normal paragraphs,
        because of the dual bio.
      </p>

      <cite> Amanda Gautreau </cite>
    </div>
  </article>
</div>

<style>
  .wrapper {
    margin: auto;
  }
  .title {
    display: grid;
    place-items: center;
    gap: 14px;
    grid-template-columns: 1fr 1.2fr;

    margin-bottom: 50px;
  }
  img {
    width: 100%;
  }
  h3 {
    text-align: center;
  }

  .bio {
    display: grid;
    grid-template-columns: 1.2fr 1fr;
    gap: 14px;
    place-items: center;
  }

  p {
    font-size: calc(0.3vw + 13px);
  }
  cite {
    display: block;

    width: 100%;
    padding-top: 10px;

    font-size: 14px;
    text-align: right;
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
