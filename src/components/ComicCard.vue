<template>
  <div class="card">
    <img :src="coverImg" alt="cover" />
    <p>{{ series }}</p>
  </div>
</template>

<script>
export default {
  name: "ComicCard",
  props: {
    coverImg: String,
    series: String,
  },
};
</script>

<style>
</style>