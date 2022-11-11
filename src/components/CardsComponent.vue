<template>
  <div class="card">
    <img :src="obj.thumb" />
    <p>{{ obj.series }}</p>
  </div>
</template>

<script>
export default {
  props: ["obj"],
};
</script>

<style lang="scss" scoped>
.card {
  flex-basis: calc(100% / 6);
  justify-content: center;

  img {
    width: 100%;
    padding: 1rem;
  }
  p {
    color: white;
    padding-left: 1rem;
    text-transform: uppercase;
    font-weight: bold;
  }
}
</style>
