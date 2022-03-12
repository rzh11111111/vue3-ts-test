<template>
 
<div>{{message+1}}</div>
<div>{{count}}</div>
</template>

<script setup lang="ts">
import {ref} from 'vue'
const message:string = '123123'
const count = ref(0)
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
