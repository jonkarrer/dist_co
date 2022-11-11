<div class="wrapper">
  <img class="image_main" src="/footer/footer_mobile.jpg" alt="" />

  <div class="logo_container">
    <img
      class="logo_container--logo"
      src="/header/logo-mobile-distilled-hair-co.png"
      alt="distilled co logo"
    />
    <span class="social_container">
      <img
        class="social_container--insta"
        src="/footer/insta.svg"
        alt="distilled co logo"
      />
      <img
        class="social_container--facebook"
        src="/footer/facebook.svg"
        alt="distilled co logo"
      />
    </span>
  </div>

  <ul class="guide">
    <li class="guide_group">
      <h3>Sitemap</h3>
      <a href="/">About Us</a>
      <a href="/">FAQ</a>
      <a href="/">Care Guide</a>
      <a href="/">IBE</a>
    </li>

    <li class="guide_group">
      <h3>Contact</h3>
      <a href="/">distilledhairco@gmail.com</a>
      <a href="/">Instagram</a>
      <a href="/">Facebook</a>
    </li>

    <li class="guide_group">
      <h3>Services</h3>
      <a href="/">Extensions</a>
      <a href="/">Consultation</a>
      <a href="/">Training</a>
    </li>

    <li class="guide_group">
      <h3>Location</h3>
      <address>
        Distilled Hair Co <br />
        Located inside Mera Salon Suites<br />
        210 Louisiana 30 W<br />
        Gonzales, LA 70737
      </address>
    </li>
  </ul>
</div>

<style>
  .image_main {
    width: 100%;
  }

  .logo_container {
    display: flex;
    justify-content: space-between;

    margin: 40px 0;
  }
  .logo_container--logo {
    width: 100px;
  }

  .social_container {
    display: flex;
    gap: 20px;
  }
  .social_container--insta {
    width: 40px;
  }
  .social_container--facebook {
    width: 40px;
    justify-self: flex-end;
  }

  .guide {
    display: grid;
    gap: 30px;
  }
  .guide_group {
    display: grid;
    gap: 16px;
  }
  .guide_group h3 {
    font-size: calc(0.3vw + 24px);
    border-bottom: 1px solid var(--super_dark);
    width: 100px;
  }
</style>
