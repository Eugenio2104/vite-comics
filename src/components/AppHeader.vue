<script>
export default {
  name: "AppHeader",
  data() {
    return {
      menu: [
        {
          text: "characters",
          href: "#",
          current: "false",
        },
        {
          text: "comics",
          href: "#",
          current: "active",
        },
        {
          text: "movies",
          href: "#",
          current: "false",
        },
        {
          text: "tv",
          href: "#",
          current: "false",
        },
        {
          text: "games",
          href: "#",
          current: "false",
        },
        {
          text: "collectibles",
          href: "#",
          current: "false",
        },
        {
          text: "videos",
          href: "#",
          current: "false",
        },
        {
          text: "fans",
          href: "#",
          current: "false",
        },
        {
          text: "news",
          href: "#",
          current: "false",
        },
        {
          text: "shop",
          href: "#",
          current: "false",
        },
      ],
    };
  },
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
          <li v-for="(link, index) in menu" :key="index">
            <a
              :class="{ active: link.current == 'active' }"
              :href="link.href"
              >{{ link.text }}</a
            >
          </li>
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
          text-transform: uppercase;
          text-decoration: none;
          &.active,
          &:hover {
            color: $primary-color;
            border-bottom: 4px solid $primary-color;
          }
        }
      }
    }
  }
}
</style>
