<script>
export default {
  name: "AppHeader",
};
</script>


<template>
  <header>
    <div class="container">
      <div class="logo">
        <img src="/dc-logo.png" alt="" />
      </div>
      <nav>
        <li><a href="#">CHARACTERS</a></li>
        <li><a href="#">COMICS</a></li>
        <li><a href="#">MOVIES</a></li>
        <li><a href="#">TV</a></li>
        <li><a href="#">GAMES</a></li>
        <li><a href="#">COLLECTIBLES</a></li>
        <li><a href="#">VIDEOS</a></li>
        <li><a href="#">FANS</a></li>
        <li><a href="#">NEWS</a></li>
        <li><a href="#">SHOP</a></li>
      </nav>
    </div>
  </header>
</template>


<style lang="scss" scoped>
.container {
  display: flex;
  justify-content: space-between;
  ul {
  }
}
</style>