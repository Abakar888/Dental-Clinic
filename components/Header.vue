<template>
  <header class="header">
    <img class="header__logo" src="/logo.png" alt />

    <my-menu />
    <!--  -->
  </header>
</template>

<script>
import Menu from '@/components/Menu'
export default {
  components: {
    'my-menu': Menu,
  },
}
</script>

<style scoped>
.header {
  width: 100%;
  padding: 30px 40px 30px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.header__logo {
  color: black;
  font-size: 42px;
  font-weight: bold;
}
</style>
