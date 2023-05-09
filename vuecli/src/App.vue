<template>
  <div>
    <h1>Counter App</h1>
    <HelloWord></HelloWord>
  </div>
</template>

<script>
import HelloWord from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWord
  }
}
</script>

<style>
h1 {
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
</style>
