<script setup>
import { RouterView } from 'vue-router'
import Navbar from './components/layouts//Navbar.vue'
</script>

<template>
  <header>
    <Navbar />
    <RouterView />
  </header>
</template>

<style>
@import '@/assets/css/styles.css';
</style>