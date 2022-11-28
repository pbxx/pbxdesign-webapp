<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

const count = ref(0)
</script>

<template>
  <h2>PBXDESIGN</h2>
  <h3>{{ msg }}</h3>
<!--



  <div class="card">
    <button type="button" @click="count++">count is {{ count }}</button>
    <p>
      Edit
      <code>components/HelloWorld.vue</code> to test HMR
    </p>
  </div>

  <p>
    Check out
    <a href="https://vuejs.org/guide/quick-start.html#local" target="_blank"
      >create-vue</a
    >, the official Vue + Vite starter
  </p>
  <p>
    Install
    <a href="https://github.com/johnsoncodehk/volar" target="_blank">Volar</a>
    in your IDE for a better DX
  </p>
  <p class="read-the-docs">Click on the Vite and Vue logos to learn more</p>

  -->
</template>

<style scoped>
.read-the-docs {
  color: #888;
}

h2 {
  font-family: "Roboto Condensed";
  font-size: var(--desktop-pbx-fontsize);
  letter-spacing: var(--desktop-pbx-lspace);
  margin-right:  calc(var(--desktop-pbx-lspace) * -1);

  text-align: center!important;
  display: flex;
  justify-content: center;

  transition-duration: 300ms;
}


h3 {
  font-family: "Roboto Condensed";
  font-weight: 300;
  padding: 0 0 88px 0;
  margin: 0!important;
  font-size: var(--desktop-subtitle-fontsize);

  letter-spacing: var(--desktop-subtitle-lspace);
  margin-right:  calc(var(--desktop-subtitle-lspace) * -1);

  color: #ffffff36;
  
  text-shadow: 0 0 15em #300e8c00;

  transition-duration: 300ms;
}



@media (prefers-color-scheme: light) {
  h3 {
    text-shadow: 0 0 4px #120f0f00;
    color: #00000091;
  }

}

@media (max-width: 400px) {
  h2 {
  font-size: var(--mobile-pbx-fontsize);
  letter-spacing: var(--mobile-pbx-lspace);
  margin-right:  calc(var(--mobile-pbx-lspace) * -1);
}


h3 {
  font-size: var(--mobile-subtitle-fontsize);
  letter-spacing: var(--mobile-subtitle-lspace);
  margin-right:  calc(var(--mobile-subtitle-lspace) * -1);
}

}

</style>
