<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <div class="container">
      <div class="container-sm">100% wide until small breakpoint</div>
      <div class="container-md">100% wide until medium breakpoint</div>
      <div class="container-lg">100% wide until large breakpoint</div>
      <div class="container-xl">100% wide until extra large breakpoint</div>
      <div class="container-xxl">100% wide until extra extra large breakpoint</div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld1 from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
