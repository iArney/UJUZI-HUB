<template>
  <div class="card text-dark bg-white shadow-sm mb-3" style="max-width: 18rem">
    <!-- <div class="card-header">Header</div> -->
    <div class="card-body">
      <h5 class="card-title text-center lh-lg">
        Light card title <br />
        <span class="card-text">$99</span>
      </h5>
      <span class="card-text mt-5">
        <ul class="lh-lg">
          <li>1000 visitors</li>
          <li>Unlimited projects</li>
          <li>Extended free trial</li>
        </ul>
      </span>
    </div>
    <div class="text-center">
      <reuse-button
        class="mb-3 mx-auto"
        btn_name="Create account"
        style="background-color: #3fa5c0; color: white"
      />
    </div>
  </div>
</template>

<script>
import ReuseButton from "@/components/GlobalComponents/ReuseButton.vue";
export default {
  name: "PriceCards",
  components: { ReuseButton },
};
</script>

<style scoped>
ul {
  list-style: none;
}

ul li::before {
  content: "\2022";
  color: #0066ff;
  font-weight: bold;
  display: inline-block;
  width: 1em;
  margin-left: -1em;
}
</style>
