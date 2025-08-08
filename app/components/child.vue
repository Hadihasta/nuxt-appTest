<!-- components/Child.vue -->
<template>
  <div>
    <p>Halo, saya Child. Nama dari parent: {{ nama }}</p>
  </div>
</template>

<script setup>
defineProps(['nama'])
</script>