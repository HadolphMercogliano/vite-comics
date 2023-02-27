<script>
export default {};
</script>

<template>
  <footer>
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
          <img
            src="../assets/dc-logo-bg.png"
            alt="" />
        </div>
      </div>
    </div>
    <div class="footer-bot">
      <div class="container">
        <button class="btn-outline">SIGN-UP NOW!</button>
        <div>
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
.footer-top {
  background-image: url(../assets/footer-bg.jpg);
  .footer-text {
    padding: 10px 0;
    div {
      margin-bottom: 10px;
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
  }
}
.footer-bot {
  background-color: #2f2f2f;
  padding: 20px;
  button {
    font-weight: 700;
    padding: 10px;
    color: white;
    background-color: #2f2f2f;
    border: 1px solid #0f82f7;
  }
  h3 {
    color: #0f82f7;
  }
}
</style>
