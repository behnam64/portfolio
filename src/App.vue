<template>
  <div id="app">
    <router-view />
    <div id="nav">
      <router-link to="">Home</router-link>
      <router-link to="/omnifood">omnifood</router-link>
    </div>
    
  </div>
</template>

<script>
  export default {
    data() {
      return {
        bool: true
      }
    },
    scripts: {
      isOnHome() {
        this.$route.path === "/";
      }
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