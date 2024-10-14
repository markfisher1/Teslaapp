<template>
  <div class="overlap-7">
    <div class="component-reports">
      <div class="overlap-11">
        <div class="side-nav">
          <div class="frame">
            <SidebarLogo class="sidebar-logo-instance" />
          </div>
          <img class="vector" alt="Vector" src="/img/vector-1.svg" />
        </div>
        <div class="text-wrapper-3">Support</div>
        <div class="rectangle-22" />
        <div class="sidebar-menu">Reports</div>
        <div class="sidebar-menu-2">People</div>
        <img class="icon-people" alt="Icon people" src="/img/icon-people-2.svg" />
        <div class="sidebar-menu-3">Library</div>
        <IconQuiz3 class="icon-quiz" />
        <div class="sidebar-menu-4">Activities</div>
        <div class="sidebar-menu-5">Get Started</div>
        <IconBulb class="icon-bulb" opacity="0.7" />
        <div class="sidebar-menu-6">Settings</div>
        <IconSettings class="icon-settings" opacity="0.7" />
        <IconAssignments3 class="icon-assignments" color="black" opacity="0.7" />
        <img class="line" alt="Line" src="/img/line-20.svg" />
        <input class="name" placeholder="samwheeler@example.com" type="email" />
        <div class="name-2">Sam Wheeler</div>
      </div>
    </div>
    <img class="photo" alt="Photo" src="/img/photo.png" />
    <Tesla class="TESLA" />
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import SidebarLogo from "../../../components/SidebarLogo.vue";
import IconAssignments3 from "../../../icons/IconAssignments3.vue";
import IconBulb from "../../../icons/IconBulb.vue";
import IconQuiz3 from "../../../icons/IconQuiz3.vue";
import IconSettings from "../../../icons/IconSettings.vue";
import Tesla from "../../../icons/Tesla.vue";

export default Vue.extend({
  name: "Overlap7",
  components: {
    SidebarLogo,
    IconAssignments3,
    IconBulb,
    IconQuiz3,
    IconSettings,
    Tesla,
  },
});
</script>

<style>
.overlap-7 {
  height: 1162px;
  left: 0;
  position: absolute;
  top: 0;
  width: 230px;
}

.overlap-7 .component-reports {
  box-shadow: var(--tile-dropshadow);
  height: 1162px;
  left: 0;
  position: absolute;
  top: 0;
  width: 230px;
}

.overlap-7 .overlap-11 {
  border-radius: 20px;
  height: 1162px;
  position: relative;
  width: 246px;
}

.overlap-7 .side-nav {
  background-color: var(--base-white-100);
  border: 1px solid;
  border-color: var(--stroke-color);
  border-radius: 20px;
  height: 1162px;
  left: 0;
  overflow: hidden;
  position: absolute;
  top: 0;
  width: 246px;
}

.overlap-7 .frame {
  align-items: flex-start;
  display: flex;
  flex-direction: column;
  gap: 40px;
  left: 0;
  position: absolute;
  top: 0;
  width: 230px;
}

.overlap-7 .sidebar-logo-instance {
  left: unset !important;
  margin-right: -20px !important;
  position: relative !important;
  top: unset !important;
}

.overlap-7 .vector {
  height: 12px;
  left: 43px;
  position: absolute;
  top: 120px;
  width: 21px;
}

.overlap-7 .text-wrapper-3 {
  color: var(--base-shade-50);
  font-family: var(--title-emphasized-font-family);
  font-size: var(--title-emphasized-font-size);
  font-style: var(--title-emphasized-font-style);
  font-weight: var(--title-emphasized-font-weight);
  left: 42px;
  letter-spacing: var(--title-emphasized-letter-spacing);
  line-height: var(--title-emphasized-line-height);
  position: absolute;
  top: 368px;
  white-space: nowrap;
}

.overlap-7 .rectangle-22 {
  background-color: #1b59f81a;
  border-radius: 10px;
  height: 46px;
  left: 27px;
  position: absolute;
  top: 103px;
  width: 193px;
}

.overlap-7 .sidebar-menu {
  color: #1b59f8;
  font-family: var(--body-1-medium-font-family);
  font-size: var(--body-1-medium-font-size);
  font-style: var(--body-1-medium-font-style);
  font-weight: var(--body-1-medium-font-weight);
  left: 78px;
  letter-spacing: var(--body-1-medium-letter-spacing);
  line-height: var(--body-1-medium-line-height);
  position: absolute;
  top: 116px;
}

