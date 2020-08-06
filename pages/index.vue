<template>
  <div>
    <Hero />
    <Intro />
    <Specifications />
    <Schema />
    <Camera />
    <Quality />
  </div>
</template>
Quality
<script>
import Hero from '@/components/Hero'
import Intro from '@/components/Intro'
import Specifications from '@/components/Specifications'
import Schema from '@/components/Schema'
import Camera from '@/components/Camera'
import Quality from '@/components/Quality'


export default {
  components: {
    Hero,
    Intro,
    Specifications,
    Schema,
    Camera,
    Quality
  }
};
</script>

<style>
*{
  margin: 0;
  padding: 0;
}

img {
  max-width: 100%;
}

.container_wrapp {
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

@media (min-width: 320px) and (max-width: 576px) {
  .container_wrapp {
    max-width: 320px;
  }
}

@media (min-width: 576px) and (max-width: 768px) {
  .container_wrapp {
    max-width: 576px;
  }
}

@media (min-width: 768px) and (max-width: 992px) {
  .container_wrapp {
    max-width: 768px;
  }
}

@media (min-width: 992px) and (max-width: 1200px) {
  .container_wrapp {
    max-width: 992px;
  }
}

@media (min-width: 1200px) {
  .container_wrapp {
    max-width: 1200px;
  }
}
</style>
