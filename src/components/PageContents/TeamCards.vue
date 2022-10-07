<template>
  <div class="team-card card HoverDiv bg-white text-white">
    <img src="@/assets/capentry.jpg" class="card-img" alt="..." />

    <!-- <p class="card-text">
        This is a wider card with supporting text below as a natural lead-in to
        additional content. This content is a little bit longer.
      </p>
      <p class="card-text">Last updated 3 mins ago</p> -->
    <div class="card bg-info w-75 text-center mx-auto" style="z-index: 100000">
      <i class="fa-brands fa-twitter"></i>
    </div>
  </div>
</template>

<script>
export default {
  name: "TeamCards",
};
</script>

<style scoped>
.card {
  border: none;
}
.team-card {
}
</style>
