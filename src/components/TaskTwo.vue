<script setup>
import List from './List.vue';
const people = [
  {
    name: 'Майкл',
    salary: 1000,
  },
  {
    name: 'Антон',
    salary: 2000,
  },
  {
    name: 'Аслан',
    salary: 3000,
  },
];
</script>

<template>
  <List :people="people" />
</template>
