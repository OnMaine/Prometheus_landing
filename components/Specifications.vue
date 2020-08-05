<template>
  <section class="Specifications">
    <div class="container_wrapp">
      <div class="Specifications_image">
        <img src="/Specifications.png" alt="intro">
      </div>
      <div class="Specifications_properties">
        <Specifications-prop>
          <h3>230mm</h3>
          <p>wheelbase</p>
        </Specifications-prop>
        <Specifications-prop>
          <h3>5”</h3>
          <p>prop size</p>
        </Specifications-prop>
        <Specifications-prop>
          <h3>190g</h3>
          <p>weight</p>
        </Specifications-prop>
        <Specifications-prop>
          <img src="/Titanium.png" alt="Specifications titanium element">
          <p>titanium full body</p>
        </Specifications-prop>
        <Specifications-prop>
          <h3>Compressed X</h3>
          <p>frame shape</p>
        </Specifications-prop>
        <Specifications-prop>
          <h3>Freestyle</h3>
          <p>frame type</p>
        </Specifications-prop>
      </div>
    </div>
  </section>
</template>

<script>
import SpecificationsProp from '~/components/SpecificationsProp';

export default {
  components: {
    SpecificationsProp
  }
};
</script>


<style>
.Specifications {
  background-color: #2f2f2f;
  color: #FFFFFF;
}

.Specifications_properties {
  display: flex;
  flex-wrap: wrap;
  flex-direction: row;
  justify-content: space-around;
  align-items: flex-end;
  padding-bottom: 20px;
  text-align: center;
}

.Specifications_image {
  padding: 58px 15px 20px;
  display: flex;
  justify-content: center;
}
</style>
