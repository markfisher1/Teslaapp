<template>
  <svg
    :class="['icon-trending-up-4', className]"
    fill="none"
    height="25"
    viewBox="0 0 24 25"
    width="24"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path class="path" d="M0 0.5H24V24.5H0V0.5Z" :fill="color" />
    <path
      class="path"
      d="M16.85 7.35L18.29 8.79L13.41 13.67L10.12 10.38C9.72998 9.99 9.09998 9.99 8.70998 10.38L2.70998 16.39C2.31998 16.78 2.31998 17.41 2.70998 17.8C3.09998 18.19 3.72998 18.19 4.11998 17.8L9.40998 12.5L12.7 15.79C13.09 16.18 13.72 16.18 14.11 15.79L19.7 10.21L21.14 11.65C21.45 11.96 21.99 11.74 21.99 11.3V7C22 6.72 21.78 6.5 21.5 6.5H17.21C16.76 6.5 16.54 7.04 16.85 7.35Z"
      :fill="fill"
      :fill-opacity="opacity"
    />
  </svg>
</template>

<script lang="ts">
import Vue, { PropType } from 'vue';

export default Vue.extend({
  name: 'IconTrendingUp4',
  props: {
    color: {
      type: String,
      default: '#1B59F8',
    },
    fill: {
      type: String,
      default: '#1B59F8',
    },
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