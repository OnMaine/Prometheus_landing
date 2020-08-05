<template>
  <div class="schema_image">
    <slot>img</slot>
  </div>
</template>

<style>
.schema_image {
  display: flex;
  flex-direction: column;
  text-align: center;
  padding-bottom: 85px;
}

.schema_image h3 {
  padding: 50px 0 40px;
  font-family: 'Roboto Medium';
  font-size: 23px;
  text-align: center;
}

.schema_image:last-child h3 {
  padding-bottom: 15px;
}

@media (min-width: 320px) and (max-width: 1199px) {
  .schema_image:last-child h3 {
    padding-bottom: 40px;
  }
  .schema_image {
    padding: 15px 15px 55px 15px;
  }
}

</style>
