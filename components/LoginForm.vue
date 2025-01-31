<template>
  <div>
    <input type="text" name="username" id="username" placeholder="Username">
    <input type="password" name="password" id="password" placeholder="Password">
  </div>
</template>

<script setup>
import { ref } from 'vue';

const username = ref('');
const password = ref('');
</script>