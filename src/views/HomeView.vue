<template>
  <main>
    <h1>Gallery:</h1>
    <p>This is where gallery should go</p>
    <div>{{ artworks }}</div>
  </main>
</template>

<script>
import artworks from "../mock/artworks.json";

export default {
  name: "Home-view",

  data() {
    return {
      artworks: artworks,
    };
  },
};
</script>
