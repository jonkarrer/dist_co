<script>
  import Review from "./Review.svelte";
</script>

<section>
  <div class="wrapper">
    <Review
      image="/reviews/tristyn_review.png"
      content="I started going to her about 2 years ago when my hair was at its worst! Changed my life!"
      cite="Tristyn"
    />
    <Review
      image="/reviews/abbie_review.png"
      content="I’ve been coming to Amanda for over a year and have not been disappointed."
      cite="Abbie"
    />
    <Review
      image="/reviews/summer_review.png"
      content="Installed my extensions with the IBE method and made everything blend beautifully"
      cite="Summer"
    />
  </div>
</section>

<style>
  /* LG */
  @media (min-width: 1024px) {
    .wrapper {
      display: flex;
      align-items: center;
      justify-content: space-between;
    }
  }
</style>
