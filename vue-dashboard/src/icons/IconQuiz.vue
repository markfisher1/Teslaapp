<template>
  <svg
    :class="['icon-quiz', className]"
    fill="none"
    height="25"
    viewBox="0 0 24 25"
    width="24"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      class="path"
      d="M0 12.5C0 5.87258 5.37258 0.5 12 0.5C18.6274 0.5 24 5.87258 24 12.5C24 19.1274 18.6274 24.5 12 24.5C5.37258 24.5 0 19.1274 0 12.5Z"
      fill="#1B59F8"
    />
    <path
      class="path"
      d="M11.0475 20.7647V14.7085H7.42968C6.92645 14.7085 6.58643 14.1234 6.83124 13.6406L11.8363 3.15189C12.1491 2.46435 13.1148 2.71304 13.1148 3.48835V9.61774H16.5694C17.0726 9.61774 17.399 10.1883 17.1814 10.671L12.3396 21.0866C12.0131 21.7887 11.0475 21.5401 11.0475 20.7647Z"
      :fill="color"
      :fill-opacity="opacity"
    />
  </svg>
</template>

<script lang="ts">
import Vue, { PropType } from 'vue';

export default Vue.extend({
  name: 'IconQuiz',
  props: {
    color: {
      type: String,
      default: 'black',
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