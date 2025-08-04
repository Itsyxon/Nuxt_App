<script setup>
const emit = defineEmits(['sayHi'])
</script>
<template>
  <div class="about-block" @click="emit('sayHi')">
    <h1>About us</h1>
    <p>Our company is cool</p>
  </div>
</template>
<style scoped>
.about-block {
  padding: 15px;
  border: 2px solid teal;
  width: fit-content;
}
</style>
