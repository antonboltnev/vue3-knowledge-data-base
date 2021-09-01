<template>
  <div class="Sidebar">
    <h1>Sidebar layout</h1>
    <p>This is the sidebar area of the app</p>
    <Navigation />
  </div>
</template>

<script>
import Navigation from "@/components/Navigation";
export default {
  name: 'Sidebar',
  components: { Navigation }
}
</script>

<style lang="scss">
.Sidebar {
  flex-basis: 25%;
  background: $green-bg;
  padding: 8px;
}
</style>
