<template>

  <h1>Counter {{}}</h1>

  <button @click="increment">click me!</button>

</template>

<script setup>
import { ref } from 'vue';

const counter = ref(0)


function increment() {
  counter++
}
</script>