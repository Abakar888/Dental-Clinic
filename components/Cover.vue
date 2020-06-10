<template>
  <div class="cover">
    <div class="cover__content">
      <h1 class="cover__title">Лучший стоматолог</h1>
      <p class="cover__text">
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
        Porro veniam hic doloremque architecto quidem aperiam culpa sint
        exercitationem eaque obcaecati!
      </p>
      <button class="cover__button">
        <a href="#" class="cover__link">Читать далее</a>
      </button>
      <ul class="cover__slide">
        <li class="cover_link">01,</li>
        <li class="cover_link">02,</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.cover {
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 0 auto;
  color: #fff;
  padding: 200px 800px 20px 0;
  background-image: url(/dent.jpg);
  background-repeat: no-repeat;
  background-size: cover;
}
.cover__content {
  width: 100%;
  min-height: 400px;
  padding-left: 100px;
}
.cover__title {
  font-size: 72px;
  font-weight: normal;
}
.cover__text {
  font-size: 16px;
  font-weight: normal;
  margin-bottom: 80px;
}
.cover__button {
  padding: 20px;
  background-color: chartreuse;
  margin-bottom: 80px;
  border-radius: 5px;
  border: none;
}
.cover__link {
  text-decoration: none;
  color: #fff;
  font-size: 16px;
}
.cover__slide {
  display: flex;
  padding-left: 0;
}
.cover_link {
  list-style: none;
  margin-left: 5px;
}
</style>
