<template>
  <div class="tabbar">
    <slot></slot>
  </div>
</template>

<script>
    export default {
        name: "TabBar"
    }
</script>

<style scoped>
  .tabbar {
    display: flex;
    background-color: #f0f0f0;
    box-shadow: 0 -1px 1px rgba(100, 100, 100, 0.1);

    position: fixed;
    bottom: 0;
    left: 0;
    right: 0;

  }
</style>
