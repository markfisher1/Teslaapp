<template>
  <svg
    :class="['icon-arrow-left', className]"
    fill="none"
    height="16"
    viewBox="0 0 16 16"
    width="16"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      class="path"
      d="M10.1831 4.175L6.35811 8L10.1831 11.825L8.99977 13L3.99977 8L8.99977 3L10.1831 4.175Z"
      fill="#B5BEC6"
    />
  </svg>
</template>

<script lang="ts">
import Vue, { PropType } from 'vue';

export default Vue.extend({
  name: 'IconArrowLeft',
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