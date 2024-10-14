<template>
  <div class="overlap-9">
    <Overlap />
    <OverlapGroup />
    <OverlapWrapper />
    <OverlapGroupWrapper />
    <DivWrapper />
    <Div />
    <SectionComponentNode />
    <Overlap1 />
    <div class="roxie-ward-17">MAR</div>
    <Overlap2 />
    <Overlap3 />
    <Overlap4 />
    <div class="overlap-17">
      <img class="rectangle-23" alt="Rectangle" src="/img/rectangle-192.svg" />
      <img class="rectangle-24" alt="Rectangle" src="/img/rectangle-193.svg" />
    </div>
    <div class="january">Activity</div>
    <img class="line-2" alt="Line" src="/img/line-23.svg" />
    <Overlap5 />
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import Overlap from "./sections/Overlap";
import OverlapGroup from "./sections/OverlapGroup";
import OverlapWrapper from "./sections/OverlapWrapper";
import OverlapGroupWrapper from "./sections/OverlapGroupWrapper";
import DivWrapper from "./sections/DivWrapper";
import Div from "./sections/Div";
import SectionComponentNode from "./sections/SectionComponentNode";
import Overlap1 from "./sections/Overlap1";
import Overlap2 from "./sections/Overlap2";
import Overlap3 from "./sections/Overlap3";
import Overlap4 from "./sections/Overlap4";
import Overlap5 from "./sections/Overlap5";

export default Vue.extend({
  name: "Overlap9",
  components: {
    Overlap,
    OverlapGroup,
    OverlapWrapper,
    OverlapGroupWrapper,
    DivWrapper,
    Div,
    SectionComponentNode,
    Overlap1,
    Overlap2,
    Overlap3,
    Overlap4,
    Overlap5,
  },
});
</script>

<style>
.overlap-9 {
  background-color: #ffffff;
  border: 1px solid;
  border-color: var(--stroke-color);
  border-radius: 20px;
  box-shadow: var(--tile-dropshadow);
  height: 322px;
  left: 843px;
  position: absolute;
  top: 202px;
  width: 556px;
}

.overlap-9 .roxie-ward-17 {
  color: #828282;
  font-family: "Inter", Helvetica;
  font-size: 9px;
  font-weight: 500;
  height: 15px;
  left: 128px;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  text-align: center;
  top: 280px;
  width: 29px;
}

.overlap-9 .overlap-17 {
  height: 210px;
  left: 133px;
  position: absolute;
  top: 70px;
  width: 30px;
}

.overlap-9 .rectangle-23 {
  height: 199px;
  left: 10px;
  position: absolute;
  top: 0;
  width: 10px;
}

.overlap-9 .rectangle-24 {
  height: 96px;
  left: 0;
  position: absolute;
  top: 114px;
  width: 30px;
}

.overlap-9 .january {
  color: #4d4d4d;
  font-family: var(--body-1-medium-font-family);
  font-size: var(--body-1-medium-font-size);
  font-style: var(--body-1-medium-font-style);
  font-weight: var(--body-1-medium-font-weight);
  height: 17px;
  left: 19px;
  letter-spacing: var(--body-1-medium-letter-spacing);
  line-height: var(--body-1-medium-line-height);
  position: absolute;
  top: 13px;
  width: 238px;
}

.overlap-9 .line-2 {
  height: 1px;
  left: 19px;
  position: absolute;
  top: 41px;
  width: 511px;
}
</style>