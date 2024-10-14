<template>
  <svg
    :class="['icon-arrow-full-down-4', className]"
    fill="none"
    height="33"
    viewBox="0 0 42 33"
    width="42"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      class="path"
      d="M15.0378 15.7021L19.4811 19.2274C20.1502 19.7582 21.231 19.7582 21.9001 19.2274L26.3434 15.7021C27.4242 14.8446 26.6522 13.3746 25.1253 13.3746H16.2387C14.7118 13.3746 13.957 14.8446 15.0378 15.7021Z"
      fill="black"
    />
  </svg>
</template>

<script lang="ts">
import Vue, { PropType } from 'vue';

export default Vue.extend({
  name: 'IconArrowFullDown4',
  props: {
    className: {
      type: String,
      default: '',
    },
  },
});
</script>

<style>
</style>