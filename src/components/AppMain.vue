<script>
import AppCards from './AppCards.vue';

export default {
  components: {
    AppCards,
  },
};
</script>

<template>
  <div class="main">
    <div class="content">
      <AppCards />
    </div>
    <div class="icon-container">
      <div class="icon-main">
        <div class="comics-logo">
          <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
          <h5>DIGITAL COMICS</h5>
        </div>
        <div class="comics-logo">
          <img src="../assets/img/buy-comics-merchandise.png" alt="" />
          <h5>DC MERCHANDISE</h5>
        </div>
        <div class="comics-logo">
          <img src="../assets/img/buy-comics-subscriptions.png" alt="" />
          <h5>SUBSCRIPTION</h5>
        </div>
        <div class="comics-logo">
          <img src="../assets/img/buy-comics-shop-locator.png" alt="" />
          <h5>COMIC SHOP LOCATOR</h5>
        </div>
        <div class="comics-logo">
          <img src="../assets/img/buy-dc-power-visa.svg" alt="" />
          <h5>DC POWER VISA</h5>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.main {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;

  .content {
    display: flex;
    justify-content: center;
    align-content: center;
    color: white;
    // height: 15vh;

    h2 {
      display: flex;
      justify-content: center;
      align-items: center;
    }
  }

  .icon-container {
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    background-color: #0082f9;
    height: 15vh;
    width: 100%;

    .icon-main {
      display: flex;

      .comics-logo {
        display: flex;
        align-items: center;
        gap: 8px;

        img {
          max-width: 20%;
        }
      }
    }

    h2 {
      display: flex;
      justify-content: center;
      align-items: center;
    }
  }
}
</style>
