<template>
  <svg
    :class="['property-1-down', className]"
    fill="none"
    height="12"
    viewBox="0 0 12 12"
    width="12"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      class="path"
      d="M5.16159 11.4545C5.53422 12.1818 6.46578 12.1818 6.83841 11.4545L11.8689 1.63636C12.2415 0.90909 11.7757 0 11.0304 0H0.969553C0.224302 0 -0.241479 0.90909 0.131147 1.63636L5.16159 11.4545Z"
      fill="#FF3E13"
    />
  </svg>
</template>

<script lang="ts">
import Vue, { PropType } from 'vue';

export default Vue.extend({
  name: "Property1Down",
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