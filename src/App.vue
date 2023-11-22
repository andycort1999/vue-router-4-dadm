<script setup>
import { RouterView } from 'vue-router';
</script>

<template>
  <div id="nav">
    <router-link  to="/">Inicio</router-link>
    <router-link  to="/about">Acerca de</router-link>
    <router-link  to="/brazil">Brazil</router-link>
  </div>
    <div class="Container">
      <RouterView />
    </div>
</template>

<style scoped>
</style>
