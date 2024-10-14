<template>
  <svg
    :class="['icon-chevron-right', className]"
    fill="none"
    height="24"
    viewBox="0 0 24 24"
    width="24"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      class="path"
      clip-rule="evenodd"
      d="M10.7134 5.6255L16.3804 11.2945C16.771 11.6848 16.771 12.3188 16.3804 12.7092L10.7134 18.3782C10.3227 18.7692 9.6897 18.7692 9.29903 18.3782C8.90837 17.9875 8.90837 17.3545 9.29903 16.9635L14.259 12.0018L9.29903 7.04017C8.90837 6.6495 8.90837 6.01583 9.29903 5.6255C9.6897 5.2345 10.3227 5.2345 10.7134 5.6255Z"
      fill="black"
      fill-rule="evenodd"
    />
  </svg>
</template>

<script lang="ts">
import Vue, { PropType } from 'vue';

export default Vue.extend({
  name: 'IconChevronRight',
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