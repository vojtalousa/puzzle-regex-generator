<template>
  <div class="wrapper">
    <SectionTitle text="Regex Assembly"/>
    <div class="assembly"></div>
  </div>
</template>

<script>
import SectionTitle from "@/components/SectionTitle";

export default {
  name: "RegexAssembly",
  components: {SectionTitle}
}
</script>

<style scoped>
.wrapper {
    flex-grow: 1;
  display: flex;
  flex-direction: column;
}

.assembly {
  background-color: var(--main2-color);
  flex-grow: 1;
  border-radius: 15px;
  background: radial-gradient(var(--main-color) 1px, transparent 2px), var(--main2-color);
  background-size: 35px 35px;
}
</style>
