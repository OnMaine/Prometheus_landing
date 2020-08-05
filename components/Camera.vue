<template>
  <section class="camera">
    <div class="container_wrapp">
      <div class="camera_content">
        <camera-img>
          <img src="/camera1.png" alt="camera angle">
          <h4>Camera tilt angle</h4>
        </camera-img>
        <camera-img>
          <img src="/camera2.png" alt="camera mount tilt angle">
          <h4>Camera mount tilt angle</h4>
        </camera-img>
      </div>
    </div>
  </section>
</template>

<script>
import CameraImg from '~/components/CameraImg';

export default {
  components: {
    CameraImg
  }
};
</script>

<style>
.camera {
  background-color: #b4b4b4;
  color: #FFFFFF;
}

.camera_content {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  align-items: flex-end;
}
</style>
