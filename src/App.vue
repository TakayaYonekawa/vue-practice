<script setup>
import { ref } from "vue";

  const newTodo = ref('')
</script>


<template>
  <input type="text" size="30" v-model="newTodo">
  <button >追加</button>
</template>