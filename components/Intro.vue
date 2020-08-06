<template>
  <section class="intro">
    <div class="container_wrapp">
      <div class="intro_text">
        <h2>Lorem ipsum</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
           Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
           Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
           Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
      </div>
      <div class="intro_image">
        <img src="/intro.png" alt="intro">
      </div>
    </div>
  </section>
</template>

<script>

export default {

};
</script>

<style>
.intro {
  background-color: #FFFFFF;
  color: #000000;
}

.intro_text {
  padding: 0 15px 0;
}

.intro_text h2 {
  padding: 50px 0 50px;
  font-family: 'Roboto', sans-serif;
  font-weight: 700;
  font-size: 54px;
  text-align: center;
}

.intro_text p {
  font-family: 'Roboto', sans-serif;
  font-weight: 300;
  padding-bottom: 60px;
  font-size: 19px;
}

.intro_image {
  padding: 0px 15px 70px;
  display: flex;
  justify-content: center;
}

@media (min-width: 320px) and (max-width: 576px) {
  .intro_text {
    padding: 0 20px 0;
  }
  .intro_text h2 {
    font-size: 42px;
  }

  .intro_text p {
    font-size: 15px;
  }
}
</style>
