<template>
  <div class="section-component-node">
    <div class="roxie-ward-12">AUG</div>
    <img class="rectangle-12" alt="Rectangle" src="/img/rectangle-202.svg" />
    <img class="rectangle-13" alt="Rectangle" src="/img/rectangle-203.svg" />
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "SectionComponentNode",
});
</script>

<style>
.section-component-node {
  height: 232px;
  left: 337px;
  position: absolute;
  top: 70px;
  width: 32px;
}

.section-component-node .roxie-ward-12 {
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
  width: 29px;
}

.section-component-node .rectangle-12 {
  height: 199px;
  left: 12px;
  position: absolute;
  top: 0;
  width: 10px;
}

.section-component-node .rectangle-13 {
  height: 80px;
  left: 2px;
  position: absolute;
  top: 130px;
  width: 30px;
}
</style>