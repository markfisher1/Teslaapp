<template>
  <img
    :class="['sidebar-logo', className]"
    alt="Sidebar logo"
    src="/img/sidebar-logo.svg"
  />
</template>

<script lang="ts">
import Vue, { PropType } from "vue";

export default Vue.extend({
  name: "SidebarLogo",
  props: {
    className: {
      type: String,
      default: "",
    },
  },
});
</script>

<style>
.sidebar-logo {
  height: 70px;
  left: 0;
  position: absolute;
  top: 0;
  width: 250px;
}
</style>