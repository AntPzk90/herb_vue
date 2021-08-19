<template>
  <div id="app">
    <AppMain />
    <AppMainEn />
  </div>
</template>

<script>
import AppMain from "./components/map1/MainScreen.vue";

import AppMainEn from "./components/map2/MainScreenEn.vue";

export default {
  name: "App",
  components: {
    AppMain,
    AppMainEn,
  },
};
</script>

<style>
#app {
}
</style>
