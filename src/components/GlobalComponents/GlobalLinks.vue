<template>
  <div>
    <a class="text-decoration-none" style="color: #000" href="#">{{
      link_name
    }}</a>
  </div>
</template>

<script>
export default {
  name: "GlobalLinks",
  props: {
    link_name: String,
  },
};
</script>

<style></style>
