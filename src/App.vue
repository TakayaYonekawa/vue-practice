<script setup>
// import { computed } from "vue";

// const answer = computed(() => {
//   return 1 + 1;
// });

const message = 'ようこそ　<strong>ヨネ</strong>さん'
const welecomeColor = 'blue'
</script>

<template>
  <h1>Vue 3</h1>
  <p v-html="message" :style="{backgroundColor:welecomeColor, 'color': 'white'}" ></p>
</template>
