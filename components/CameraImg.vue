<template>
  <div class="camera_image">
    <slot>img</slot>
  </div>
</template>

<style>
.camera_image {
  display: flex;
  flex-direction: column;
  text-align: center;
  padding: 33px 15px 60px;
}

@media (min-width: 1200px) {
  .camera_image {
    padding-top: 73px;
  }
}

</style>
