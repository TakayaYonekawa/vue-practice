<script setup>
import { ref } from "vue";
  const todos = ref([])
  const newTodo = ref('')

  const addTodo = () => {
    todos.value.push(newTodo.value)
  }
</script>


<template>
  <input type="text" size="30" v-model="newTodo">
  <button @click="addTodo">追加</button>
</template>