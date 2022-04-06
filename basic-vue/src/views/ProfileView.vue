<template>
  <div class="profile">
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <!-- msg is a props. It can be customized and only created once on the root file -->
    <HelloWorld msg="This is a profile page"/> 
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'ProfileView',
  components: {
    HelloWorld
  }
}
</script>
