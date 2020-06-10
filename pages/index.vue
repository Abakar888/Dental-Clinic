<template>
  <div class="container">
    <my-info></my-info>
    <my-cover></my-cover>
    <my-greenstend />
    <section class="container__content">
      <img src="/about.jpg" alt class="container__icon" />
      <div class="container__block">
        <h1 class="container__title">Мы заботимся о ваших зубах</h1>
        <p class="container__text">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit.
          Duis semper venenatis turpis eget suscipit.
          Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
          Donec eu nulla sollicitudin, vestibulum sapien nec, dictum dolor. Morbi non penatibus et magnis volutpat magna.
        </p>
        <img src="/awards.jpg" alt class="container__icon-awar" />
      </div>
    </section>
    <my-ourservice></my-ourservice>
  </div>
</template>

<script>
import Cover from '@/components/Cover'
import GreenStend from '@/components/GreenStend'
import OurService from '@/components/OurService'
export default {
  components: {
    'my-cover': Cover,
    'my-greenstend': GreenStend,
    'my-ourservice': OurService,
  },
}
</script>

<style scoped>
.container__content {
  display: flex;
  padding: 60px 50px;
}
.container__icon {
  width: 450px;
  height: 380px;
}
.container__block {
  max-width: 700px;
  min-height: 380px;

  padding-left: 30px;
}
.container__title {
  font-size: 42px;
  font-weight: normal;
  opacity: 0.7;
  padding-bottom: 40px;
}
.container__text {
  padding-bottom: 40px;
}
</style>

