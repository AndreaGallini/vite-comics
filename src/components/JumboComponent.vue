<template>
  <div class="jumbo">
    <div class="btn">
      <p>Current series</p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
@use "../assets/partials/variable" as *;
.jumbo {
  background-image: url(/public/img/jumbotron.jpg);
  min-height: 400px;
  position: relative;
}
.btn {
  background-color: $mainblue;
  width: 220px;
  height: 60px;
  position: absolute;
  bottom: -30px;
  left: 350px;
  z-index: 100;
  display: flex;
  align-items: center;
  justify-content: center;
  p {
    color: white;
    text-transform: uppercase;
    font-weight: bolder;
    font-size: 20px;
  }
}
</style>
