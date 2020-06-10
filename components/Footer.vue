<template>
  <div class="footer">
    <div class="footer__content">
      <div class="footer__block-one">
        <img src="/logo-light.png" alt class="footer__logo" />
        <p class="footer__text">
          Phasellus vehicleula tempus orci vel consquat.
          Nullam lorem sem, viverra a rutrum sed, gravida mattis magna.
          Suspendisse Vitae Commodo Quam. Quisque a enim et ante vulputate finibus nec laoreet ipsum.
        </p>

        <a href class="footer__social">
          <img class="footer__social-icon" src="/facebok.png" alt />
        </a>
        <a href class="footer__social">
          <img class="footer__social-icon" src="/facebok.png" alt />
        </a>
        <a href class="footer__social">
          <img class="footer__social-icon" src="/facebok.png" alt />
        </a>
        <a href class="footer__social">
          <img class="footer__social-icon" src="/facebok.png" alt />
        </a>
        <a href class="footer__social">
          <img class="footer__social-icon" src="/facebok.png" alt />
        </a>
        <a href class="footer__social">
          <img class="footer__social-icon" src="/facebok.png" alt />
        </a>
      </div>
      <div class="footer__block-two">
        <h2 class="footer__title">Наши сервисы</h2>

        <ul class="footer__list">
          <li class="footer__item">
            <a class="footer__link" href="#">Зубные Имплантаты</a>
          </li>
          <li class="footer__item">
            <a class="footer__link" href="#">Фигурные скобки</a>
          </li>
          <li class="footer__item">
            <a class="footer__link" href="#">Висдон Тит</a>
          </li>
          <li class="footer__item">
            <a class="footer__link" href="#">Фарфоровые виниры</a>
          </li>
          <li class="footer__item">
            <a class="footer__link" href="#">Отбеливание зубов</a>
          </li>
          <li class="footer__item">
            <a class="footer__link" href="#">Стоматологические мосты</a>
          </li>
        </ul>
      </div>
      <div class="footer__block-three">
        <h2 class="footer__title-hours">Часы работы</h2>
        <p class="footer__operating-mode">понедельник 8:00 - 12:00</p>
        <p class="footer__operating-mode">вторник 8:00 - 12:00</p>
        <p class="footer__operating-mode">среда 8:00 - 12:00</p>
        <p class="footer__operating-mode">четверг 8:00 - 12:00</p>
        <p class="footer__operating-mode">пятница 8:00 - 12:00</p>
        <p class="footer__operating-mode">суббота 8:00 - 12:00</p>
        <p class="footer__operating-mode">воскресенье 8:00 - 12:00</p>
      </div>
    </div>
    <my-menu />
  </div>
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
.footer {
  width: 100%;
  padding: 100px;

  color: white;
  background-image: url(/footer-bg.jpg);
  background-repeat: no-repeat;
  background-size: cover;
}
.footer__content {
  display: flex;
}
.footer__block-one {
  max-width: 350px;
}
.footer__social-icon {
  width: 20px;
  height: 20px;
}
.footer__text {
  padding-top: 25px;
  padding-bottom: 70px;
  line-height: 30px;
  opacity: 0.6;
}
.footer__block-two {
  padding-left: 50px;
}
.footer__social {
  padding-right: 8px;
}
.footer__item {
  list-style: none;
  padding-bottom: 20px;
}
.footer__link {
  text-decoration: none;
  opacity: 0.6;
  color: white;
}
.footer__link:hover {
  color: chartreuse;
}
.footer__title {
  padding-top: 10px;
  padding-left: 40px;
  padding-bottom: 50px;
}
.footer__block-three {
  display: flex;
  flex-direction: column;
  margin-left: 300px;

  border: chartreuse solid 2px;
}
.footer__title-hours {
  padding-bottom: 50px;
}
.footer__operating-mode {
  opacity: 0.6;
}
</style>
