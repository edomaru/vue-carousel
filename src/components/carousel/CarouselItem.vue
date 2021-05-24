<template>
  <div class="carousel-item">
    <img :src="slide" />
  </div>
</template>

<script>
export default {
  props: ["slide"],
};
</script>

<style scoped>
.carousel-item {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
}
</style>
