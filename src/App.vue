<template>
  <div class="container">
    <HeaderComponent />
    <FooterTopComponent />
    <FooterBottomComponent />
  </div>
</template>

<script>
import HeaderComponent from "./components/HeaderComponent.vue";
import FooterTopComponent from "./components/FooterTopComponent.vue";
import FooterBottomComponent from "./components/FooterBottomComponent.vue";

export default {
  components: {
    HeaderComponent,
    FooterTopComponent,
    FooterBottomComponent,
  },
};
</script>

<style lang="scss" scoped></style>
