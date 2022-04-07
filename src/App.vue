<template>
  <div id="app">
    <Header />
    <Main :comics="comics" />
    <TopFooter />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";
import TopFooter from "./components/TopFooter.vue";
import comics from "@/assets/data/dc-comics";

export default {
  name: "App",
  data() {
    return {
      comics,
    };
  },
  components: {
    Header,
    Main,
    Footer,
    TopFooter,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 30px;
}
</style>
