<template>
  <div id="app">
    <Navbar />
    <router-view></router-view>
  </div>
</template>

<script setup lang="ts">
import Navbar from './components/Navbar.vue';
</script>

<style scoped>
</style>
