<template>
  <svg
    :class="['icon-trending-up-2', className]"
    fill="none"
    height="24"
    viewBox="0 0 24 24"
    width="24"
    xmlns="http://www.w3.org/2000/svg"
  >
    <g class="g" clip-path="url(#clip0_5558_5835)">
      <path
        class="path"
        d="M16.85 6.85L18.29 8.29L13.41 13.17L10.12 9.88C9.72998 9.49 9.09998 9.49 8.70999 9.88L2.70999 15.89C2.31999 16.28 2.31999 16.91 2.70999 17.3C3.09999 17.69 3.72999 17.69 4.11999 17.3L9.40998 12L12.7 15.29C13.09 15.68 13.72 15.68 14.11 15.29L19.7 9.71L21.14 11.15C21.45 11.46 21.99 11.24 21.99 10.8V6.5C22 6.22 21.78 6 21.5 6H17.21C16.76 6 16.54 6.54 16.85 6.85Z"
        fill="black"
      />
    </g>
    <defs class="defs">
      <clipPath class="clip-path" id="clip0_5558_5835">
        <rect class="rect" fill="white" height="24" width="24" />
      </clipPath>
    </defs>
  </svg>
</template>

<script lang="ts">
import Vue, { PropType } from 'vue';

export default Vue.extend({
  name: "IconTrendingUp2",
  props: {
    className: {
      type: String,
      default: "",
    },
  },
});
</script>

<style>
</style>