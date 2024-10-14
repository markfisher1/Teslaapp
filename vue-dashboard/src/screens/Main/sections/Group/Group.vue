<template>
  <div class="group">
    <div class="overlap-10">
      <IconDownload class="icon-download" color="#4D4D4D" />
      <div class="text">Download</div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import IconDownload from "../../../../icons/IconDownload.vue";

export default Vue.extend({
  name: "Group",
  components: {
    IconDownload,
  },
});
</script>

<style>
.group {
  height: 22px;
  left: 1229px;
  position: absolute;
  top: 43px;
  width: 159px;
}

.group .overlap-10 {
  height: 22px;
  position: relative;
  width: 157px;
}

.group .icon-download {
  height: 22px !important;
  left: 64px !important;
  position: absolute !important;
  top: 0 !important;
  width: 22px !important;
}

.group .text {
  color: #4d4d4d;
  font-family: var(--body-1-emphasized-font-family);
  font-size: var(--body-1-emphasized-font-size);
  font-style: var(--body-1-emphasized-font-style);
  font-weight: var(--body-1-emphasized-font-weight);
  height: 18px;
  left: 0;
  letter-spacing: var(--body-1-emphasized-letter-spacing);
  line-height: var(--body-1-emphasized-line-height);
  position: absolute;
  text-align: right;
  top: 1px;
  width: 157px;
}
</style>