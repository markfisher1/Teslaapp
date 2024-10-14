<template>
  <div class="group-wrapper">
    <div class="div-2">
      <div class="date-dropdown-wrapper">
        <DateDropdown
          class="date-dropdown-instance"
          :icon="iconArrowFullDown"
          showThisYearClassName="design-component-instance-node"
          spanClassName="text-wrapper-6"
          spanClassNameOverride="text-wrapper-7"
          text="Timeframe: "
          text1="All-time"
        />
      </div>
      <IconArrowFullDown4 class="icon-arrow-full-down-1" />
    </div>
    <div class="overlap-14">
      <div class="group-8">
        <div class="show-this-year-wrapper">
          <p class="show-this-year-2">
            <span class="text-wrapper-6">People: </span>
            <span class="text-wrapper-7">All</span>
          </p>
        </div>
      </div>
      <IconArrowFullDown4 class="icon-arrow-full-down-5" />
    </div>
    <div class="overlap-15">
      <div class="div-2">
        <div class="overlap-16">
          <IconArrowFullDown4 class="icon-arrow-full-down-6" />
          <div class="group-9">
            <div class="overlap-group-4">
              <p class="show-this-year-3">
                <span class="text-wrapper-6">Topic: </span>
                <span class="text-wrapper-7">All</span>
              </p>
            </div>
          </div>
        </div>
      </div>
      <IconArrowFullDown4 class="icon-arrow-full-down-3" />
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import DateDropdown from "../../../../components/DateDropdown.vue";
import IconArrowFullDown from "../../../../components/IconArrowFullDown.vue";
import IconArrowFullDown4 from "../../../../icons/IconArrowFullDown4.vue";

export default Vue.extend({
  name: "GroupWrapper",
  components: {
    DateDropdown,
    IconArrowFullDown,
    IconArrowFullDown4,
  },
  data() {
    return {
      iconArrowFullDown: <IconArrowFullDown />,
    };
  },
});
</script>

<style>
.group-wrapper {
  height: 49px;
  left: 283px;
  position: absolute;
  top: 132px;
  width: 1116px;
}

.group-wrapper .div-2 {
  height: 49px;
  left: 0;
  position: absolute;
  top: 0;
  width: 365px;
}

.group-wrapper .date-dropdown-wrapper {
  background-image: url(../../../../../static/img/bounds.svg);
  background-size: 100% 100%;
  height: 49px;
  left: 0;
  position: absolute;
  top: 0;
  width: 365px;
}

.group-wrapper .date-dropdown-instance {
  border-radius: 20px !important;
  display: flex !important;
  height: 33px !important;
  left: 15px !important;
  top: 9px !important;
  width: 173px !important;
}

.group-wrapper .design-component-instance-node {
  font-family: var(--title-medium-font-family) !important;
  font-size: var(--title-medium-font-size) !important;
  font-style: var(--title-medium-font-style) !important;
  font-weight: var(--title-medium-font-weight) !important;
  letter-spacing: var(--title-medium-letter-spacing) !important;
  line-height: var(--title-medium-line-height) !important;
}

.group-wrapper .text-wrapper-6 {
  color: #000000b2 !important;
  font-family: var(--title-medium-font-family) !important;
  font-size: var(--title-medium-font-size) !important;
  font-style: var(--title-medium-font-style) !important;
  font-weight: var(--title-medium-font-weight) !important;
  letter-spacing: var(--title-medium-letter-spacing) !important;
  line-height: var(--title-medium-line-height) !important;
}

.group-wrapper .text-wrapper-7 {
  color: #000000 !important;
  font-family: var(--title-medium-font-family) !important;
  font-size: var(--title-medium-font-size) !important;
  font-style: var(--title-medium-font-style) !important;
  font-weight: var(--title-medium-font-weight) !important;
  letter-spacing: var(--title-medium-letter-spacing) !important;
  line-height: var(--title-medium-line-height) !important;
}

.group-wrapper .icon-arrow-full-down-1 {
  height: 24px !important;
  left: 329px !important;
  position: absolute !important;
  top: 14px !important;
  width: 24px !important;
}

.group-wrapper .overlap-14 {
  height: 49px;
  left: 375px;
  position: absolute;
  top: 0;
  width: 365px;
}

.group-wrapper .group-8 {
  background-image: url(../../../../../static/img/bounds-1.svg);
  background-size: 100% 100%;
  height: 49px;
  left: 0;
  position: absolute;
  top: 0;
  width: 365px;
}

.group-wrapper .show-this-year-wrapper {
  height: 30px;
  left: 18px;
  position: relative;
  top: 10px;
  width: 291px;
}

.group-wrapper .show-this-year-2 {
  color: transparent;
  font-family: var(--title-medium-font-family);
  font-size: var(--title-medium-font-size);
  font-style: var(--title-medium-font-style);
  font-weight: var(--title-medium-font-weight);
  height: 30px;
  left: 0;
  letter-spacing: var(--title-medium-letter-spacing);
  line-height: var(--title-medium-line-height);
  position: absolute;
  top: 0;
  width: 289px;
}

.group-wrapper .icon-arrow-full-down-5 {
  height: 24px !important;
  left: 328px !important;
  position: absolute !important;
  top: 14px !important;
  width: 24px !important;
}

.group-wrapper .overlap-15 {
  height: 49px;
  left: 751px;
  position: absolute;
  top: 0;
  width: 365px;
}

.group-wrapper .overlap-16 {
  height: 49px;
  position: relative;
  width: 367px;
}

.group-wrapper .icon-arrow-full-down-6 {
  height: 33px !important;
  left: 311px !important;
  position: absolute !important;
  top: 8px !important;
  width: 41px !important;
}

.group-wrapper .group-9 {
  height: 49px;
  left: 0;
  position: absolute;
  top: 0;
  width: 367px;
}

.group-wrapper .overlap-group-4 {
  background-image: url(../../../../../static/img/bounds-2.svg);
  background-size: 100% 100%;
  height: 49px;
  position: relative;
  width: 365px;
}

.group-wrapper .show-this-year-3 {
  color: transparent;
  font-family: var(--title-medium-font-family);
  font-size: var(--title-medium-font-size);
  font-style: var(--title-medium-font-style);
  font-weight: var(--title-medium-font-weight);
  height: 30px;
  left: 19px;
  letter-spacing: var(--title-medium-letter-spacing);
  line-height: var(--title-medium-line-height);
  position: absolute;
  top: 10px;
  width: 280px;
}

.group-wrapper .icon-arrow-full-down-3 {
  height: 24px !important;
  left: 332px !important;
  position: absolute !important;
  top: 15px !important;
  width: 24px !important;
}
</style>