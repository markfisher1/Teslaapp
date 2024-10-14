<template>
  <svg
    :class="['icon-download', className]"
    fill="none"
    height="22"
    viewBox="0 0 22 22"
    width="22"
    xmlns="http://www.w3.org/2000/svg"
  >
    <g class="g" clip-path="url(#clip0_5558_6315)">
      <path
        class="path"
        :d="pathData"
        :fill="color"
      />
    </g>
    <defs class="defs">
      <clipPath class="clip-path" id="clip0_5558_6315">
        <rect class="rect" fill="white" height="22" width="22" />
      </clipPath>
    </defs>
  </svg>
</template>

<script lang="ts">
import Vue, { PropType } from 'vue';

export default Vue.extend({
  name: 'IconDownload',
  props: {
    color: {
      type: String,
      default: 'black',
    },
    className: {
      type: String,
      default: '',
    },
  },
  computed: {
    pathData() {
      return "M15.2075 8.25H13.75V3.66667C13.75 3.1625 13.3375 2.75 12.8333 2.75H9.16665C8.66248 2.75 8.24998 3.1625 8.24998 3.66667V8.25H6.79248C5.97665 8.25 5.56415 9.24 6.14165 9.8175L10.3491 14.025C10.7066 14.3825 11.2841 14.3825 11.6416 14.025L15.8491 9.8175C16.4266 9.24 16.0233 8.25 15.2075 8.25ZM4.58331 17.4167C4.58331 17.9208 4.99581 18.3333 5.49998 18.3333H16.5C17.0041 18.3333 17.4166 17.9208 17.4166 17.4167C17.4166 16.9125 17.0041 16.5 16.5 16.5H5.49998C4.99581 16.5 4.58331 16.9125 4.58331 17.4167Z";
    },
  },
});
</script>

<style>
.icon-download {
  /* Add any specific styles for the icon here if needed */
}
</style>