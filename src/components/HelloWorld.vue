<template>
<div>
  <h1>{{ message }}</h1>
  <button id = "increaseState" type = "button" @click = "state.count++"> INCREASE COUNT </button>
  <button id = "buttonState" type = "button">COUNT : {{ state.count }} </button>
  <button id = "decreaseState" type = "button" @click = "state.count--"> DECREASE COUNT </button>
  <button id = "resetButton" @click = "state.count *= 0">RESET</button>
  </div>
</template>

<script setup>
import { defineProps, reactive } from 'vue'


defineProps({
  message: String
})


const state = reactive({ count: 0 })
</script>

<style scoped>
a {
  color: #42b983;
}
</style>
