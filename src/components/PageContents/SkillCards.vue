<template>
  <!-- <div class="skill-card HoverDiv card" style="width: 18rem">
    <img
      src="@/assets/capentry.jpg"
      class="card-img position-relative"
      alt="..."
    />
    <div class="card-body">
      <p class="card-text">
        Some quick example text to build on the card title and make up the bulk
        of the card's content.
      </p>
    </div>
  </div> -->
  <div class="card HoverDiv bg-light text-white">
    <img src="@/assets/capentry.jpg" class="card-img" alt="..." />
    <div class="card-img-overlay" style="z-index: 100000">
      <h5 class="card-title fw-bolder" style="margin-top: 12rem">Card title</h5>
      <!-- <p class="card-text">
        This is a wider card with supporting text below as a natural lead-in to
        additional content. This content is a little bit longer.
      </p>
      <p class="card-text">Last updated 3 mins ago</p> -->
    </div>
  </div>
</template>
<script>
export default {
  name: "SkillCards",
};
</script>

<style>
.skill-card {
  border: none;
}
.HoverDiv {
  cursor: pointer;
  position: relative;
  overflow: hidden;
  border: 1px solid black;
  width: 360px;
  margin: 10px;
}

.HoverDiv img {
  max-width: 100%;
  text-align: center;
  -moz-transition: all 0.3s;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
}

.HoverDiv:hover img {
  -moz-transform: scale(1.1);
  -webkit-transform: scale(1.1);
  transform: scale(1.1);
}
p {
  margin-top: 10px;
}

img {
  display: inline-block;
  /* border: 1px solid #ddd;
  border-radius: 2px; */
  padding: 1px;
  transition: 0.3s;
  position: relative;
  z-index: 1;
}
</style>
