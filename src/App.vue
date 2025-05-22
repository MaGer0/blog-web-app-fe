<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import LoginView from './views/LoginView.vue'
</script>

<template>
  <div class="app"></div>
  <LoginView />
</template>

<style>
body {
  font-family: 'Nunito', sans-serif;  
}
</style>
