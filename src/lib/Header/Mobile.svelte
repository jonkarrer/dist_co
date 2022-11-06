<span>
  <figure>
    <img
      class="logo_mobile"
      src="/header/logo-mobile-distilled-hair-co.png"
      alt="Distilled Hair Co logo"
    />
  </figure>

  <figure>
    <img class="burger_icon" src="/header/hamburger.svg" alt="menu icon" />
  </figure>
</span>

<style>
  span {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin: 12px auto;

    max-width: var(--mobile__max-width);
    padding: var(--mobile__bounds);
  }
  .logo_mobile {
    width: 50px;
  }

  @media (min-width: 1024px) {
    span,
    .logo_mobile,
    .burger_icon {
      display: none;
    }
  }
</style>
