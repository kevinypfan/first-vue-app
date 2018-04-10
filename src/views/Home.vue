<template>
  <div class="home">
    <img src="../assets/logo.png">
    <HelloWorld msg="Hello Vue"/>
    <HelloWorld msg="Mr. Chou"/>
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
