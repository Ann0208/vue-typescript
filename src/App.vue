<template>
  <div id="app">
    <p>....</p>
    <img alt="Vue logo" src="./assets/cat.png">
    <HelloWorld msg="What are you looking at? It's just a kitten" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HelloWorld from './components/HelloWorld.vue';

export default defineComponent({
  name: "App",
  components: {
    HelloWorld
  }
})
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
