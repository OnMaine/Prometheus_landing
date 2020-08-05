<template>
  <section class="schema">
    <div class="container_wrapp">
      <div class="schema_image">
        <img src="/schema.png" alt="intro">
      </div>
      <div class="schema_properties">
        <schema-prop>
          <h3>230mm</h3>
          <p>wheelbase</p>
        </schema-prop>
        <schema-prop>
          <h3>5”</h3>
          <p>prop size</p>
        </schema-prop>
        <schema-prop>
          <h3>190g</h3>
          <p>weight</p>
        </schema-prop>
        <schema-prop>
          <img src="/Titanium.png" alt="schema titanium element">
          <p>titanium full body</p>
        </schema-prop>
        <schema-prop>
          <h3>Compressed X</h3>
          <p>frame shape</p>
        </schema-prop>
        <schema-prop>
          <h3>Freestyle</h3>
          <p>frame type</p>
        </schema-prop>
      </div>
    </div>
  </section>
</template>

<script>
import SchemaProp from '~/components/SchemaProp';

export default {
  components: {
    SchemaProp
  }
};
</script>


<style>
.schema {
  background-color: #2f2f2f;
  color: #FFFFFF;
}

.schema_properties {
  display: flex;
  flex-wrap: wrap;
  flex-direction: row;
  justify-content: space-around;
  align-items: flex-end;
  padding-bottom: 20px;
  text-align: center;
}

.schema_image {
  padding: 58px 15px 20px;
  display: flex;
  justify-content: center;
}
</style>
