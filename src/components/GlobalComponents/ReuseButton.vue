<template>
  <div class="btn rounded mt-2 w-50">
    <span class="btn-span mx-auto">{{ btn_name }}</span>
  </div>
</template>

<script>
export default {
  name: "ReuseButton",
  props: {
    btn_name: String,
  },
};
</script>

<style scoped>
.btn {
  width: 200px !important;
  height: 40px !important;
}

@media (min-width: 400px) and (max-width: 650px) {
}
@media (min-width: 300px) and (max-width: 398px) {
}
</style>
