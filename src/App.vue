<template>
  <div id="app">
    <app-header></app-header>
  </div>
</template>

<script>
export default {
  components: {
    "app-header": () => import("./components/app-header.vue"),
    "navigation": () => import("./components/navigation.vue")
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css?family=Lato:100,300,300i,400');
@import "./styles/normalize.scss";
@import "./styles/grid.scss";
@import "./variables.scss";
@import "./App.scss";
</style>
