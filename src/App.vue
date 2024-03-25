<script setup>
import { ref } from 'vue'

const count = ref(0)

function increment() {
  count.value++
}
</script>

<template>
  <button v-on:click="increment"> hitungan saat ini adalah {{ count }} </button>
</template>

<style scoped>

</style>
