<script setup>
defineProps({
  title: String,
  description: String,
  image: String,
})
</script>

<template>
  <div class="service-card">
    <img :src="image" :alt="title" />

    <h3>{{ title }}</h3>

    <p>{{ description }}</p>
  </div>
</template>
