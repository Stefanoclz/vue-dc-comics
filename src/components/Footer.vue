<template>
  <footer>
    <div class="container">
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
  padding: 20px 0px;
}

.container {
  display: flex;
  justify-content: space-between;
  margin: auto;
  width: 70%;
  text-align: center;
  padding: 20px;

  .info {
    display: flex;
    column-gap: 30px;
  }

  .link {
    text-align: left;

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
</style>