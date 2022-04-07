<template>
  <main>
    <div class="jumbo">
      <img src="../assets/jumbotron.jpg" alt="jumbo" />
    </div>
    <div class="container">
      <div class="card" v-for="(item, index) in comics" :key="index">
        <img :src="item.thumb" alt="cover" />
        <p>{{ item.series }}</p>
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
}

.card {
  width: calc(100% / 6) - 3%;
  height: 200px;
  text-align: left;

  img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: top;
    margin-bottom: 10px;
  }
}

button {
  color: white;
  padding: 10px 50px;
  background-color: #097df6;
  margin: 30px 0px;
  border: none;
}
</style>