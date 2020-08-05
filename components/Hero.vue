<template>
  <section class="hero">
    <div class="container_wrapp">
      <div class="hero_text">
        <h1>Prometheus</h1>
        <span class="hero_text__mark">FPV freestyle frame</span>
        <p>Full titanium. Durable. Maintenable.</p>
      </div>
      <div class="hero_image">
        <img src="/hero-main.png" alt="Hero DJI">
      </div>
      <div class="hero_target">
        <span class="hero-target__price">&#36; 170.00</span>
        <hero-btn>PRE-ORDER NOW</hero-btn>
        <!-- <div class="hero-target__img">
          <img src="/hero-logo.png" alt="">
        </div> -->
      </div>
    </div>
  </section>
</template>

<script>
import HeroBtn from '~/components/HeroBtn';

export default {
  components: {
    HeroBtn
  }
};
</script>


<style>
.hero {
  background-color: #2f2f2f;
  text-align: center;
  color: #FFFFFF;
}

.hero_text h1 {
  /* padding-top:55px; */
  padding: 25px 0 25px;
  font-family: 'Roboto Black';
  font-size: 80px;
}

.hero_text p {
  font-family: 'Roboto Medium';
  padding: 20px;
  font-size: 27px;
}

.hero_text__mark {
  font-family: 'Roboto Thin';
  font-size: 20px;
}

.hero_image {
  padding: 30px 15px 45px;
  display: flex;
  justify-content: center;
}

.hero_target {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: flex-end;
  padding-bottom: 40px;
}

.hero-target__price {
  font-family: 'Roboto Black';
  font-size: 40px;
  margin-right: 18px;
}
/* переделать! */
.hero-target__img {
  position: absolute;
  left: 75%;
}

@media (min-width: 320px) and (max-width: 576px) {
  .hero_text h1 {
    font-size: 50px;
  }
  .hero_text p {
    font-size: 25px;
  }
  .hero_text__mark {
    font-size: 15px;
  }
  .hero-target__price {
    padding-bottom: 20px;
  }
}
</style>
