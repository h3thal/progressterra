<template>
  <Navbar/>
  <Main/>
  <About/>
  <Advantage/>
  <HowToUse/>
  <WeUse/>
</template>

<script>
import Navbar from '@/components/Navbar/Navbar.vue'
import Main from '@/components/Main/Main.vue'
import About from '@/components/About/About.vue'
import Advantage from '@/components/Advantage/Advantage.vue'
import HowToUse from '@/components/HowToUse/HowToUse.vue'
import WeUse from '@/components/WeUse/WeUse.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Main,
    About,
    Advantage,
    HowToUse,
    WeUse
  }
}
</script>

<style lang="scss">
  body {
    margin: 0px;
    padding: 0px;
  }
</style>
