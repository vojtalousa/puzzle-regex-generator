<template>
    <SectionTitle text="Generated Regex" />
    <div class="result"></div>
</template>

<script>
import SectionTitle from "@/components/SectionTitle";
export default {
name: "RegexResult",
  components: {SectionTitle}
}
</script>

<style scoped>
  .result {
    height: 60px;
    background-color: var(--main2-color);
    margin-bottom: 20px;
    border-radius: 15px;
  }
</style>
