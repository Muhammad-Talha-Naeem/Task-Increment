<template>
  <inc/>
  <inc/>
  <inc/>
</template>

<script>
import inc from './components/inc.vue'
export default {
  name: 'App',
  components: {
    inc,
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
