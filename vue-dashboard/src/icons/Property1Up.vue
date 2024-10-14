<template>
  <svg
    :class="['property-1-up', className]"
    fill="none"
    height="12"
    viewBox="0 0 12 12"
    width="12"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      class="path"
      d="M5.16159 0.545454C5.53422 -0.181819 6.46578 -0.181818 6.83841 0.545455L11.8689 10.3636C12.2415 11.0909 11.7757 12 11.0304 12H0.969553C0.224302 12 -0.241479 11.0909 0.131147 10.3636L5.16159 0.545454Z"
      fill="#1FE08F"
    />
  </svg>
</template>

<script lang="ts">
import Vue, { PropType } from 'vue';

export default Vue.extend({
  name: 'Property1Up',
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