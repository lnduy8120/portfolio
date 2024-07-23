<script setup lang="ts">
import BodyOverlay from "@/components/BodyOverlay.vue";
import LeftSideBar from "@/components/LeftSideBar.vue";
import Contents from "@/components/Contents.vue";
</script>

<template>
  <main>
    <div class="wrapper">
      <BodyOverlay>
      </BodyOverlay>
      <LeftSideBar></LeftSideBar>
      <Contents></Contents>
      </div>
  </main>
</template>

<style scoped>
  .wrapper {
    height: 1300px;
  }
</style>
