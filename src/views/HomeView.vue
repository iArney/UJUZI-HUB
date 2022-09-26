<template>
  <div class="home">
    <nav-bar />
  </div>
  <main>
    <home-v-height />
    <body-section />
  </main>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import NavBar from "@/components/GlobalComponents/NavBar.vue"; // @ is an alias to /src
import HomeVHeight from "@/components/HomePage/HomeVHeight.vue";
import BodySection from "@/components/HomePage/BodySection.vue";

export default defineComponent({
  name: "HomeView",
  components: {
    NavBar,
    HomeVHeight,
    BodySection,
  },
});
</script>
<style scoped>
main {
  overflow-x: hidden;
}
</style>
