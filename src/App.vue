<template>
  <TheSidebar/>
  <RegexAssembly/>
</template>

<script>
import RegexAssembly from "@/components/RegexAssembly";
import TheSidebar from "@/components/TheSidebar";

export default {
  name: 'App',
  components: {
    TheSidebar,
    RegexAssembly,
  }
}
</script>

<style>
:root {
  --accent-color: #6263D5;
  --main-color: #E8EBF4;
  --main2-color: #ffffff;
  --text-color: #393939;
  --text2-color: white;
  --placeholder-color: #868686;

}


* {
  font-family: 'Open Sans', sans-serif;
  padding: 0;
  margin: 0;
  user-select: none;
  transition: 0.2s;
  box-sizing: border-box;
}

body, html {
  width: 100%;
  height: 100%;
}

#app {
  background-color: var(--main-color);
  width: 100%;
  height: 100%;
  display: flex;
  gap: 30px;
  padding: 40px;
}


</style>
