<script lang="ts">
export default {
  name: "VHeader",
  props: {
    title: String,
  },
};
</script>

<template>
  <nav>
    <h3>{{ title }}</h3>
  </nav>
</template>
