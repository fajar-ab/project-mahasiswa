<template>
  <section>
    <button @click="$emit('increment', i)">click me</button>
  </section>
</template>

<script setup>

let i = 0
</script>