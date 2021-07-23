<template>
  <div class="home">
    <BoxChat/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '../components/HelloWorld.vue'
import BoxChat from '../components/BoxChat.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
    BoxChat
  }
}
</script>
