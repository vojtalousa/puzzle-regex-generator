<template>
  <h2 class="title">{{ text }}</h2>
</template>

<script>
export default {
  name: "SectionTitle",
  props: {
    text: String
  }
}
</script>

<style scoped>
.title {
  font-weight: 700;
  color: var(--text-color);
  font-size: 1.15em;
  margin-bottom: 10px;
  max-width: 80%;
}
</style>
