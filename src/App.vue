<template>
  <div class="container">
    <HeaderComponent />
    <FooterTopComponent />
  </div>
</template>

<script>
import HeaderComponent from "./components/HeaderComponent.vue";
import FooterTopComponent from "./components/FooterTopComponent.vue";

export default {
  components: {
    HeaderComponent,
    FooterTopComponent,
  },
};
</script>

<style lang="scss" scoped></style>
