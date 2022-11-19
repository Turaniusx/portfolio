<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <main>
    <Header />
    <RouterView :key="$route.fullPath" />
  </main>
</template>

<script>
import Header from "@/layout/Header.vue";

export default {
  name: "App",
  components: {
    RouterView,
    Header,
  },
};
</script>

<style lang="scss">
@import "./assets/scss/main.scss";
</style>
