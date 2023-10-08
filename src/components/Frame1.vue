<template>
  <div class="frame19">
    <div class="line2" />
    <div class="auto-layout-vertical41">
      <b class="b24" :style="b1Style">{{prop}}</b>
      <div class="auto-layout-vertical42">
        <div class="auto-layout-horizontal64">
          <img class="icon-checkmark6" alt="" :src="iconCheckmark" />
          <div class="div110">{{prop1}}</div>
        </div>
        <div class="auto-layout-horizontal65">
          <img class="icon-checkmark6" alt="" :src="iconCheckmark1" />
          <div class="div110">{{prop2}}</div>
        </div>
        <div class="auto-layout-horizontal64">
          <img class="icon-checkmark6" alt="" :src="iconCheckmark2" />
          <div class="div110">{{prop3}}</div>
        </div>
        <div class="auto-layout-horizontal65">
          <img class="icon-checkmark6" alt="" :src="iconCheckmark3" />
          <div class="div110">{{prop4}}</div>
        </div>
        <div class="auto-layout-horizontal65">
          <img class="icon-checkmark6" alt="" :src="iconCheckmark4" />
          <div class="div110" :style="gRStyle">{{gR}}</div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "Frame1",
    props: {
      prop: { type: String },
      iconCheckmark: { type: String },
      prop1: { type: String },
      iconCheckmark1: { type: String },
      prop2: { type: String },
      iconCheckmark2: { type: String },
      prop3: { type: String },
      iconCheckmark3: { type: String },
      prop4: { type: String },
      iconCheckmark4: { type: String },
      gR: { type: String },
      propWidth: { type: [Object, Array, String, Number, Boolean] },
      propWidth1: { type: [Object, Array, String, Number, Boolean] },
    },
    computed: {
      b1Style() {
        return {
          width: this.propWidth,
        };
      },
      gRStyle() {
        return {
          width: this.propWidth1,
        };
      },
    },
  });
</script>
<style scoped>
  .line2 {
    position: absolute;
    height: 1.18%;
    width: calc(100% + 6px);
    top: 0.59%;
    right: -3px;
    bottom: 98.22%;
    left: -3px;
    border-top: 6px solid var(--primary);
    box-sizing: border-box;
  }
  .b24 {
    position: relative;
    letter-spacing: -0.01em;
    line-height: 36.44px;
    display: inline-block;
    width: 440px;
  }
  .icon-checkmark6 {
    position: relative;
    width: 28px;
    height: 28px;
    overflow: hidden;
    flex-shrink: 0;
  }
  .div110 {
    position: relative;
    letter-spacing: -0.01em;
    line-height: 30px;
    display: inline-block;
    width: 404px;
    flex-shrink: 0;
  }
  .auto-layout-horizontal64 {
    width: 285px;
    height: 28px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: 7.73px;
  }
  .auto-layout-horizontal65 {
    width: 285px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: 7.73px;
  }
  .auto-layout-vertical42 {
    width: 440px;
    height: 354px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-5xl);
    font-size: var(--body-desktop2-size);
    color: var(--grey3);
  }
  .auto-layout-vertical41 {
    position: absolute;
    top: 45px;
    left: 480px;
    width: 440px;
    height: 423px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: 38.65px;
    transform: rotate(180deg);
    transform-origin: 0 0;
  }
  .frame19 {
    position: relative;
    border-radius: 6.63px;
    background-color: var(--white);
    box-shadow: 0px 4.417364597320557px 13.25px rgba(12, 68, 204, 0.1);
    width: 520px;
    height: 507px;
    transform: rotate(180deg);
    transform-origin: 0 0;
    text-align: left;
    font-size: var(--font-size-5xl-3);
    color: var(--black1);
    font-family: var(--body-desktop2);
  }
</style>
