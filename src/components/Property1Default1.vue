<template>
  <div class="property-1default1" :style="property1Default1Style">
    <div class="watch-the-demo-group">
      <b class="watch-the-demo1" :style="watchTheDemoStyle">{{watchTheDemo}}</b>
      <img class="arrow-icon1" alt="" :src="arrow" :style="arrowIconStyle" />
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "Property1Default1",
    props: {
      watchTheDemo: { type: String },
      arrow: { type: String },
      property1DefaultCursor: { type: String },
      property1DefaultPosition: { type: String },
      property1DefaultTop: { type: [Object, Array, String, Number, Boolean] },
      property1DefaultLeft: { type: [Object, Array, String, Number, Boolean] },
      property1DefaultWidth: { type: [Object, Array, String, Number, Boolean] },
      property1DefaultHeight: {
        type: [Object, Array, String, Number, Boolean],
      },
      watchTheDemoFontSize: { type: String },
      watchTheDemoDisplay: { type: String },
      arrowIconHeight: { type: [Object, Array, String, Number, Boolean] },
    },
    computed: {
      property1Default1Style() {
        return {
          cursor: this.property1DefaultCursor,
          position: this.property1DefaultPosition,
          top: this.property1DefaultTop,
          left: this.property1DefaultLeft,
          width: this.property1DefaultWidth,
          height: this.property1DefaultHeight,
        };
      },
      watchTheDemoStyle() {
        return {
          fontSize: this.watchTheDemoFontSize,
          display: this.watchTheDemoDisplay,
        };
      },
      arrowIconStyle() {
        return {
          height: this.arrowIconHeight,
        };
      },
    },
  });
</script>
<style scoped>
  .watch-the-demo1 {
    position: relative;
    letter-spacing: -0.01em;
    line-height: 36.62px;
  }
  .arrow-icon1 {
    position: relative;
    width: 60.48px;
    height: 22.09px;
  }
  .watch-the-demo-group {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-end;
    gap: var(--gap-base);
  }
  .property-1default1 {
    border-radius: 42.72px;
    background-color: var(--primary);
    box-shadow: var(--bttn);
    border: 2px solid var(--primary);
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-xs) var(--padding-21xl);
    text-align: left;
    font-size: var(--body-desktop-size);
    color: var(--white);
    font-family: var(--body-desktop2);
  }
</style>
