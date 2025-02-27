<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <header>
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/intro">簡介</RouterLink>
        <RouterLink to="/elementary">國小課綱</RouterLink>
      </nav>
  </header>

  <RouterView />
</template>

<style scoped>

</style>
