<template>
  <div class="container">
    <div class="container__block">
      <h2 class="container__title">Запишитесь на бесплатную консультацию.</h2>
      <p
        class="container__text"
      >*Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec malesuada lorem maximus.</p>
    </div>
    <button class="container__button">
      <a href="#" class="container__link">Читать далее</a>
    </button>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.container {
  width: 100%;
  display: flex;
  padding: 50px 100px;
  color: white;
  justify-content: space-between;
  background-color: chartreuse;
}
.container__button {
  padding: 20px;
  background-color: white;

  border-radius: 5px;
  border: none;
}
.container__link {
  text-decoration: none;
  color: #000;
  font-size: 16px;
}
</style>
