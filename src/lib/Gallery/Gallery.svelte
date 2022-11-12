<script>
  import Button from "../common/Button.svelte";
</script>

<section>
  <div class="wrapper">
    <img class="left_top" src="/gallery/left_top.jpg" alt="" />
    <img class="left_bottom" src="/gallery/left_bottom.jpg" alt="" />
    <img class="right" src="/gallery/right.jpg" alt="" />
    <img class="bottom" src="/gallery/bottom.jpg" alt="" />
    <img class="bottom_right" src="/gallery/bottom_right.jpg" alt="" />

    <img class="bottom_left" src="/gallery/bottom_left.jpg" alt="" />
  </div>
  <Button text="Instagram" align="center" />
</section>

<style>
  .wrapper {
    display: grid;
    grid-template-columns: 50% 1fr;
    grid-auto-flow: row;

    padding-bottom: 60px;
  }
  img {
    border-radius: 0px;
    width: 100%;
  }
  .left_bottom {
    align-self: end;
  }
  .right {
    padding-left: 6%;
    grid-column: 2;
    grid-row: 1 / span 2;
  }
  .bottom {
    grid-column: 1 / span 2;
    margin: 12px 0;
  }
  .bottom_left {
    padding-left: 6px;
  }
  .bottom_right {
    padding-right: 6px;
  }

  /*
***********************************************************
* LG
***********************************************************
*/
  @media (min-width: 1024px) {
    .wrapper {
      display: grid;
      grid-template-columns: 50% 1fr;
      grid-auto-flow: row;
      gap: 32px;

      padding-bottom: 60px;
    }
    img {
      border-radius: 0px;
      width: 100%;
      height: 100%;
    }
    .left_bottom {
      align-self: end;
    }
    .right {
      padding-left: 0%;
      grid-column: 2;
      grid-row: 1 / span 2;
    }
    .bottom {
      grid-column: 1 / span 2;
      margin: 0;
    }
    .bottom_left {
      padding-left: 0px;
    }
    .bottom_right {
      padding-right: 0px;
    }
  }
</style>
