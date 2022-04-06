<template>
  <header>
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
  </header>
</template>

<script>
export default {
  name: "headerPage",
};
</script>

<style scoped lang="scss">
header {
  display: flex;
  justify-content: space-around;
  text-align: center;
  background-color: white;
  padding: 20px;

  img {
    height: 80px;
  }

  ul {
    display: flex;
    column-gap: 20px;
    align-items: center;
  }

  li {
    list-style-type: none;
  }

  a {
    text-decoration: none;
    color: black;
    font-weight: bold;
    font-size: 13px;
  }
}
</style>