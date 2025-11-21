<script setup lang="ts">
import { ref } from "vue";

const emoji = ref("✅");
</script>

<template>
  <header>
    <span>{{ emoji }}</span>
  </header>
</template>

<style scoped>
header {
  text-align: center;
  font-size: 3rem;
}
</style>
