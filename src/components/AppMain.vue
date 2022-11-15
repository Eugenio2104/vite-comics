<script>
export default {
  name: "AppMain",
};
</script>


<template>
  <main>
    <div class="container">
      <div class="box">
        <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
        <span> DIGITAL COMICS </span>
      </div>
      <div class="box">
        <img src="../assets/img/buy-comics-merchandise.png" alt="" />
        <span> DC Merchandise </span>
      </div>
      <div class="box">
        <img src="../assets/img/buy-comics-subscriptions.png" alt="" />
        <span> subscription </span>
      </div>
      <div class="box">
        <img src="../assets/img/buy-comics-shop-locator.png" alt="" />
        <span> comic shop locator </span>
      </div>
      <div class="box">
        <img src="../assets/img/buy-dc-power-visa.svg" alt="" />
        <span> dc power visa </span>
      </div>
    </div>
  </main>
</template>


<style lang="scss" scoped>
@use "../style/partials/variables" as *;
@use "../style/partials/mixin" as *;

.container {
  background-color: $primary-color;
}
</style>