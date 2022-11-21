<div class="wrapper">
  <article class="title">
    <h3>
      My passion is giving women the confidence boost by enhancing their natural
      hair.
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
        I knew that our town needed better hair! Seeing extensions done
        incorrectly really started to bother me, and I knew they could be
        better. After spending years on education and certifications, I am now
        at Platform Status for I.B.E. My extensions help woman feel confident
        about their look as I bring back thier natural hair.
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
