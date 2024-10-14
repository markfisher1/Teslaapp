<template>
  <svg
    :class="['icon-chevron-up-8', className]"
    fill="none"
    height="24"
    viewBox="0 0 24 24"
    width="24"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      class="path"
      d="M11.295 9L6.705 13.59C6.315 13.98 6.315 14.61 6.705 15C7.095 15.39 7.725 15.39 8.115 15L12.005 11.12L15.885 15C16.275 15.39 16.905 15.39 17.295 15C17.685 14.61 17.685 13.98 17.295 13.59L12.705 9C12.325 8.61 11.685 8.61 11.295 9Z"
      fill="black"
      :fill-opacity="opacity"
    />
  </svg>
</template>

<script lang="ts">
import Vue, { PropType } from 'vue';

export default Vue.extend({
  name: 'IconChevronUp8',
  props: {
    opacity: {
      type: String,
      default: 'unset',
    },
    className: {
      type: String,
      default: '',
    },
  },
});
</script>

<style>
</style>