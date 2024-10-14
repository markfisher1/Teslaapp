<template>
  <div class="div-wrapper">
    <div class="roxie-ward-10">FEB</div>
    <img class="rectangle-8" alt="Rectangle" src="/img/rectangle-190.svg" />
    <img class="rectangle-9" alt="Rectangle" src="/img/rectangle-191.svg" />
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "DivWrapper",
});
</script>

<style>
.div-wrapper {
  height: 232px;
  left: 91px;
  position: absolute;
  top: 70px;
  width: 31px;
}

.div-wrapper .roxie-ward-10 {
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
  width: 25px;
}

.div-wrapper .rectangle-8 {
  height: 199px;
  left: 11px;
  position: absolute;
  top: 0;
  width: 10px;
}

.div-wrapper .rectangle-9 {
  height: 96px;
  left: 1px;
  position: absolute;
  top: 114px;
  width: 30px;
}
</style>