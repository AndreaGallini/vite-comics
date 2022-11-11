<template>
  <div class="sfondo">
    <JumboComponent />
    <section class="row container">
      <CardsComponent v-for="(item, index) in cards" :key="index" :obj="item" />
      <button>Load more</button>
    </section>
  </div>
</template>

<script>
import CardsComponent from "./CardsComponent.vue";
import { immagini } from "../data/data";
import JumboComponent from "./JumboComponent.vue";
export default {
  components: {
    JumboComponent,
    CardsComponent,
  },
  data() {
    return {
      cards: immagini,
    };
  },
};
</script>

<style lang="scss" scoped>
@use "../assets/partials/variable" as *;
.sfondo {
  min-height: 400px;
  background-color: black;
}
h2 {
  color: white;
}
.row {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}
.container {
  max-width: 1170px;
  margin: 0 auto;
  margin-top: 50px;
}
button {
  width: 200px;
  height: 50px;
  color: white;
  background-color: $mainblue;
  border: 0;
  margin: 40px 0;
  cursor: pointer;
  text-transform: uppercase;
  font-weight: bold;
  font-size: 15px;

  &:hover {
    color: black;
  }
}
</style>
