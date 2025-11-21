<script setup lang="ts">
import { ref } from "vue";

const name = ref("Steven");
</script>

<template>
  <main>
    <h1>Hello, {{ name }}</h1>
    <p>I'm about yo learn <a href="https://vuejs.org/" target="_blank">Vue.js</a>!</p>
  </main>
</template>

<style scoped>
main {
  text-align: center;
}
</style>
