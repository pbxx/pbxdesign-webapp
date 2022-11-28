<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="logoHolder">
  </div>
  <HelloWorld msg="website coming soon" />
</template>

<style scoped>

.logoHolder {
  width: 50vh;
  height: 50vh;
  background-image: url(./assets/pbx-light.svg);
  background-size: cover; 
  padding: 0px;
  will-change: filter;
  transition-duration: 300ms;
}
/*
.logoHolder:hover {
  filter: drop-shadow(0 0 5em #300e8c);
}
*/

@media (prefers-color-scheme: light) {
  .logoHolder {
    background-image: url(./assets/pbx-light.svg);
  }

}
</style>
