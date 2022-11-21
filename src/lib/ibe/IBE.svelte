<section>
  <div class="wrapper">
    <img src="/ibe/ibe_elite.gif" alt="ibe gif" />
    <article>
      <p>Learn about my method</p>
      <button>
        <a
          href="https://www.invisiblebeadextensions.com"
          target="_blank"
          rel="noreferrer">Explore</a
        >
      </button>
    </article>
  </div>
</section>

<style>
  section {
    background: black;
  }
  .wrapper {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    margin: auto;
    padding: 40px 0;
  }
  img {
    width: 80px;
  }
  article {
    display: grid;
    gap: 20px;
  }
  article p {
    color: white;
  }
  a {
    color: var(--super_dark);
  }
  article button {
    width: 50%;
    padding: 5px;
    margin: auto;

    background-color: var(--light_shade);

    border: none;
    border-radius: 3px;
  }
  article button:hover {
    cursor: pointer;
  }

  /*Lg*/
  @media (min-width: 1024px) {
    .wrapper {
      max-width: 500px;
      padding: 50px 0;
    }
    article {
      gap: 30px;
    }
    img {
      width: 160px;
    }
    p {
      font-size: 22px;
    }
    article button {
      width: 50%;
      padding: 5px;
      margin: auto;
      font-size: var(--xs);
    }
    article button {
      width: 50%;
      padding: 5px;
      margin: auto;
      font-size: var(--sm);
    }
  }
</style>
