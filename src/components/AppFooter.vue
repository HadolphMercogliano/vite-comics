<script>
export default {};
</script>

<template>
  <footer>
    <!--------------------- FOOTER TOP --------------------->
    <div class="footer-top">
      <div class="container">
        <div class="footer-text">
          <div>
            <h3>DC COMICS</h3>
            <ul>
              <li>
                <a href="#">Characters</a>
              </li>
              <li>
                <a href="#">Comics</a>
              </li>
              <li>
                <a href="#">Movies</a>
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
                <a href="#">News</a>
              </li>
            </ul>
            <h3>SHOP</h3>
            <ul>
              <li><a href="#">Shop DC </a></li>
              <li><a href="#">Shop DC Collectibles</a></li>
            </ul>
          </div>
          <div>
            <h3>DC</h3>
            <ul>
              <li><a href="#">Terms Of Use</a></li>
              <li><a href="#">Privacy Policy (New)</a></li>
              <li><a href="#"> Ad Choises</a></li>
              <li><a href="#">Advertising</a></li>
              <li><a href="#">Jobs</a></li>
              <li><a href="#">Subscriptions</a></li>
              <li><a href="#">Talent Workshops</a></li>
              <li><a href="#">CPSC Certificates</a></li>
              <li><a href="#">Ratings</a></li>
              <li><a href="#">Shop Help</a></li>
              <li><a href="#">Contact Us</a></li>
            </ul>
          </div>
          <div>
            <h3>SITES</h3>
            <ul>
              <li><a href="#">DC</a></li>
              <li><a href="#">MAD Magazine</a></li>
              <li><a href="#">DC Kids</a></li>
              <li><a href="#">DC Universe</a></li>
              <li><a href="#">DC Power Visa</a></li>
            </ul>
          </div>
        </div>
        <div class="bg-logo">
          <div></div>
        </div>
      </div>
    </div>

    <!--------------------- FOOTER BOTTOM --------------------->
    <div class="footer-bot">
      <div class="container">
        <div>
          <button class="btn-outline">SIGN-UP NOW!</button>
        </div>
        <div class="socials">
          <h3>FOLLOW US</h3>
          <ul>
            <li>
              <a href="#">
                <img
                  src="../assets/footer-facebook.png"
                  alt="" />
              </a>
            </li>
            <li>
              <a href="#">
                <img
                  src="../assets/footer-twitter.png"
                  alt="" />
              </a>
            </li>
            <li>
              <a href="#">
                <img
                  src="../assets/footer-youtube.png"
                  alt="" />
              </a>
            </li>
            <li>
              <a href="#">
                <img
                  src="../assets/footer-pinterest.png"
                  alt="" />
              </a>
            </li>
            <li>
              <a href="#">
                <img
                  src="../assets/footer-periscope.png"
                  alt="" />
              </a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>

<style lang="scss" scoped>
@use "../assets/styles/variables.scss" as *;
@use "../assets/styles/mixins.scss" as *;
.footer-top {
  background-image: url(../assets/footer-bg.jpg);
  background-repeat: no-repeat;
  .container {
    @include d-flex();
  }
  .footer-text {
    @include d-flex();

    width: 50%;

    padding: 20px 0;
    padding-bottom: 30px;
    div {
      margin-bottom: 10px;
      margin-right: 20px;
    }
    h3 {
      color: white;
      margin-bottom: 10px;
    }
    li {
      padding: 2px 0;
      font-size: 0.7rem;
      font-weight: 400;

      a {
        color: gray;
        text-decoration: none;
      }
    }
  }
  .bg-logo {
    width: 50%;
    div {
      height: 100%;
      background-image: url(../assets/dc-logo-bg.png);
      background-size: cover;
      background-position: center;
    }
  }
}
.footer-bot {
  .container {
    @include d-flex();
    justify-content: space-between;
    align-items: center;
  }
  background-color: $grey;
  padding: 20px;
  button {
    display: inline;
    font-weight: 700;
    padding: 10px;
    color: white;
    background-color: $grey;
    border: 1px solid $blue;
  }
  h3 {
    color: #0f82f7;
  }
  .socials {
    @include d-flex();
    align-items: center;
    column-gap: 10px;
    ul {
      @include d-flex();
      column-gap: 10px;
    }
  }
}
</style>
