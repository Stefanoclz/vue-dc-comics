<template>
  <header>
    <div class="container">
      <img src="../assets/dc-logo.png" alt="DC logo" />
      <ul>
        <li>
          <a href="#">CHARACTERS</a>
        </li>
        <li>
          <a href="#">COMICS</a>
        </li>
        <li>
          <a href="#">MOVIES</a>
        </li>
        <li>
          <a href="#">TV</a>
        </li>
        <li>
          <a href="#">GAMES</a>
        </li>
        <li>
          <a href="#">COLLECTIBLES</a>
        </li>
        <li>
          <a href="#">VIDEOS</a>
        </li>
        <li>
          <a href="#">FANS</a>
        </li>
        <li>
          <a href="#">NEWS</a>
        </li>
        <li>
          <a href="#">SHOP</a>
        </li>
      </ul>
    </div>
  </header>
</template>

<script>
export default {
  name: "headerPage",
};
</script>

<style scoped lang="scss">
header {
  background-color: white;
}

.container {
  display: flex;
  justify-content: space-between;
  margin: auto;
  width: 70%;
  text-align: center;

  img {
    height: 80px;
    margin: 20px 0px;
  }

  ul {
    display: flex;
    column-gap: 20px;
    align-items: center;
  }

  li {
    list-style-type: none;
    padding-bottom: 48px;
    margin-top: 50px;

    &:hover {
      border-bottom: 3px solid #0282f9;
      color: #0282f9;
    }
  }

  a {
    text-decoration: none;
    color: black;
    font-weight: bold;
    font-size: 13px;
  }
}

li:hover a {
  color: #0282f9;
}
</style>