.overlap-7 .sidebar-menu-2 {
  color: #4d4d4d;
  font-family: var(--body-1-medium-font-family);
  font-size: var(--body-1-medium-font-size);
  font-style: var(--body-1-medium-font-style);
  font-weight: var(--body-1-medium-font-weight);
  left: 78px;
  letter-spacing: var(--body-1-medium-letter-spacing);
  line-height: var(--body-1-medium-line-height);
  position: absolute;
  top: 231px;
}

.overlap-7 .icon-people {
  height: 24px;
  left: 39px;
  position: absolute;
  top: 226px;
  width: 26px;
}

.overlap-7 .sidebar-menu-3 {
  color: var(--base-shade-70);
  font-family: var(--body-1-medium-font-family);
  font-size: var(--body-1-medium-font-size);
  font-style: var(--body-1-medium-font-style);
  font-weight: var(--body-1-medium-font-weight);
  height: 17px;
  left: 78px;
  letter-spacing: var(--body-1-medium-letter-spacing);
  line-height: var(--body-1-medium-line-height);
  position: absolute;
  top: 174px;
}

.overlap-7 .icon-quiz {
  height: 24px !important;
  left: 38px !important;
  position: absolute !important;
  top: 171px !important;
  width: 24px !important;
}

.overlap-7 .sidebar-menu-4 {
  color: var(--base-shade-70);
  font-family: var(--body-1-medium-font-family);
  font-size: var(--body-1-medium-font-size);
  font-style: var(--body-1-medium-font-style);
  font-weight: var(--body-1-medium-font-weight);
  height: 17px;
  left: 78px;
  letter-spacing: var(--body-1-medium-letter-spacing);
  line-height: var(--body-1-medium-line-height);
  position: absolute;
  top: 288px;
}

.overlap-7 .sidebar-menu-5 {
  color: var(--base-shade-70);
  font-family: var(--body-1-medium-font-family);
  font-size: var(--body-1-medium-font-size);
  font-style: var(--body-1-medium-font-style);
  font-weight: var(--body-1-medium-font-weight);
  left: 78px;
  letter-spacing: var(--body-1-medium-letter-spacing);
  line-height: var(--body-1-medium-line-height);
  position: absolute;
  top: 420px;
}

.overlap-7 .icon-bulb {
  height: 24px !important;
  left: 38px !important;
  position: absolute !important;
  top: 417px !important;
  width: 24px !important;
}

.overlap-7 .sidebar-menu-6 {
  color: var(--base-shade-70);
  font-family: var(--body-1-medium-font-family);
  font-size: var(--body-1-medium-font-size);
  font-style: var(--body-1-medium-font-style);
  font-weight: var(--body-1-medium-font-weight);
  left: 78px;
  letter-spacing: var(--body-1-medium-letter-spacing);
  line-height: var(--body-1-medium-line-height);
  position: absolute;
  top: 476px;
}

.overlap-7 .icon-settings {
  height: 24px !important;
  left: 38px !important;
  position: absolute !important;
  top: 474px !important;
  width: 24px !important;
}

.overlap-7 .icon-assignments {
  height: 24px !important;
  left: 39px !important;
  position: absolute !important;
  top: 285px !important;
  width: 26px !important;
}

.overlap-7 .line {
  height: 1px;
  left: 20px;
  object-fit: cover;
  position: absolute;
  top: 1014px;
  width: 210px;
}

.overlap-7 .name {
  background: transparent;
  border: none;
  color: var(--base-shade-50);
  font-family: var(--body-2-font-family);
  font-size: var(--body-2-font-size);
  font-style: var(--body-2-font-style);
  font-weight: var(--body-2-font-weight);
  left: 40px;
  letter-spacing: var(--body-2-letter-spacing);
  line-height: var(--body-2-line-height);
  padding: 0;
  position: absolute;
  top: 1106px;
}

.overlap-7 .name-2 {
  color: var(--base-shade-100);
  font-family: var(--body-1-emphasized-font-family);
  font-size: var(--body-1-emphasized-font-size);
  font-style: var(--body-1-emphasized-font-style);
  font-weight: var(--body-1-emphasized-font-weight);
  left: 40px;
  letter-spacing: var(--body-1-emphasized-letter-spacing);
  line-height: var(--body-1-emphasized-line-height);
  position: absolute;
  top: 1088px;
  white-space: nowrap;
}

.overlap-7 .photo {
  height: 34px;
  left: 38px;
  object-fit: cover;
  position: absolute;
  top: 1046px;
  width: 34px;
}

.overlap-7 .TESLA {
  height: 17px !important;
  left: 38px !important;
  position: absolute !important;
  top: 43px !important;
  width: 138px !important;
}
</style>