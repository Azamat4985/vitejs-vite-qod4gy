<script setup>
import { ref } from 'vue';
const isMonteKristo = ref();
</script>

<template>
  <div>
    <label>
      <input v-model="isMonteKristo" type="checkbox" />
      Граф Монте-Кристо
    </label>
    <p>Любимая книга: {{ isMonteKristo }}</p>
  </div>
</template>
