<template>
  <main>
    <div class="container">
      <div class="card" v-for="(item, index) in comics" :key="index">
        <img :src="item.thumb" alt="cover" />
        <p>{{ item.series }}</p>
      </div>
    </div>
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

.container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  margin: auto;
  width: 70%;
  align-items: center;
  padding: 50px 0px;
  column-gap: 30px;
  row-gap: 50px;
}

.card {
  width: calc(100% / 6) - 3%;
  height: 200px;

  img {
    width: 100%;
    height: 100%;
  }
}
</style>