<template>
  <Navbar/>
  <Main/>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Navbar from '@/components/Navbar/Navbar.vue'
import Main from '@/components/Main/Main.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Navbar,
    Main
  }
}
</script>

<style lang="scss">
  body {
    margin: 0px;
    padding: 0px;
  }
</style>
