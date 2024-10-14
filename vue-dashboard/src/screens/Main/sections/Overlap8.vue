<template>
  <div class="overlap-8">
    <div class="group-6">
      <div class="overlap-12">
        <div class="bottom">
          <div class="subtext">Out of 43</div>
        </div>
        <div class="group-7">
          <div class="small-graph-wrapper">
            <div class="small-graph">
              <div class="metric">64%</div>
            </div>
          </div>
          <div class="overlap-13">
            <div class="small-graph">
              <div class="metric-2">86%</div>
              <div class="title">
                <div class="primary-title">Current Knowledge</div>
              </div>
              <img class="graph" alt="Graph" src="/img/graph.png" />
            </div>
          </div>
          <div class="overlap-group-3">
            <div class="small-graph">
              <div class="metric-3">+34%</div>
              <div class="title">
                <div class="primary-title">Knowledge Gain</div>
              </div>
              <img class="graph-2" alt="Graph" src="/img/graph-1.png" />
            </div>
          </div>
        </div>
        <div class="primary-title-2">Starting Knowledge</div>
      </div>
      <div class="group-7">
        <div class="small-graph-wrapper">
          <div class="small-graph">
            <p class="p">
              <span class="text-wrapper-4">27</span>
              <span class="text-wrapper-5">/80</span>
            </p>
            <div class="primary-title-wrapper">
              <div class="primary-title">Active Users</div>
            </div>
          </div>
        </div>
        <div class="overlap-13">
          <div class="small-graph">
            <div class="metric-4">3,298</div>
            <div class="title-2">
              <div class="primary-title">Questions Answered</div>
            </div>
          </div>
        </div>
        <div class="overlap-group-3">
          <div class="small-graph">
            <div class="metric-5">2m 34s</div>
            <div class="title-3">
              <div class="primary-title">Av. Session Length</div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <img class="graph-3" alt="Graph" src="/img/graph-2.png" />
    <IconInfoCircleLine1 class="icon-info-circle" />
  </div>
</template>

<script lang="ts">
import Vue, { PropType } from 'vue';
import IconInfoCircleLine1 from '../../../icons/IconInfoCircleLine1.vue';

export default Vue.extend({
  name: 'Overlap8',
  components: {
    IconInfoCircleLine1,
  },
});
</script>

<style>
.overlap-8 {
  height: 322px;
  left: 283px;
  position: absolute;
  top: 202px;
  width: 538px;
}

.overlap-8 .group-6 {
  box-shadow: var(--tile-dropshadow);
  height: 322px;
  left: 0;
  position: absolute;
  top: 0;
  width: 538px;
}

.overlap-8 .overlap-12 {
  height: 152px;
  left: 0;
  position: absolute;
  top: 170px;
  width: 536px;
}

.overlap-8 .bottom {
  align-items: center;
  display: flex;
  gap: 8px;
  height: 17px;
  left: 68px;
  position: absolute;
  top: 24px;
  width: 218px;
}

.overlap-8 .subtext {
  color: var(--base-shade-70);
  font-family: var(--body-1-medium-font-family);
  font-size: var(--body-1-medium-font-size);
  font-style: var(--body-1-medium-font-style);
  font-weight: var(--body-1-medium-font-weight);
  letter-spacing: var(--body-1-medium-letter-spacing);
  line-height: var(--body-1-medium-line-height);
  margin-top: -1.21px;
  position: relative;
  width: 148px;
}

.overlap-8 .group-7 {
  height: 152px;
  left: 0;
  position: absolute;
  top: 0;
  width: 536px;
}

.overlap-8 .small-graph-wrapper {
  background-color: #ffffff;
  border: 1px solid;
  border-color: var(--stroke-color);
  border-radius: 20px;
  height: 152px;
  left: 0;
  position: absolute;
  top: 0;
  width: 171px;
}

.overlap-8 .small-graph {
  height: 107px;
  left: 10px;
  position: relative;
  top: 22px;
  width: 141px;
}

.overlap-8 .metric {
  color: var(--base-shade-100);
  font-family: var(--headline-font-family);
  font-size: var(--headline-font-size);
  font-style: var(--headline-font-style);
  font-weight: var(--headline-font-weight);
  height: 27px;
  left: 7px;
  letter-spacing: var(--headline-letter-spacing);
  line-height: var(--headline-line-height);
  position: absolute;
  top: 35px;
  white-space: nowrap;
  width: 55px;
}

.overlap-8 .overlap-13 {
  background-color: #ffffff;
  border: 1px solid;
  border-color: var(--stroke-color);
  border-radius: 20px;
  height: 152px;
  left: 183px;
  position: absolute;
  top: 0;
  width: 171px;
}

.overlap-8 .metric-2 {
  color: var(--base-shade-100);
  font-family: var(--headline-font-family);
  font-size: var(--headline-font-size);
  font-style: var(--headline-font-style);
  font-weight: var(--headline-font-weight);
  height: 28px;
  left: 7px;
  letter-spacing: var(--headline-letter-spacing);
  line-height: var(--headline-line-height);
  position: absolute;
  top: 34px;
  white-space: nowrap;
  width: 63px;
}

