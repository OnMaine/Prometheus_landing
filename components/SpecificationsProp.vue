<template>
  <div class="Specifications_prop">
    <slot>Properties</slot>
  </div>
</template>

<style>
.Specifications_prop h3 {
  font-family: 'Roboto', sans-serif;
  font-weight: bold;
  font-size: 27px;
}

.Specifications_prop p {
  font-family: 'Roboto', sans-serif;
  font-weight: 300;
  font-size: 14px;
  padding-top: 8px;
}

@media (min-width: 320px) and (max-width: 576px) {
  .Specifications_prop {
    padding: 15px;
  }
}

@media (min-width: 576px) and (max-width: 768px) {
  .Specifications_prop {
    padding: 20px;
  }
}
</style>
