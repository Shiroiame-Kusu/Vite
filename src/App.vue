<script setup>
const App = {
  data() {
    return{
      count:0
    }
  },
  methods:{
    Clicker1(){
      index.count = index.count + 1
    }
  }
}
import index from './components/index.vue'
</script>

<template>
  <index msg="Vite + Vue" count="count"/>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
