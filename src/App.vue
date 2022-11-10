<template>
  <div class="container">
    <HeaderComponent />
    <MainComponent />
    <FooterTopComponent />
    <FooterComponent />
    <FooterBottomComponent />
  </div>
</template>

<script>
import HeaderComponent from "./components/HeaderComponent.vue";
import FooterTopComponent from "./components/FooterTopComponent.vue";
import FooterBottomComponent from "./components/FooterBottomComponent.vue";
import FooterComponent from "./components/FooterComponent.vue";
import MainComponent from "./components/MainComponent.vue";

export default {
  components: {
    HeaderComponent,
    FooterTopComponent,
    FooterBottomComponent,
    FooterComponent,
    MainComponent,
  },
};
</script>

<style lang="scss" scoped></style>
