<script setup lang="ts">
import AppHeader from "./components/AppHeader.vue";
import AppFooter from "./components/AppFooter.vue";
import AppMain from "./components/AppMain.vue";
</script>

<template>
  <AppHeader />
  <AppMain />
  <AppFooter />
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
</style>
