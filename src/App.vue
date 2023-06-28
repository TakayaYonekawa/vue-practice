<script setup>
import { ref } from "vue";

  const number = ref(0)
</script>


<template>
  <input type="text" size="30" v-model="number">
  <button>+1</button>
</template>