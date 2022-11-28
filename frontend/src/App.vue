<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <img src="./assets/pbx.svg" class="logo" alt="Vite logo" />
  </div>
  <HelloWorld msg="website coming soon" />
</template>

<style scoped>
.logo {
  height: 50vh;
  padding: 0px;
  will-change: filter;
  filter: drop-shadow(0 0 1em #120f0f42);
}
.logo:hover {
  filter: drop-shadow(0 0 2em #120f0f42);
}
</style>
