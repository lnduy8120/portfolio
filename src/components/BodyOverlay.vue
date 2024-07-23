<script setup lang="ts">

</script>

<template>
 <div class="body-overlay">
 </div>
</template>

<style scoped>
.body-overlay {
  background-image: url("@/assets/macos-bg.jpg");
  height: 100%;
  width: 100%;
  position: fixed;
  z-index: -1;
  top: 0;
  left: 0;
  object-fit: cover;
  opacity: 0.3;
}
</style>