<template>
  <nav>
    <img src="@/assets/logo-white.png" alt="omnifood logo">
    <ul>
      <li><a href="#">Food delivery</a></li>
      <li><a href="#">How it works</a></li>
      <li><a href="#">Our cities</a></li>
      <li><a href="#">Sign up</a></li>
    </ul>
  </nav>
</template>

<style lang="scss" scoped>
  @import "@/variables.scss";
  img {
    height: 100px;
    width: auto;
    float: left;
    margin-top: 1rem;
    margin-left: 4rem;
  }

  a,
  a:visited {
    color: #fff;
    text-decoration: none;
    text-transform: uppercase;
    font-size: 0.9rem;
    padding-top: 0.5rem;
    padding-bottom: 0.5rem;
    border-bottom: 2px solid transparent;
    transition: border 0.2s;
  }

  a:hover,
  a:active {
    border-bottom: 2px solid $sBtnCol;
  }

  ul {
    float: right;
    margin-top: 3rem;
    margin-right: 6rem;
  }

  li {
    display: inline-block;
    margin-left: 2rem;
  }
</style>