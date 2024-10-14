<template>
  <svg
    :class="['icon-talk-1', className]"
    fill="none"
    height="25"
    viewBox="0 0 24 25"
    width="24"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      class="path"
      d="M20 3.5H6C4.9 3.5 4 4.4 4 5.5V13.5C4 15.71 5.79 17.5 8 17.5H14C16.21 17.5 18 15.71 18 13.5V10.5H20C21.1 10.5 22 9.6 22 8.5V5.5C22 4.4 21.1 3.5 20 3.5ZM20 8.5H18V5.5H20V8.5ZM3 21.5H19C19.55 21.5 20 21.05 20 20.5C20 19.95 19.55 19.5 19 19.5H3C2.45 19.5 2 19.95 2 20.5C2 21.05 2.45 21.5 3 21.5Z"
      :fill="color"
    />
  </svg>
</template>

<script lang="ts">
import Vue, { PropType } from 'vue';

export default Vue.extend({
  name: "IconTalk1",
  props: {
    color: {
      type: String,
      default: "black",
    },
    className: {
      type: String,
      default: "",
    },
  },
});
</script>

<style>
</style>