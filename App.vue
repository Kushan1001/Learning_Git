<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
  <RouterView />
  </header>
</template>

<style scoped>
header {
  line-height: 1.5;
  max-height: 100vh;
}
</style>
