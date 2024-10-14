<template>
  <div class="overlap-wrapper">
    <div class="roxie-ward-8">JUL</div>
    <img class="rectangle-4" alt="Rectangle" src="/img/rectangle-200.svg" />
    <img class="rectangle-5" alt="Rectangle" src="/img/rectangle-201.svg" />
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "OverlapWrapper",
});
</script>

<style>
.overlap-wrapper {
  height: 232px;
  left: 297px;
  position: absolute;
  top: 70px;
  width: 31px;
}

.overlap-wrapper .roxie-ward-8 {
  color: #828282;
  font-family: "Inter", Helvetica;
  font-size: 9px;
  font-weight: 500;
  height: 27px;
  left: 0;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  text-align: center;
  top: 205px;
  width: 24px;
}

.overlap-wrapper .rectangle-4 {
  height: 199px;
  left: 12px;
  position: absolute;
  top: 0;
  width: 10px;
}

.overlap-wrapper .rectangle-5 {
  height: 142px;
  left: 0;
  position: absolute;
  top: 68px;
  width: 31px;
}
</style>