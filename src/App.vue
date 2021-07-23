<template>
  <div id="app">
    <HelloWorld msg="Chat App"/>
    <BoxChat/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import BoxChat from './components/BoxChat.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    BoxChat
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
