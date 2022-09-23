<template>
  <main>
    <h1>Gallery:</h1>
    <p>This is where gallery should go?</p>
    <div>{{ artworks }}</div>
  </main>
</template>

<script>
// import data and tools
import artworks from "../mock/artworks.json";
// import components

export default {
  name: "Home-View",
  data() {
    return {
      artworks: artworks,
    };
  },
};
</script>
