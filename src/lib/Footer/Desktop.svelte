<footer>
  <div class="wrapper">
    <div class="header">
      <span>
        <img src="/footer/white_logo.svg" alt="distilled hair co logo" />
        <h4>Consultation</h4>
        <h4>Training</h4>
        <h4>FAQs</h4>
      </span>
      <span>
        <h4>i.b.e website</h4>
        <h4>instagram</h4>
        <h4>facebook</h4>
      </span>
    </div>

    <address>
      Distilled Hair Co <br />
      Located inside Mera Salon Suites<br />
      210 Louisiana 30 W<br />
      Gonzales, LA 70737
    </address>

    <div class="email">
      <a href="/">distilledhairco@gmail.com</a>
    </div>
  </div>
</footer>

<style>
  .wrapper {
    display: none;
  }

  /* LG */
  @media (min-width: 1024px) {
    footer {
      position: relative;
      background-image: url("/footer/footer_background.jpg");
      background-size: cover;
      background-position: center;

      height: 500px;
    }
    .wrapper {
      display: block;
      background-color: rgba(0, 0, 0, 0.5);
      height: 100%;

      color: white;
    }
    .header {
      display: flex;
      align-items: center;
      justify-content: space-between;

      padding: 40px;
    }
    .header span {
      display: flex;
      align-items: center;
      gap: 30px;
    }
    .header h4 {
      font-size: 20px;
    }

    address {
      font-style: normal;

      position: absolute;
      bottom: 120px;
      left: 40px;
    }
    .email {
      position: absolute;
      bottom: 60px;
      left: 40px;
    }
  }
</style>
