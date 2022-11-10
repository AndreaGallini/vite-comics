<template>
  <div class="footer-main">
    <div class="left">
      <div>
        <div>
          <p>dc comics</p>
          <ul>
            <li>Character</li>
            <li>comics</li>
            <li>movies</li>
            <li>tv</li>
            <li>games</li>
            <li>videos</li>
            <li>news</li>
          </ul>
        </div>
        <div>
          <p>shop</p>
          <ul>
            <li>shop DC</li>
            <li>shop DC Collectibles</li>
          </ul>
        </div>
      </div>

      <div>
        <p>dc</p>
        <ul>
          <li>terms of Use</li>
          <li>Privacy policy(New)</li>
          <li>Ad Choices</li>
          <li>Advertising</li>
          <li>Jobs</li>
          <li>Subscriptions</li>
          <li>Talent Workshop</li>
          <li>CPSC Certificates</li>
          <li>Ratings</li>
          <li>Shop Help</li>
          <li>Contact Us</li>
        </ul>
      </div>
      <div>
        <p>Sites</p>
        <ul>
          <li>DC</li>
          <li>MAD Magazine</li>
          <li>DC Kids</li>
          <li>DC Universe</li>
          <li>DC Power Visa</li>
        </ul>
      </div>
    </div>
    <div class="right">
      <img src="../assets/img/dc-logo-bg.png" alt="" />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
@use "../assets/partials/variable" as *;

.footer-main {
  width: 100%;
  min-height: 300px;
  background-image: url(../assets/img/footer-bg.jpg);
  display: flex;
  justify-content: space-between;
  overflow: hidden;
  position: relative;
}
.left {
  flex-basis: 50%;
  display: flex;
  flex-direction: row;
}
.right {
  flex-basis: 50%;

  img {
    position: absolute;
    top: -100px;
    overflow: hidden;
  }
}
p {
  color: white;
  text-transform: uppercase;
  font-weight: bold;
  font-size: 1.2rem;

  margin: 0.5rem 30px;
  margin-top: 40px;
}
li {
  color: $greytext;
  text-transform: capitalize;
  margin-bottom: 0.3rem;
  list-style: none;
}
ul {
  margin: 0 30px;
  margin-bottom: 40px;
}
</style>
