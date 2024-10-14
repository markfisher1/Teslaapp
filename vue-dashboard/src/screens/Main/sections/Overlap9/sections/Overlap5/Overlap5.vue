<template>
  <div class="overlap-5">
    <div class="text-wrapper-2">Month</div>
    <Icons class="icons-instance" />
  </div>
</template>

<script lang="ts">
import Vue, { PropType } from 'vue';
import Icons from "../../../../../../icons/Icons.vue";

export default Vue.extend({
  name: "Overlap5",
  components: {
    Icons,
  },
});
</script>

<style>
.overlap-5 {
  height: 16px;
  left: 480px;
  position: absolute;
  top: 18px;
  width: 54px;
}

.overlap-5 .text-wrapper-2 {
  color: var(--primarypressed);
  font-family: var(--body-2-emphasized-font-family);
  font-size: var(--body-2-emphasized-font-size);
  font-style: var(--body-2-emphasized-font-style);
  font-weight: var(--body-2-emphasized-font-weight);
  height: 15px;
  left: 0;
  letter-spacing: var(--body-2-emphasized-letter-spacing);
  line-height: var(--body-2-emphasized-line-height);
  position: absolute;
  top: 0;
  width: 46px;
}

.overlap-5 .icons-instance {
  height: 16px !important;
  left: 38px !important;
  position: absolute !important;
  top: 0 !important;
  width: 16px !important;
}
</style>