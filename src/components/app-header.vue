<template>
  <header>
    <navigation></navigation>
    <div>
      <h1>Goodbye junk food<br>Hello super healthy meals</h1>
      <a class="btn btn-full">I'm hungry</a>
      <a class="btn btn-ghost">Show me more</a>
    </div>
  </header>
</template>

<script>
export default {
  components:  {
    navigation: () => import("./navigation.vue")
  }
}
</script>


<style lang="scss" scoped>
  header {
    background-image: linear-gradient(to bottom right, rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), url('../assets/hero.jpg');
    background-size: cover;
    background-position: center;
    height: 100vh;
  }

  h1 {
    margin: 0 0 20px 0;
    color: #fff;
    font-size: 2.5rem;
    font-weight: 300;
    text-transform: uppercase;
    letter-spacing: 1px;
    word-spacing: 4px;
  }

  div {
    position: absolute;
    width: 1140px;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
  }
</style>