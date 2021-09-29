<template>
    <SectionTitle text="Regex Selection" />
    <div class="selection" />
</template>

<script>
import SectionTitle from "@/components/SectionTitle";
export default {
name: "RegexSelection",
  components: {SectionTitle}
}
</script>

<style scoped>
  .selection {
    height: 100%;
    flex-grow: 1;
    background-color: var(--main2-color);
    border-radius: 15px;
  }
</style>
