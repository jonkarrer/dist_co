<div class="wrapper">
  <img
    src="/about/amanda-gautreau-distilled-hair-co.jpg"
    alt="owner of Distilled Hair Co styling brunette hair"
  />
  <article class="bio">
    <h3>
      I love making woman happy about their hair from my cozy private suite.
    </h3>
    <div class="content">
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
    display: none;
  }
  /*
***********************************************************
* LG
***********************************************************
*/
  @media (min-width: 1024px) {
    .wrapper {
      display: grid;
      grid-template-columns: 1fr 1fr;
    }
    h3 {
      text-align: center;
      margin: 60px auto;
      width: 93%;
      max-width: 450px;
    }
    img {
      height: 100vh;
    }
    .content {
      margin-left: 40px;
      margin-top: 35vh;
      width: 218px;
      line-height: 1.3;
    }
    cite {
      display: block;

      width: 100%;
      padding-top: 10px;

      font-size: 18px;
      text-align: right;
    }
  }
</style>
