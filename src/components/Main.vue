<template>
  <main>
    <div class="jumbo">
      <img src="../assets/jumbotron.jpg" alt="jumbo" />
    </div>
    <div class="container">
      <div class="current">CURRENT SERIES</div>
      <div class="card" v-for="(item, index) in comics" :key="index">
        <a href="#">
          <img :src="item.thumb" alt="cover" />
          <p>{{ item.series }}</p>
        </a>
      </div>
    </div>
    <button>LOAD MORE</button>
  </main>
</template>

<script>
export default {
  name: "mainPage",
  props: {
    comics: Array,
  },
};
</script>

<style scoped lang="scss">
main {
  color: white;
  background-color: #1c1c1c;
}

.jumbo {
  height: 400px;

  img {
    object-fit: cover;
    object-position: top;
    height: 100%;
    width: 100%;
  }
}

.container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  margin: auto;
  width: 70%;
  align-items: center;
  padding: 50px 0px;
  column-gap: 3%;
  row-gap: 80px;
  position: relative;

  .current {
    position: absolute;
    left: 0;
    top: -40px;
    background-color: #097df6;
    padding: 15px 20px;
    font-weight: bolder;
    font-size: 25px;
  }
}

.card {
  width: calc(100% / 6) - 3%;
  height: 200px;
  text-align: left;
  transition: transform 0.5s ease-in;

  &:hover {
    transform: scale(1.1);
  }

  img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: top;
    margin-bottom: 10px;
  }

  a {
    text-decoration: none;
    color: white;
  }
}

button {
  color: white;
  padding: 10px 50px;
  background-color: #097df6;
  margin: 30px 0px;
  border: 1px solid transparent;
  transition-property: border-radius, background-color, border-color;
  transition-duration: 0.5s;
  transition-timing-function: ease-in;

  &:hover {
    border-radius: 25px;
    background-color: transparent;
    border-color: white;
  }
}
</style>