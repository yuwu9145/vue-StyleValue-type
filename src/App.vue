<template>
  <h1 :style="[ style, {background: 'green'} ]">Test</h1>  
</template>
<script setup lang="ts">
import { ref } from 'vue'
const style = ref(undefined)
</script>
