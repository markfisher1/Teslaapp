<template>
  <svg
    :class="['icons', className]"
    fill="none"
    height="16"
    viewBox="0 0 16 16"
    width="16"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      class="path"
      d="M4.175 5.81689L8 9.64189L11.825 5.81689L13 7.00023L8 12.0002L3 7.00023L4.175 5.81689Z"
      fill="#848A95"
    />
  </svg>
</template>

<script lang="ts">
import Vue, { PropType } from 'vue';

export default Vue.extend({
  name: 'Icons',
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