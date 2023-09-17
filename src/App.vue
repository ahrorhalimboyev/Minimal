<template>
  <div>
    <Navbar />
    <Body />
    <Body1 />
    <Body2 />
    <Body3 />
    <Body4 />
    <Body5 />
    <Body6 />
    <Body7 />
  </div>
</template>
<script setup>
import { ref } from "vue";
import Navbar from "./components/Navbar.vue";
import Body from "./components/Body.vue";
import Body1 from "./components/Body1.vue";
import Body2 from "./components/Body2.vue";
import Body3 from "./components/Body3.vue";
import Body4 from "./components/Body4.vue";
import Body5 from "./components/Body5.vue";
import Body6 from "./components/Body6.vue";
import Body7 from "./components/Body7.vue";
</script>
<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
