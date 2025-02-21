<script setup lang="ts">
import { RouterView } from 'vue-router'
</script>

<template>
  <RouterView />
</template>

<style scoped>
header {
  display: flex;
  justify-content: center;
  padding: 1rem;
  background-color: #f5f5f5;
}

nav {
  font-size: 16px;
}

nav a {
  margin: 0 15px;
  text-decoration: none;
  color: #333;
}

nav a.router-link-active {
  font-weight: bold;
}
</style>