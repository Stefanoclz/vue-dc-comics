<template>
  <div class="top">
    <div class="container">
      <div class="merch">
        <img src="../assets/buy-comics-digital-comics.png" alt="" />
        <a href="#">DIGITAL COMICS</a>
      </div>
      <div class="merch">
        <img src="../assets/buy-comics-merchandise.png" alt="" />
        <a href="#">DIGITAL MERCHANDISE</a>
      </div>
      <div class="merch">
        <img src="../assets/buy-comics-subscriptions.png" alt="" />
        <a href="#">DIGITAL SUBSCRIPTION</a>
      </div>
      <div class="merch">
        <img src="../assets/buy-comics-shop-locator.png" alt="" />
        <a href="#">DIGITAL COMIC SHOP LOCATOR</a>
      </div>
      <div class="merch">
        <img src="../assets/buy-dc-power-visa.svg" alt="" />
        <a href="#">DC POWER VISA</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "topFooter",
};
</script>

<style scoped lang="scss">
.top {
  background-color: #0282f9;
}

.container {
  display: flex;
  margin: auto;
  width: 70%;
  text-align: center;
  padding: 40px 20px;
  justify-content: space-evenly;

  .merch {
    display: flex;
    align-items: center;
    column-gap: 20px;
    color: white;

    img {
      width: 40px;
    }

    a {
      font-size: 13px;
      color: white;
      text-decoration: none;
    }
  }
}
</style>