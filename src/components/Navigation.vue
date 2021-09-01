<template>
  <div class='Navigation'>
    <div
      class="Navigation__item"
      v-for="item in navItems"
      :key="item.name">
      <span>{{ item.name }}</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Navigation',
  data: () => ({
    navItems: [
      {name: 'Navigation item 1', path: '/'},
      {name: 'Navigation item 2', path: '/'},
      {name: 'Navigation item 3', path: '/'},
      {name: 'Navigation item 4', path: '/'},
    ]
  }),
}
</script>

<style lang='scss'>
.Navigation {
  &__item {
    cursor: pointer;
    padding: 8px 16px;
    margin-bottom: 8px;
    background: #302e2e;
    border-radius: 8px;
    color: #ffffff;
    &:hover {
      background: rgba(48, 46, 46, 0.55);
    }
  }
}
</style>
