<template>
  <p>{{ games }}</p>
</template>

<script setup>
  import { computed } from 'vue';
  import store from '../store'
  const games = computed(() => store.state.games)
</script>

<style>

</style>