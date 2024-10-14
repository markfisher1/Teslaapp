<template>
  <div :class="['date-dropdown', className]">
    <p :class="['show-this-year', showThisYearClassName]">
      <span :class="['text-wrapper', spanClassName]">{{ text }}</span>
      <span :class="['span', spanClassNameOverride]">{{ text1 }}</span>
    </p>
    <component :is="icon" class="icon-arrow-full-down" />
  </div>
</template>

<script lang="ts">
import Vue, { PropType } from "vue";
import IconArrowFullDown4 from "../icons/IconArrowFullDown4.vue";

export default Vue.extend({
  name: "DateDropdown",
  components: {
    IconArrowFullDown4,
  },
  props: {
    className: {
      type: String,
      default: "",
    },
    showThisYearClassName: {
      type: String,
      default: "",
    },
    spanClassName: {
      type: String,
      default: "",
    },
    text: {
      type: String,
      default: "Show:",
    },
    spanClassNameOverride: {
      type: String,
      default: "",
    },
    text1: {
      type: String,
      default: " Last 7 Days",
    },
    icon: {
      type: Object as PropType<JSX.Element>,
      default: () => <IconArrowFullDown4 className="icon-arrow-full-down" />,
    },
  },
});
</script>

<style>
.date-dropdown {
  align-items: center;
  display: inline-flex;
  position: relative;
}

.date-dropdown .show-this-year {
  color: transparent;
  font-family: var(--label-medium-font-family);
  font-size: var(--label-medium-font-size);
  font-style: var(--label-medium-font-style);
  font-weight: var(--label-medium-font-weight);
  letter-spacing: var(--label-medium-letter-spacing);
  line-height: var(--label-medium-line-height);
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.date-dropdown .text-wrapper {
  color: #92929d;
  font-family: var(--label-medium-font-family);
  font-size: var(--label-medium-font-size);
  font-style: var(--label-medium-font-style);
  font-weight: var(--label-medium-font-weight);
  letter-spacing: var(--label-medium-letter-spacing);
  line-height: var(--label-medium-line-height);
}

.date-dropdown .span {
  color: #686873;
  font-family: var(--label-medium-font-family);
  font-size: var(--label-medium-font-size);
  font-style: var(--label-medium-font-style);
  font-weight: var(--label-medium-font-weight);
  letter-spacing: var(--label-medium-letter-spacing);
  line-height: var(--label-medium-line-height);
}

.date-dropdown .icon-arrow-full-down {
  height: 24px !important;
  position: relative !important;
  width: 24px !important;
}
</style>