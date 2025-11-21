<script setup lang="ts">
import { ref } from "vue";

const name = ref("Steven");
const emoji = ref("✅");
const copyright = ref("2025");
</script>

<template>
  <header>
    <span>{{ emoji }}</span>
  </header>

  <main>
    <h1>Hello, {{ name }}</h1>
    <p>I'm about yo learn <a href="https://vuejs.org/" target="_blank">Vue.js</a>!</p>
  </main>

  <footer>
    <p>&copy; {{ copyright }}</p>
  </footer>
</template>

<style>
body {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100%;
  height: 100%;
  background: white;
  color: black;
}

header,
main,
footer {
  text-align: center;
}

footer {
  margin-top: 50px;
  color: blue;
}
</style>
