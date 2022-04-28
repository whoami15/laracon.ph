<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})
</script>

<template>
  <h1 class="text-center text-5xl font-bold">
    {{ msg }}
  </h1>
</template>
