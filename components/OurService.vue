<template>
  <div class="container">
    <h1 class="container__title">Наши сервисы</h1>

    <div class="container__content">
      <div class="container__block">
        <h2 class="container__subtitle">Короны мосты</h2>
        <p
          class="container__text"
        >Lorem Ipsum Dolor Sit Amet, Concetetur Adipiscing Elit. Duis sem per venenatis turpis.</p>
        <!-- <img src alt class="container__img" /> -->
      </div>
      <div class="container__block">
        <h2 class="container__subtitle">Имплантанты</h2>
        <p
          class="container__text"
        >Phasellus vehicleula tempus orci vel consquat. Nullam lorem sem, viverra a rutrum sed.</p>
        <!-- <img src alt class="container__img" /> -->
      </div>
      <div class="container__block">
        <h2 class="container__subtitle">Отбеливание зубов</h2>
        <p
          class="container__text"
        >Lorem Ipsum Dolor Sit Amet, Concetetur Adipiscing Elit. Duis sem per venenatis turpis,</p>
        <!-- <img src alt class="container__img" /> -->
      </div>
      <div class="container__block">
        <h2 class="container__subtitle">Корневые каналы</h2>
        <p
          class="container__text"
        >Phasellus vehicleula tempus orci vel consquat. Nullam lorem sem, viverra a rutrum sed.</p>
        <!-- <img src alt class="container__img" /> -->
      </div>
      <div class="container__block">
        <h2 class="container__subtitle">Зубы мудрости</h2>
        <p
          class="container__text"
        >Lorem Ipsum Dolor Sit Amet, Concetetur Adipiscing Elit. Duis sem per venenatis turpis,</p>
        <!-- <img src alt class="container__img" /> -->
      </div>
      <div class="container__block">
        <h2 class="container__subtitle">Фигурные скобки</h2>
        <p
          class="container__text"
        >Nullam lorem sem, viverra a rutru m sed, gravida mattis magna. Suspendisse Vitae Commodo.</p>
        <!-- <img src alt class="container__img" /> -->
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.container {
  margin-top: 100px;
  background-color: #f0f1f4;
}
.container__content {
  width: 70%;
  margin: 0 auto;
  display: flex;
  flex-flow: row wrap;
  justify-content: space-between;
}
.container__title {
  margin-left: 550px;
  margin-bottom: 80px;
  font-weight: normal;
}
.container__subtitle {
  font-weight: normal;
  margin-bottom: 15px;
}
.container__block {
  width: 300px;

  margin-bottom: 100px;
}
</style>
