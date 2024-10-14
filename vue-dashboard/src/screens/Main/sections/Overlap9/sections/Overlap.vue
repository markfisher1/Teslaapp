<template>
  <div class="overlap">
    <div class="roxie-ward">JAN</div>
    <img class="rectangle" alt="Rectangle" src="/img/rectangle-188.svg" />
    <img class="img" alt="Rectangle" src="/img/rectangle-189.svg" />
    <div class="group-2">
      <div class="roxie-ward-2">400</div>
      <div class="roxie-ward-3">300</div>
      <div class="roxie-ward-4">200</div>
      <div class="roxie-ward-5">100</div>
      <div class="roxie-ward-6">0</div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "Overlap",
});
</script>

<style>
.overlap {
  height: 233px;
  left: 20px;
  position: absolute;
  top: 69px;
  width: 60px;
}

.overlap .roxie-ward {
  color: #828282;
  font-family: "Inter", Helvetica;
  font-size: 9px;
  font-weight: 500;
  height: 27px;
  left: 32px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  text-align: center;
  top: 206px;
  width: 23px;
}

.overlap .rectangle {
  height: 199px;
  left: 40px;
  position: absolute;
  top: 1px;
  width: 10px;
}

.overlap .img {
  height: 80px;
  left: 30px;
  position: absolute;
  top: 131px;
  width: 30px;
}

.overlap .group-2 {
  height: 196px;
  left: 0;
  opacity: 0.5;
  position: absolute;
  top: 0;
  width: 33px;
}

.overlap .roxie-ward-2 {
  color: var(--base-shade-100);
  font-family: "Inter", Helvetica;
  font-size: 9.7px;
  font-weight: 600;
  left: 1px;
  letter-spacing: 0;
  line-height: 12.6px;
  position: absolute;
  text-align: right;
  top: 0;
  white-space: nowrap;
  width: 22px;
}

.overlap .roxie-ward-3 {
  color: var(--base-shade-100);
  font-family: "Inter", Helvetica;
  font-size: 9.7px;
  font-weight: 600;
  left: 1px;
  letter-spacing: 0;
  line-height: 12.6px;
  position: absolute;
  text-align: right;
  top: 46px;
  white-space: nowrap;
  width: 22px;
}

.overlap .roxie-ward-4 {
  color: var(--base-shade-100);
  font-family: "Inter", Helvetica;
  font-size: 9.7px;
  font-weight: 600;
  left: 1px;
  letter-spacing: 0;
  line-height: 12.6px;
  position: absolute;
  text-align: right;
  top: 91px;
  white-space: nowrap;
  width: 22px;
}

.overlap .roxie-ward-5 {
  color: var(--base-shade-100);
  font-family: "Inter", Helvetica;
  font-size: 9.7px;
  font-weight: 600;
  left: 1px;
  letter-spacing: 0;
  line-height: 12.6px;
  position: absolute;
  text-align: right;
  top: 137px;
  white-space: nowrap;
  width: 22px;
}

.overlap .roxie-ward-6 {
  color: var(--base-shade-100);
  font-family: "Inter", Helvetica;
  font-size: 9.7px;
  font-weight: 600;
  left: 0;
  letter-spacing: 0;
  line-height: 12.6px;
  position: absolute;
  text-align: right;
  top: 183px;
  white-space: nowrap;
  width: 22px;
}
</style>