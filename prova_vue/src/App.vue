<template>
  <div>
    <h1>Counter App</h1>
    <counter></counter>
  </div>
</template>

<script>
import CounterComponent from './components/CounterComponent.vue'

export default {
  name: 'App',
  components: {
    CounterComponent
  }
}
</script>
