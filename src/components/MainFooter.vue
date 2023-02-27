<script>
export default {};
</script>
<template>
  <div class="bg-blue">
    <div class="container">
      <div class="card">
        <img
          src="../assets/buy-comics-digital-comics.png"
          alt="" />
        <span>DIGITAL COMICS</span>
      </div>

      <div class="card">
        <img
          src="../assets/buy-comics-merchandise.png"
          alt="" />
        <span>DC MERCHANDISE</span>
      </div>

      <div class="card">
        <img
          src="../assets/buy-comics-subscriptions.png"
          alt="" />
        <span>SUBSCRIPTION</span>
      </div>

      <div class="card">
        <img
          src="../assets/buy-comics-shop-locator.png"
          alt="" />
        <span>COMIC SHOP LOCATOR</span>
      </div>

      <div class="card">
        <img
          class="visa"
          src="../assets/buy-dc-power-visa.svg"
          alt="" />
        <span>DC POWER VISA</span>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use "../assets/styles/variables.scss" as *;
@use "../assets/styles/mixins.scss" as *;

.bg-blue {
  background-color: $blue;

  .container {
    @include d-flex();
    column-gap: 10px;
    justify-content: space-between;

    .card {
      @include d-flex();
      align-items: center;
      color: white;
      font-size: 0.7rem;

      img {
        height: 40%;
        margin-right: 10px;
      }
      .visa {
        height: 30%;
      }
    }
  }
}
</style>
