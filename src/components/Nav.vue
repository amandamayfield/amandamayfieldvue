<script setup lang="ts">
import { RouterLink } from 'vue-router';
</script>

<template>
  <div class="nav">
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/about">About</RouterLink>
    <RouterLink to="/blog">Blog</RouterLink>
    <RouterLink to="/projects">Projects</RouterLink>
  </div>
</template>

<style lang="scss" scoped>
.nav {
  background-color: pink;
}
</style>