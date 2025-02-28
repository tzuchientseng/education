<script setup lang="ts">
import { RouterLink } from 'vue-router';
</script>

<template>
  <nav>
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/intro">簡介</RouterLink>
    <RouterLink to="/elementary">國小課綱</RouterLink>
  </nav>
</template>

<style scoped>
nav {
  display: flex;
  gap: 20px;
  background-color: #2c3e50;
  padding: 10px 20px;
  border-radius: 8px;
}

nav a {
  text-decoration: none;
  color: white;
  font-weight: bold;
  padding: 8px 12px;
  transition: background-color 0.3s ease-in-out, transform 0.2s;
  border-radius: 4px;
}

nav a:hover {
  background-color: #34495e;
  transform: scale(1.1);
}

nav a.router-link-exact-active {
  background-color: #1abc9c;
  color: #fff;
}
</style>
