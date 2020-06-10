<template>
  <nav class="menu">
    <nuxt-link to="/" class="menu-link">Главная</nuxt-link>
    <nuxt-link to="/about" class="menu-link">О нас</nuxt-link>
    <nuxt-link to="/service" class="menu-link">Сервис</nuxt-link>
    <nuxt-link to="/blog" class="menu-link">Блог</nuxt-link>
    <nuxt-link to="/contact" class="menu-link">Контакты</nuxt-link>
  </nav>
</template>

<script>
export default {}
</script>

<style scoped>
.menu {
  width: 400px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.menu-link {
  color: black;
  text-decoration: none;
  font-size: 18px;
  font-weight: bold;
}
.menu-link:hover {
  color: chartreuse;
}
.menu-link:active {
  padding: 10px;
  color: white;
  background-color: chartreuse;
  border-radius: 3px;
}
</style>
