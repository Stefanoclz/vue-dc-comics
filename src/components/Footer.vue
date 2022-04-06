<template>
  <footer>
    <div class="container">
      <!-- inizio sezione footer link -->

      <div class="info">
        <div class="link">
          <ul>
            <h3>DC COMICS</h3>
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

          <ul>
            <h3>SHOP</h3>
            <li>
              <a href="#">Shop DC</a>
            </li>
            <li>
              <a href="#">Shop DC Collectibles</a>
            </li>
          </ul>
        </div>

        <div class="link">
          <ul>
            <h3>DC</h3>
            <li>
              <a href="#">Terms of use</a>
            </li>
            <li>
              <a href="#">Privacy Policy(New)</a>
            </li>
            <li>
              <a href="#">AD Choices</a>
            </li>
            <li>
              <a href="#">Advertising</a>
            </li>
            <li>
              <a href="#">Jobs</a>
            </li>
            <li>
              <a href="#">Subscriptions</a>
            </li>
            <li>
              <a href="#">Talent Workshops</a>
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
        </div>

        <div class="link">
          <ul>
            <h3>Sites</h3>
            <li>
              <a href="#">DC</a>
            </li>
            <li>
              <a href="#">Mad Magazine</a>
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
        </div>
      </div>

      <!-- Fine sezione footer Link -->

      <!-- Inizio sezione footer logo big DC -->

      <div class="footerLogo"></div>
    </div>
    <!-- Inizio sezione Follow -->

    <div class="bot-footer">
      <div class="container-footer">
        <div class="signup">
          <button>SIGN UP NOW!</button>
        </div>

        <div class="followUs">
          <h3>FOLLOW US</h3>
          <img src="../assets/footer-facebook.png" alt="faceBook" />
          <img src="../assets/footer-twitter.png" alt="twitter" />
          <img src="../assets/footer-youtube.png" alt="youtube" />
          <img src="../assets/footer-pinterest.png" alt="pinterest" />
          <img src="../assets/footer-periscope.png" alt="periscope" />
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "footerPage",
};
</script>

<style scoped lang="scss">
footer {
  background-image: url(../assets/footer-bg.jpg);
}

.container {
  display: flex;
  justify-content: space-between;
  margin: auto;
  width: 70%;
  text-align: center;

  .info {
    display: flex;
    column-gap: 30px;
  }

  .link {
    text-align: left;
    padding: 60px 20px;

    h3 {
      color: white;
      margin-bottom: 10px;
    }

    ul {
      margin-bottom: 10px;
    }

    li {
      list-style-type: none;
    }

    a {
      color: grey;
      text-decoration: none;
      font-size: 13px;
    }
  }
}

.footerLogo {
  background-image: url(../assets/dc-logo-bg.png);
  background-repeat: no-repeat;
  background-position: center;
  width: 50%;
}

.bot-footer {
  background-color: #303030;
}

.container-footer {
  display: flex;
  justify-content: space-between;
  margin: auto;
  width: 70%;
  text-align: center;
  padding: 40px 0px;

  button {
    color: white;
    background-color: transparent;
    padding: 15px 10px;
    border: 2px solid #097df6;
    font-size: 18px;
  }

  h3 {
    color: #097df6;
    font-size: 20px;
  }

  .followUs {
    display: flex;
    column-gap: 25px;
    align-items: center;
  }
}
</style>