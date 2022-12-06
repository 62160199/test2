<template>
  <div class="home">
    <img alt="gif" src="https://www.galvanizeaction.org/wp-content/uploads/2022/06/Wow-gif.gif">
    <HelloWorld msg="Home"/>
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
