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
        <ul>
          <li><a href="#">CHARACTERS</a></li>
          <li><a class="active" href="#">COMICS</a></li>
          <li><a href="#">MOVIES</a></li>
          <li><a href="#">TV</a></li>
          <li><a href="#">GAMES</a></li>
          <li><a href="#">COLLECTIBLES</a></li>
          <li><a href="#">VIDEOS</a></li>
          <li><a href="#">FANS</a></li>
          <li><a href="#">NEWS</a></li>
          <li><a href="#">SHOP</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>


<style lang="scss" scoped>
@use "../style/partials/variables" as *;
@use "../style/partials/mixin" as *;
.container {
  height: 100px;
  @include centralFlex("vertical");
  @include centralFlex("space-between");
  .logo {
    img {
      width: 60px;
    }
  }
  nav {
    height: 100%;
    @include centralFlex;
    ul {
      @include centralFlex("horizzontal");
      li {
        list-style: none;
        padding-left: 20px;
        a {
          font-weight: 600;
          font-size: 0.9rem;
          color: #464646;
          text-decoration: none;
          &.active,
          &:hover {
            color: $primary-color;
          }
        }
      }
    }
  }
}
</style>
