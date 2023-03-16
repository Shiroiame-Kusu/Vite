<script setup>
import { ref } from 'vue'
import 'bootstrap'

defineProps({
  msg: String,
})

const count = ref(0)
</script>
<template>
  <header>
    <span>a</span>
  </header>
</template>
<style scoped>
.header{
  height: 100px;
  background-color: #fff;
}
</style>