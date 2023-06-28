<script setup>
import {ref, computed } from "vue";

// const answer = computed(() => {
//   return 1 + 1;
// });

const message = 'ようこそ　<strong>ヨネ</strong>さん'
const welecomeColor = 'blue'
const myname = ref('')
</script>

<template>
  <h1>Vue 3</h1>
  <p>お名前は？：<input type="text" size="10" v-model="myname"></p>
  <p v-html="myname" :style="{backgroundColor:welecomeColor, 'color': 'white'}" ></p>
</template>
