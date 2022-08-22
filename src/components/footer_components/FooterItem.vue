<script setup>
defineProps({
  text: {
    type: String,
    default: "bug",
  },
});
</script>

<template>
  <li>{{ text }}</li>
</template>
