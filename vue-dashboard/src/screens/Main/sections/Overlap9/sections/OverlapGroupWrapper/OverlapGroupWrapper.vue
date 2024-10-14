<template>
  <div class="overlap-group-wrapper">
    <div class="roxie-ward-9">OCT</div>
    <img class="rectangle-6" alt="Rectangle" src="/img/rectangle-206.svg" />
    <img class="rectangle-7" alt="Rectangle" src="/img/rectangle-207.svg" />
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "OverlapGroupWrapper",
});
</script>

<style>
.overlap-group-wrapper {
  height: 232px;
  left: 422px;
  position: absolute;
  top: 70px;
  width: 30px;
}

.overlap-group-wrapper .roxie-ward-9 {
  color: #828282;
  font-family: "Inter", Helvetica;
  font-size: 9px;
  font-weight: 500;
  height: 27px;
  left: 1px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  text-align: center;
  top: 205px;
  width: 28px;
}

.overlap-group-wrapper .rectangle-6 {
  height: 199px;
  left: 10px;
  position: absolute;
  top: 0;
  width: 10px;
}

.overlap-group-wrapper .rectangle-7 {
  height: 186px;
  left: 0;
  position: absolute;
  top: 24px;
  width: 30px;
}
</style>