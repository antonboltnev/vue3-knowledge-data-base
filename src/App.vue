<template>
  <main class="page-container">
    <Sidebar />
    <Content />
  </main>
</template>

<script>
import Sidebar from "./layouts/Sidebar";
import Content from "./layouts/Content";

export default {
  name: 'App',
  components: {
    Sidebar,
    Content
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

main {
  display: flex;
  position: fixed;
  top: 0;
  bottom: 0;
  right: 0;
  left: 0;
}

</style>
