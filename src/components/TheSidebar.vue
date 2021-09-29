<template>
  <div class="sidebar">
    <TheSidebarResult/>
    <TheSidebarSelection/>
  </div>
</template>

<script>
import TheSidebarResult from "@/components/TheSidebarResult";
import TheSidebarSelection from "@/components/TheSidebarSelection";

export default {
  name: "TheSidebar",
  components: {
    TheSidebarSelection,
    TheSidebarResult
  }
}
</script>

<style scoped>
  .sidebar {
    display: flex;
    flex-direction: column;
    width: 280px;
  }
</style>
