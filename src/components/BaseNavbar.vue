<template>
  <div class="bg-amber-400">Hello this is navbar {{ count }}</div>
  <button @click="count++">Increment</button>
</template>

<script setup lang="ts">
import { ref } from 'vue';

const count = ref(0);
</script>

<style scoped></style>
