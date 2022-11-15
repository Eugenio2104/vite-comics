<script>
import AppHeader from "./components/AppHeader.vue";
import AppFooter from "./components/AppFooter.vue";
import AppMain from "./components/AppMain.vue";
import AppJumbotron from "./components/AppJumbotron.vue";
import AppFooterBottom from "./components/AppFooterBottom.vue";

export default {
  name: "App",
  components: {
    AppHeader,
    AppFooter,
    AppMain,
    AppJumbotron,
    AppFooterBottom,
  },
};
</script>


<template>
  <AppHeader />
  <AppJumbotron />
  <AppMain />
  <AppFooter />
  <AppFooterBottom />
</template>


<style lang="scss">
@use "./style/general";
</style>