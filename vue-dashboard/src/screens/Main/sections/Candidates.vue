<template>
  <div class="candidates">
    <div class="overlap-group-wrapper-2">
      <div class="overlap-group-2">
        <div class="elston-gullan">West Coast Managers</div>
        <div class="google-inc">66%</div>
        <div class="frond-end-developer">45</div>
        <div class="jun">74%</div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "Candidates",
});
</script>

<style>
.candidates {
  align-items: flex-start;
  display: inline-flex;
  flex-direction: column;
  left: 3208px;
  position: absolute;
  top: 558px;
}

.candidates .overlap-group-wrapper-2 {
  height: 68px;
  overflow: hidden;
  position: relative;
  width: 1120px;
}

.candidates .overlap-group-2 {
  background-color: #ffffff;
  height: 70px;
  left: -1px;
  position: relative;
  top: -1px;
  width: 1122px;
}

.candidates .elston-gullan {
  color: #686873;
  font-family: "Roboto", Helvetica;
  font-size: 16px;
  font-weight: 500;
  left: 21px;
  letter-spacing: 0.1px;
  line-height: 26px;
  position: absolute;
  top: 21px;
  white-space: nowrap;
}

.candidates .google-inc {
  color: #686873;
  font-family: "Roboto", Helvetica;
  font-size: 16px;
  font-weight: 400;
  left: 902px;
  letter-spacing: 0.1px;
  line-height: 26px;
  position: absolute;
  top: 21px;
  white-space: nowrap;
}

.candidates .frond-end-developer {
  color: #686873;
  font-family: "Roboto", Helvetica;
  font-size: 16px;
  font-weight: 400;
  left: 364px;
  letter-spacing: 0.1px;
  line-height: 26px;
  position: absolute;
  top: 21px;
  white-space: nowrap;
}

.candidates .jun {
  color: #686873;
  font-family: "Roboto", Helvetica;
  font-size: 16px;
  font-weight: 400;
  left: 571px;
  letter-spacing: 0.1px;
  line-height: 26px;
  position: absolute;
  top: 21px;
  white-space: nowrap;
}
</style>