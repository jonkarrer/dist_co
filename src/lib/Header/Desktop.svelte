<span>
  <figure>
    <img
      src="/header/logo-desktop-distilled-hair-co.png"
      alt="Distilled Hair Co logo"
    />
  </figure>

  <nav>
    <a href="#about"> About </a>

    <a href="#extensions"> Extensions </a>

    <a href="#consultation"> Consultation </a>

    <a href="#guide"> Guide </a>
  </nav>
</span>

<style>
  span,
  nav,
  img {
    display: none;
  }

  /*
***********************************************************
* LG
***********************************************************
*/
  @media (min-width: 1024px) {
    span {
      position: absolute;
      width: 100%;

      padding: 0 70px;

      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    img {
      width: 110px;

      display: flex;
      justify-content: flex-start;
    }

    nav {
      display: flex;
      align-items: center;
      gap: 20px;

      /* Slightly not centered to the logo, moved it down */
      margin-top: 14px;
    }

    a {
      font-family: "Branch";
      font-size: 16px;
      text-decoration: none;
      color: var(--super_dark);
    }
  }
</style>
