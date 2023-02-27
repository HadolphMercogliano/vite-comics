<script>
export default {};
</script>

<template>
  <footer>
    <div class="footer-top">
      <div class="container">
        <div class="footer-text">
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
  //   height: 500px;
  .footer-text {
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
