<template>
  <section class="quality">
    <div class="container_wrapp">
      <div class="quality_prop">
        <div class="quality_prop_left">
          <div class="">
            <h5>Specs:</h5>
            <p>Wheelbase - 230mm
              Frame shape - Compressed X
              Prop size - 5"
              Weight - 190g
              Type - Freestyle
              Thickness - 3mm on all titanim details, 3mm on all carbonfiber detailes
              Stack height - up to 20mm
              FPV Camera mounting - 21.1mm for DJI HD camera
              FC mounting - 20x20mm and 30.5x30.5 holes are provided
              Motor mounting - slots for 16x16, 16x19 and 19x19mm
              Motor mount pattern - 22xx
              Hardware - 10.9 grade steel bolts, Aluminum standoffs</p>
          </div>
        </div>
        <div class="quality_prop_right">
          <div class="quality_recomendation">
            <h5>Recommended components:</h5>
            <p>Motor size - 2207
              ESC - 4 in 1
              Prop size - 5"
              LiPo - 4-6S/1300mAh</p>
          </div>
          <div class="quality_features">
            <h5>Features:</h5>
            <p>Grade 2/VT1-0 titanium for body
              Titanium camera protection
              Extra maintenable</p>
          </div>
        </div>
      </div>
      <div class="quality_paymant">
        <h4>We Accept:</h4>
        <div class="quality_paymant_img">
          <quality-img>
            <img src="/visa.png" alt="DJI system placing">
          </quality-img>
          <quality-img>
            <img src="/paypal.png" alt="DJI system placing">
          </quality-img>
          <quality-img>
            <img src="/maestro.png" alt="DJI system placing">
          </quality-img>
          <quality-img>
            <img src="/master.png" alt="DJI system placing">
          </quality-img>
          <quality-img>
            <img src="/american.png" alt="DJI system placing">
          </quality-img>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import QualityImg from '~/components/QualityImg';

export default {
  components: {
    QualityImg
  }
};
</script>


<style>
.quality {
  background-color: #212121;
  color: #FFFFFF;
}

.quality_prop {
  display: flex;
  flex-wrap: wrap;
  flex-direction: row;
  justify-content: space-around;
}

.quality_prop_left,
.quality_prop_right,
.quality_paymant {
  padding-top: 45px;
}

.quality_prop_left h5,
.quality_prop_right h5 {
  font-family: 'Roboto', sans-serif;
  font-weight: 500;
  font-size: 14px;
}

.quality_prop_left p,
.quality_prop_right p {
  padding-top: 8px;
  font-family: 'Roboto', sans-serif;
  font-weight: 100;
  font-size: 14px;
  white-space: pre-line;
  line-height: 1.5;
}

.quality_recomendation {
  padding-bottom: 20px;
}

.quality_paymant {
  text-align: center;
  text-transform: uppercase;
}

.quality_paymant_img {
 padding: 5px;
 display: flex;
 flex-wrap: wrap;
 flex-direction: row;
 justify-content: center;
}

@media (min-width: 320px) and (max-width: 576px) {
  .quality_prop_left {
    padding: 15px 60px;
  }
  .quality_prop_right {
    padding-top: 20px;
  }
}

@media (min-width: 576px) and (max-width: 768px) {
  .quality_prop_right {
    display: flex;
    justify-content: space-around;
  }
  .quality_recomendation {
    padding-right: 50px;
  }
}

</style>
