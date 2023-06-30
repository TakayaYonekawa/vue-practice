<script setup>
    defineProps(['color'])
</script>

<template>
  <header>
    <h1 :style="{ 'color' :color }" >ToDoツール</h1>
  </header>
</template>
