<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

const count = ref(0)
</script>

<template>
  <h1 class="text-lime-500">{{ msg }}</h1>
  <p>Test</p>
</template>

<style scoped>
</style>
