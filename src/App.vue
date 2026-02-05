<template>
  <input v-model="name" placeholder="Type your name" />
  <p v-if="name">Hello, {{ name }}.</p>
</template>

<script setup>
import { ref } from "vue";
const name = ref("");
</script>
