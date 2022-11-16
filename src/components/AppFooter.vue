<script>
export default {
  name: "AppFooter",
};
</script>


<template>
  <footer>
    <div class="container">
      <div class="list-footer">
        <nav>
          <h3>DC COMICS</h3>
          <ul>
            <li>
              <a href="#">Characters</a>
            </li>
            <li>
              <a href="#">Comics</a>
            </li>
            <li>
              <a href="#">movies</a>
            </li>
            <li>
              <a href="#">TV</a>
            </li>
            <li>
              <a href="#">Games</a>
            </li>
            <li>
              <a href="#">Videos</a>
            </li>
            <li>
              <a href="#">news</a>
            </li>
          </ul>
          <h3>SHOP</h3>
          <ul>
            <li>
              <a href="#">Shop Dc</a>
            </li>
            <li>
              <a href="#">Shop DC Collectibles</a>
            </li>
          </ul>
        </nav>
      </div>
      <div class="list-footer">
        <nav>
          <h3>DC</h3>
          <ul>
            <li>
              <a href="#">Terms Of Use</a>
            </li>
            <li>
              <a href="#">Privacy policy(New)</a>
            </li>
            <li>
              <a href="#">Ad Choices</a>
            </li>
            <li>
              <a href="#">Adverstising</a>
            </li>
            <li>
              <a href="#">Jobs</a>
            </li>
            <li>
              <a href="#">Subscription</a>
            </li>
            <li>
              <a href="#">Talent Workshop</a>
            </li>
            <li>
              <a href="#">CPSC Certificates</a>
            </li>
            <li>
              <a href="#">Ratings</a>
            </li>
            <li>
              <a href="#">Shop Help</a>
            </li>
            <li>
              <a href="#">Contact Us</a>
            </li>
          </ul>
        </nav>
      </div>
      <div class="list-footer">
        <nav>
          <h3>SITES</h3>
          <ul>
            <li>
              <a href="#">DC</a>
            </li>
            <li>
              <a href="#">MAD Magazine</a>
            </li>
            <li>
              <a href="#">DC Kids</a>
            </li>
            <li>
              <a href="#">DC Universe</a>
            </li>
            <li>
              <a href="#">DC Power Visa</a>
            </li>
          </ul>
        </nav>
      </div>
    </div>
  </footer>
</template>


<style lang="scss" scoped>
@use "../style/partials/variables" as *;
@use "../style/partials/mixin" as *;

footer {
  padding: 20px;
  width: 100%;
  background-size: cover;
  background-image: url("../assets/img/footer-bg.jpg");
  .container {
    height: 350px;
    background-image: url("../assets/img/dc-logo-bg.png");
    background-position: right;
    background-repeat: no-repeat;
    @include centralFlex("vertical");
    align-items: flex-start;
    h3 {
      color: white;
      margin-left: 20px;
    }
    ul {
      margin-top: 20px;
      margin-bottom: 10px;
      li {
        list-style: none;
        margin-left: 20px;
        a {
          font-size: 0.8rem;
          text-decoration: none;
          color: gray;
        }
      }
    }
    .img-footer {
      width: 450px;
      align-items: flex-end;
      position: relative;
    }
  }
}
</style>