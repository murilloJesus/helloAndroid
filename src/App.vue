<script setup>
import { ref } from 'vue';

  const counter = ref(0);

  function add(){
    counter.value++
  }
</script>

<template>
  <h1>Hello Android</h1>
  <h3>Counter: {{ counter }}</h3>
  <button @click="add">Add</button>
</template>

<style scoped>
  button {
    color: blue;
    width: 100%;
  }
</style>
