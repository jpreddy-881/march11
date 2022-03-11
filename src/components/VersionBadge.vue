<template>
  <a
      target="_blank"
  >
    <q-badge color="primary">v{{ version }}</q-badge>
  </a>
</template>

<script setup>
const version = PACKAGE_VERSION
</script>
