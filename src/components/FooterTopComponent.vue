<template>
  <div class="footer-top">
    <div class="card">
      <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
      <p>digital comics</p>
    </div>
    <div class="card">
      <img src="../assets/img/buy-comics-merchandise.png" alt="" />
      <p>dc merchandise</p>
    </div>
    <div class="card">
      <img src="../assets/img/buy-comics-subscriptions.png" alt="" />
      <p>subscription</p>
    </div>
    <div class="card">
      <img src="../assets/img/buy-comics-shop-locator.png" alt="" />
      <p>comic shop locator</p>
    </div>
    <div class="card">
      <img src="../assets/img/buy-dc-power-visa.svg" alt="" />
      <p>dc powered visa</p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
@use "../assets/partials/variable" as *;
.footer-top {
  background-color: $mainblue;
  width: 100%;
  height: 200px;
  display: flex;
  justify-content: space-around;
  align-items: center;
}
.card {
  display: flex;
  align-items: center;
  p {
    padding-left: 1rem;
    text-transform: uppercase;
    color: white;
  }
  img {
    width: 50px;
  }
}
</style>
