<template>
  <div class="schema_prop">
    <slot>Properties</slot>
  </div>
</template>

<style>
.schema_prop h3 {
  font-family: 'Roboto Bold';
  font-size: 27px;
}

.schema_prop p {
  font-family: 'Roboto Light';
  font-size: 14px;
  padding-top: 8px;
}

@media (min-width: 320px) and (max-width: 576px) {
  .schema_prop {
    padding: 15px;
  }
}

@media (min-width: 576px) and (max-width: 768px) {
  .schema_prop {
    padding: 20px;
  }
}
</style>