.overlap-8 .title {
  align-items: flex-start;
  display: inline-flex;
  gap: 8px;
  left: 7px;
  position: absolute;
  top: -6px;
}

.overlap-8 .primary-title {
  color: var(--base-shade-70);
  font-family: var(--body-1-medium-font-family);
  font-size: var(--body-1-medium-font-size);
  font-style: var(--body-1-medium-font-style);
  font-weight: var(--body-1-medium-font-weight);
  letter-spacing: var(--body-1-medium-letter-spacing);
  line-height: var(--body-1-medium-line-height);
  margin-top: -1px;
  position: relative;
  width: fit-content;
}

.overlap-8 .graph {
  height: 34px;
  left: 6px;
  position: absolute;
  top: 73px;
  width: 139px;
}

.overlap-8 .overlap-group-3 {
  background-color: #ffffff;
  border: 1px solid;
  border-color: var(--stroke-color);
  border-radius: 20px;
  height: 152px;
  left: 365px;
  position: absolute;
  top: 0;
  width: 171px;
}

.overlap-8 .metric-3 {
  color: var(--base-shade-100);
  font-family: var(--headline-font-family);
  font-size: var(--headline-font-size);
  font-style: var(--headline-font-style);
  font-weight: var(--headline-font-weight);
  height: 28px;
  left: 7px;
  letter-spacing: var(--headline-letter-spacing);
  line-height: var(--headline-line-height);
  position: absolute;
  top: 34px;
  white-space: nowrap;
  width: 79px;
}

.overlap-8 .graph-2 {
  height: 34px;
  left: 5px;
  position: absolute;
  top: 73px;
  width: 139px;
}

.overlap-8 .primary-title-2 {
  color: var(--base-shade-70);
  font-family: var(--body-1-medium-font-family);
  font-size: var(--body-1-medium-font-size);
  font-style: var(--body-1-medium-font-style);
  font-weight: var(--body-1-medium-font-weight);
  left: 17px;
  letter-spacing: var(--body-1-medium-letter-spacing);
  line-height: var(--body-1-medium-line-height);
  position: absolute;
  top: 18px;
  width: 191px;
}

.overlap-8 .p {
  color: transparent;
  font-family: "Inter", Helvetica;
  font-size: 24px;
  font-weight: 400;
  height: 27px;
  left: 7px;
  letter-spacing: 0;
  line-height: 24px;
  position: absolute;
  top: 36px;
  white-space: nowrap;
  width: 83px;
}

.overlap-8 .text-wrapper-4 {
  color: #000000;
  font-family: var(--headline-font-family);
  font-size: var(--headline-font-size);
  font-style: var(--headline-font-style);
  font-weight: var(--headline-font-weight);
  letter-spacing: var(--headline-letter-spacing);
  line-height: var(--headline-line-height);
}

.overlap-8 .text-wrapper-5 {
  color: #00000080;
  font-family: var(--label-emphasized-font-family);
  font-size: var(--label-emphasized-font-size);
  font-style: var(--label-emphasized-font-style);
  font-weight: var(--label-emphasized-font-weight);
  letter-spacing: var(--label-emphasized-letter-spacing);
  line-height: var(--label-emphasized-line-height);
}

.overlap-8 .primary-title-wrapper {
  align-items: flex-start;
  display: inline-flex;
  gap: 8px;
  left: 6px;
  position: absolute;
  top: -5px;
}

.overlap-8 .metric-4 {
  color: var(--base-shade-100);
  font-family: var(--headline-font-family);
  font-size: var(--headline-font-size);
  font-style: var(--headline-font-style);
  font-weight: var(--headline-font-weight);
  height: 28px;
  left: 7px;
  letter-spacing: var(--headline-letter-spacing);
  line-height: var(--headline-line-height);
  position: absolute;
  top: 36px;
  white-space: nowrap;
  width: 84px;
}

.overlap-8 .title-2 {
  align-items: flex-start;
  display: inline-flex;
  gap: 8px;
  left: 7px;
  position: absolute;
  top: -8px;
}

.overlap-8 .metric-5 {
  color: var(--base-shade-100);
  font-family: var(--headline-font-family);
  font-size: var(--headline-font-size);
  font-style: var(--headline-font-style);
  font-weight: var(--headline-font-weight);
  height: 28px;
  left: 7px;
  letter-spacing: var(--headline-letter-spacing);
  line-height: var(--headline-line-height);
  position: absolute;
  top: 36px;
  white-space: nowrap;
  width: 111px;
}

.overlap-8 .title-3 {
  align-items: flex-start;
  display: inline-flex;
  gap: 8px;
  left: 6px;
  position: absolute;
  top: -8px;
}

.overlap-8 .graph-3 {
  height: 34px;
  left: 27px;
  position: absolute;
  top: 266px;
  width: 126px;
}

.overlap-8 .icon-info-circle {
  height: 11px !important;
  left: 152px !important;
  position: absolute !important;
  top: 192px !important;
  width: 11px !important;
}
</style>