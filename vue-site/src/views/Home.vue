<template>
  <div class="home">
    <div class="animate-bounce"><img class="mx-auto h-24 transform rotate-180" alt="Vue logo" src="../assets/logo.png"></div>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
