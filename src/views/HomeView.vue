<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/recipe.png">
    <HelloWorld msg="Welcome to Home cooks"/>
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
