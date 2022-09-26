<template>
  <div class="HoverDiv card" style="width: 18rem">
    <img src="@/assets/capentry.jpg" class="card-img" alt="..." />
    <div class="card-body">
      <h5 class="card-title">Card title</h5>
      <p class="card-text">
        Some quick example text to build on the card title and make up the bulk
        of the card's content.
      </p>
      <reuse-button
        btn_name="ENROLL"
        style="background-color: #f18626; color: white"
      />
    </div>
  </div>
</template>

<script>
import ReuseButton from "../GlobalComponents/ReuseButton.vue";
export default {
  components: { ReuseButton },
  name: "EnrollCards",
};
</script>

<style></style>
