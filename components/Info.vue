<template>
  <div class="container">
    <img src="/map-marker.png" alt class="container__img" />
    <div class="container__block">
      <p class="container__text">Дентал Стрит 20199</p>
      <p class="container__text_opays">Денвер, США</p>
    </div>
    <img src="/clock.png" alt class="container__img" />
    <div class="container__block">
      <p class="container__text">Часы работы</p>
      <p class="container__text_opays">Пн-Сб: 8:00 - 19:00</p>
    </div>
    <img src="/phone.png" alt class="container__img" />
    <div class="container__block">
      <p class="container__text">+885 332 1568</p>
      <p class="container__text_opays">Позвоните нам сейчас!</p>
    </div>
    <img src="/calendar.png" alt class="container__img" />
    <div class="container__block">
      <p class="container__text">Дентал Стрит 20199</p>
      <p class="container__text_opays">Денвер, США</p>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.container {
  width: 100%;
  display: flex;
  justify-content: space-between;
  padding: 50px 130px;
  background-color: #f0f1f4;
}

.container__text {
  font-size: 18px;
}
.container__text_opays {
  opacity: 0.4;
}
</style>
