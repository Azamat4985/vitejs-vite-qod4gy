<script setup>
const props = defineProps(['people']);
</script>

<template>
  <div>
    <div v-for="item in people">
      <p>Имя: {{ item.name }}</p>
      <slot></slot>
    </div>
  </div>
</template>
