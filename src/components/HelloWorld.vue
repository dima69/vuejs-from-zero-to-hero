<template>
  <h1>{{ msg }}</h1>

  <p>
     заходит однажды улитка в бар
  </p>

  <!-- oh-oh this is gonna be a disaster  -->
  <HelloWorld />

  <button @click="state.count++">count is: {{ state.count }}</button>
  <p>
    Edit
    <code>components/HelloWorld.vue function() { }</code> to test hot module replacement.
  </p>
</template>

<script setup>
import { defineProps, reactive } from 'vue'

defineProps({
  msg: String,
  asd: String
})
let asd = 123; // defineProps
const state = reactive({ count: 0 }) // what the hell
</script>

<style scoped>
a {
  color: #000;
}
</style>
