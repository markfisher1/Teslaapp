<template>
  <svg
    :class="['icon-quiz-3', className]"
    fill="none"
    height="24"
    viewBox="0 0 24 24"
    width="24"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      class="path"
      d="M11.0475 20.2647V14.2085H7.42968C6.92645 14.2085 6.58643 13.6234 6.83124 13.1406L11.8363 2.65189C12.1491 1.96435 13.1148 2.21304 13.1148 2.98835V9.11774H16.5694C17.0726 9.11774 17.399 9.68826 17.1814 10.171L12.3396 20.5866C12.0131 21.2887 11.0475 21.0401 11.0475 20.2647Z"
      fill="black"
      fill-opacity="0.7"
    />
  </svg>
</template>

<script lang="ts">
import Vue, { PropType } from 'vue';

export default Vue.extend({
  name: 'IconQuiz3',
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