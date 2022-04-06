<template>
  <div class="top">
    <div class="container">
      <div class="merch">
        <img src="../assets/buy-comics-digital-comics.png" alt="" />
        <p>DIGITAL COMICS</p>
      </div>
      <div class="merch">
        <img src="../assets/buy-comics-merchandise.png" alt="" />
        <p>DIGITAL MERCHANDISE</p>
      </div>
      <div class="merch">
        <img src="../assets/buy-comics-subscriptions.png" alt="" />
        <p>DIGITAL SUBSCRIPTION</p>
      </div>
      <div class="merch">
        <img src="../assets/buy-comics-shop-locator.png" alt="" />
        <p>DIGITAL COMIC SHOP LOCATOR</p>
      </div>
      <div class="merch">
        <img src="../assets/buy-dc-power-visa.svg" alt="" />
        <p>DC POWER VISA</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "topFooter",
};
</script>

<style scope lang="scss">
.top {
  background-color: #0282f9;
}

.container {
  display: flex;
  margin: auto;
  width: 70%;
  text-align: center;
  padding: 40px 20px;
  justify-content: space-around;

  .merch {
    display: flex;
    align-items: center;
    column-gap: 20px;
    color: white;

    img {
      width: 40px;
    }
  }
}
</style>