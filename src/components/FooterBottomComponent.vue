<template>
  <div class="footer-bottom">
    <button>sign-up now!</button>
    <div class="destra">
      <h2>follow us</h2>
      <img src="../assets/img/footer-facebook.png" alt="" />
      <img src="../assets/img/footer-twitter.png" alt="" />
      <img src="../assets/img/footer-youtube.png" alt="" />
      <img src="../assets/img/footer-pinterest.png" alt="" />
      <img src="../assets/img/footer-periscope.png" alt="" />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
@use "../assets/partials/variable" as *;
.footer-bottom {
  display: flex;
  justify-content: space-around;
  height: 100px;
  align-items: center;
  background-color: $lightgrey;
  z-index: 100;
  img {
    margin: 5px;
  }
}
.destra {
  display: flex;
  align-items: center;
}
h2 {
  text-transform: uppercase;
  color: $mainblue;
  padding-right: 20px;
  font-weight: bold;
}
button {
  width: 130px;
  height: 50px;
  background-color: transparent;
  border: 3px solid $mainblue;
  text-transform: uppercase;
  color: white;
  font-weight: bold;
  cursor: pointer;
  transition: all 0.5s;
  &:hover {
    background-color: $mainblue;
    color: white;
  }
}

.container {
  max-width: 1170px;
  margin: 0 auto;
}
</style>
