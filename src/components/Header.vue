<script setup>
defineProps({
  title: {
    type: String,
    required: true,
    default: 'title',
  },
})
</script>

<template>
  <h1>{{ title }}</h1>
</template>

<style scoped></style>
