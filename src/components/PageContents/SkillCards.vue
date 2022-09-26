<template>
  <div class="HoverDiv card" style="width: 18rem">
    <img src="@/assets/capentry.jpg" class="card-img" alt="..." />
    <div class="card-body">
      <p class="card-text">
        Some quick example text to build on the card title and make up the bulk
        of the card's content.
      </p>
    </div>
  </div>
</template>
<script>
export default {
  name: "SkillCards",
};
</script>

<style>
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

img:hover {
  /* box-shadow: 0 0 2px 1px rgba(0, 140, 186, 0.5); */
  /* -webkit-transform: skewX(-20deg);
  -ms-transform: skewX(-20deg);
  transform: skewX(-20deg);
  -webkit-transform-origin: 0 0;
  -ms-transform-origin: 0 0;
  transform-origin: 0 0; */
}
</style>
