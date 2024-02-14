<template>
  <div>
    <h3>{{ title }}</h3>
    <p>Create a simple Vue component and display data in the template. </p>

    <p>Task Completed On {{ date }}.</p>
  </div>
</template>

<script setup>
import { ref } from 'vue';

const title = ref("My First Task");
const date = ref("09/02/2024");
</script>