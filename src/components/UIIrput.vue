<template>
  <label v-if="label">
    {{ label }}
  </label>
  <input type="text">
</template>

<script lang="ts" setup>
import { defineProps } from 'vue';

defineProps({
  label: {
    type: String,
    default: '',
  }
});

console.log('UIinputter');
</script>

