<template>
  <div>
    <Hero/>
  </div>
</template>

<script>
import Hero from '@/components/Hero'

export default {
  components: {
    Hero,
  }
};
</script>

<style>
*{
  margin: 0;
  padding: 0;
  color: white;
}

img {
  max-width: 100%;
}

.container_wrapp {
  max-width: 1200px;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
</style>
