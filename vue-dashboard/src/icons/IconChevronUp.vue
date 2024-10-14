<template>
  <svg
    :class="['icon-chevron-up', className]"
    fill="none"
    height="25"
    viewBox="0 0 24 25"
    width="24"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      class="path"
      d="M11.295 15.5L6.70498 10.91C6.31498 10.52 6.31498 9.89001 6.70498 9.50001C7.09498 9.11001 7.72498 9.11001 8.11498 9.50001L12.005 13.38L15.885 9.50001C16.275 9.11001 16.905 9.11001 17.295 9.50001C17.685 9.89001 17.685 10.52 17.295 10.91L12.705 15.5C12.325 15.89 11.685 15.89 11.295 15.5Z"
      fill="black"
      fill-opacity="0.2"
    />
  </svg>
</template>

<script lang="ts">
import Vue, { PropType } from 'vue';

export default Vue.extend({
  name: 'IconChevronUp',
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