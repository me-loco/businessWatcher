<template>
  <div class="frame18">
    <div class="line1" />
    <div class="auto-layout-vertical39">
      <b class="b23" :style="bStyle">{{prop}}</b>
      <div class="auto-layout-vertical40">
        <div class="auto-layout-horizontal58">
          <img class="icon-checkmark" alt="" :src="iconCheckmark" />
          <div class="div104">{{prop1}}</div>
        </div>
        <div class="auto-layout-horizontal59">
          <img class="icon-checkmark" alt="" :src="iconCheckmark1" />
          <div class="div104">{{prop2}}</div>
        </div>
        <div class="auto-layout-horizontal58">
          <img class="icon-checkmark" alt="" :src="iconCheckmark2" />
          <div class="div104">{{prop3}}</div>
        </div>
        <div class="auto-layout-horizontal59">
          <img class="icon-checkmark" alt="" :src="iconCheckmark3" />
          <div class="div104">{{prop4}}</div>
        </div>
        <div class="auto-layout-horizontal59">
          <img class="icon-checkmark" alt="" :src="iconCheckmark4" />
          <div class="div104">{{prop5}}</div>
        </div>
        <div class="auto-layout-horizontal59">
          <img class="icon-checkmark" alt="" :src="iconCheckmark5" />
          <div class="div104" :style="divStyle">{{prop6}}</div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "Frame2",
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
      prop5: { type: String },
      iconCheckmark5: { type: String },
      prop6: { type: String },
      propWidth: { type: [Object, Array, String, Number, Boolean] },
      propWidth1: { type: [Object, Array, String, Number, Boolean] },
    },
    computed: {
      bStyle() {
        return {
          width: this.propWidth,
        };
      },
      divStyle() {
        return {
          width: this.propWidth1,
        };
      },
    },
  });
</script>
<style scoped>
  .line1 {
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
  .b23 {
    position: relative;
    letter-spacing: -0.01em;
    line-height: 36.44px;
    display: inline-block;
    width: 309px;
  }
  .icon-checkmark {
    position: relative;
    width: 28px;
    height: 28px;
    overflow: hidden;
    flex-shrink: 0;
  }
  .div104 {
    position: relative;
    letter-spacing: -0.01em;
    line-height: 30px;
    display: inline-block;
    width: 404px;
    flex-shrink: 0;
  }
  .auto-layout-horizontal58 {
    width: 285px;
    height: 28px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: 7.73px;
  }
  .auto-layout-horizontal59 {
    width: 285px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: 7.73px;
  }
  .auto-layout-vertical40 {
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
  .auto-layout-vertical39 {
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
  .frame18 {
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
