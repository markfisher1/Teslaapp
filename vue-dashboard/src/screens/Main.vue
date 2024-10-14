<template>
  <div class="main">
    <div class="div-3">
      <Candidates />
      <div class="divider" />
      <Overlap6 />
      <div class="navigation-header">
        <div class="title-4">Reports</div>
      </div>
      <Group />
      <Overlap7 />
      <Overlap8 />
      <GroupWrapper />
      <Overlap9 />
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import Candidates from "./Main/sections/Candidates.vue";
import Group from "./Main/sections/Group/Group.vue";
import GroupWrapper from "./Main/sections/GroupWrapper/GroupWrapper.vue";
import Overlap6 from "./Main/sections/Overlap6.vue";
import Overlap7 from "./Main/sections/Overlap7.vue";
import Overlap8 from "./Main/sections/Overlap8.vue";
import Overlap9 from "./Main/sections/Overlap9.vue";

export default Vue.extend({
  name: "Main",
  components: {
    Candidates,
    Group,
    GroupWrapper,
    Overlap6,
    Overlap7,
    Overlap8,
    Overlap9,
  },
});
</script>

<style>
.main {
  background-color: #f9f9f9;
  display: flex;
  flex-direction: row;
  justify-content: center;
  width: 100%;
}

.main .div-3 {
  background-color: #f9f9f9;
  height: 1162px;
  overflow: hidden;
  position: relative;
  width: 1440px;
}

.main .divider {
  background-color: var(--background-dividers);
  height: 1px;
  left: 280px;
  position: absolute;
  top: 103px;
  width: 1110px;
}

.main .navigation-header {
  align-items: center;
  display: inline-flex;
  gap: 16px;
  left: 280px;
  position: absolute;
  top: 37px;
}

.main .title-4 {
  color: var(--base-shade-100);
  font-family: var(--headline-font-family);
  font-size: var(--headline-font-size);
  font-style: var(--headline-font-style);
  font-weight: var(--headline-font-weight);
  letter-spacing: var(--headline-letter-spacing);
  line-height: var(--headline-line-height);
  margin-top: -1px;
  position: relative;
  width: fit-content;
}
</style>