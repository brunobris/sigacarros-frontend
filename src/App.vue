<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <Anuncio/>
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue'
import Anuncio from '@/components/Anuncio.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Anuncio
  }
}
</script>

<style src="@/assets/main.css">
</style>
