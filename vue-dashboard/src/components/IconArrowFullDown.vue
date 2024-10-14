<template>
  <IconArrowFullDown4 class="icon-arrow-full-down-4" />
</template>

<script lang="ts">
import Vue, { PropType } from "vue";
import IconArrowFullDown4 from "../icons/IconArrowFullDown4.vue";

export default Vue.extend({
  name: "IconArrowFullDown",
  components: {
    IconArrowFullDown4,
  },
});
</script>

<style>
.icon-arrow-full-down-4 {
  height: 24px !important;
  left: 0 !important;
  position: absolute !important;
  top: 0 !important;
  width: 24px !important;
}
</style>