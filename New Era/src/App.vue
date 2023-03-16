<script setup>
import header from './components/header.vue'
import index from './components/index.vue'
import footer from './components/footer.vue'
</script>

<template>
  <header />
  <index msg="New Era" class="index"/>
  <footer />
</template>

<style scoped>
.index{
  background-color: white;
}

</style>
