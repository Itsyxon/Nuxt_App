<script setup>
import AboutBlock from '../../components/AboutBlock.vue'
function sayhi() {
  console.log('Hi from Nuxt')
}
</script>
<template><AboutBlock @sayHi="sayhi" /></template>
