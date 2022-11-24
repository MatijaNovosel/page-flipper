<template>
  <div id="app">
    Testing
    <flipbook class="flipbook" :pages="pages" />
  </div>
</template>

<script lang="ts" setup>
import Flipbook from "flipbook-vue";
const pages = ["", "1.jpg", "2.jpg", "3.jpg", "4.jpg", "6.jpg", "5.jpg"];
</script>

<style>
.flipbook .viewport {
  width: 90vw;
  height: 90vh;
}

.flipbook .bounding-box {
  box-shadow: 0 0 20px #000;
}
</style>
