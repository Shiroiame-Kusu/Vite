<script setup>
import { ref } from 'vue'
import count from '../App.vue'

defineProps({
  msg: String,
})


</script>

<template>
  <h1>{{ msg }}</h1>

  <div class="card">
    <button type="button" @click="Clicker1">count is {{ count }}</button>
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
