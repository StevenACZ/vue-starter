<script setup lang="ts">
import { ref } from "vue";

const copyright = ref("2025");
</script>

<template>
  <footer>
    <p>&copy; {{ copyright }}</p>
  </footer>
</template>

<style scoped>
footer {
  text-align: center;
  margin-top: 50px;
  color: blue;
}
</style>
