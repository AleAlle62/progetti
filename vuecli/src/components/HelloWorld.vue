<template>
  <div>
    <button @click="increment">+</button>
    <span>{{ count }}</span>
    <button @click="decrement">-</button>
  </div>
</template>


<script>
export default {
  data() {
    return {
      count: 0
    }
  },
  methods: {
    increment() {
      this.count++
    },
    decrement() {
      this.count--
    }
  }
}
</script>

<style >

div {
  text-align: center;
}

span {
  font-size: 30px;
  margin: 20px;
  color: #4CAF50;
}
button {
  background-color: #4CAF50;
  border: none;
  color: white;
  padding: 12px 24px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  border-radius: 4px;
  cursor: pointer;
  transition: all 0.2s ease-in-out;
}

</style>