<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.jpg" width="300" height="400">
    <HelloWorld msg="Bienvenidos a mi pagina"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
