<template>
  <main>
    <h1>Gallery:</h1>
    <div v-for="artwork in artworks" :key="artwork.id">
      <h1>{{ artwork.name }}</h1>
      <!-- <img :src="artwork.img" />
      <img src="@/mock/images/portfolio1.jpg" /> -->
      <!-- path is not found. artwork name is found so it's sth to do w the img path-->
    </div>
  </main>
</template>

<script>
// import data and tools
import artworks from "../mock/artworks.json";
import ArtPanel from "../components/ArtPanel.vue";
// import components

export default {
  name: "Home-View",
  data() {
    return {
      artworks: artworks,
    };
  },
  components: { ArtPanel },
};
</script>
