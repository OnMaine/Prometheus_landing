<template>
  <section class="schema">
    <div class="container_wrapp">
      <div class="schema_content">
        <schema-img>
          <h3>Mounting holes</h3>
          <img src="/schema1.png" alt="Mounting holes">
        </schema-img>
        <schema-img class="schema_image">
          <img src="/schema2.png" alt="DJi 20mm acum">
        </schema-img>
        <schema-img>
          <h3>DJI FPV system placing</h3>
          <img src="/schema3.png" alt="DJI system placing">
        </schema-img>
      </div>
    </div>
  </section>
</template>

<script>
import SchemaImg from '~/components/SchemaImg';

export default {
  components: {
    SchemaImg
  }
};
</script>

<style>
.schema {
  background-color: #d0d0d0;
  color: #000000;
}

.schema_content {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  align-items: center;
}
</style>
