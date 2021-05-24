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
