<template>
  <div class="home">
    <img src="../assets/logo.png">
    <HelloWorld msg="VUE-STARTER - A Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>
