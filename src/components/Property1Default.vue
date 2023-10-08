<template>
  <div class="property-1default" :style="property1DefaultStyle">
    <div class="watch-the-demo-parent">
      <b class="watch-the-demo">{{watchTheDemo}}</b>
      <img class="arrow-icon" alt="" src="/arrow.svg" />
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "Property1Default",
    props: {
      watchTheDemo: { type: String },
      property1DefaultPosition: { type: String },
      property1DefaultTop: { type: [Object, Array, String, Number, Boolean] },
      property1DefaultLeft: { type: [Object, Array, String, Number, Boolean] },
      property1DefaultWidth: { type: [Object, Array, String, Number, Boolean] },
      property1DefaultHeight: {
        type: [Object, Array, String, Number, Boolean],
      },
    },
    computed: {
      property1DefaultStyle() {
        return {
          position: this.property1DefaultPosition,
          top: this.property1DefaultTop,
          left: this.property1DefaultLeft,
          width: this.property1DefaultWidth,
          height: this.property1DefaultHeight,
        };
      },
    },
  });
</script>
<style scoped>
  .watch-the-demo {
    position: relative;
    letter-spacing: -0.01em;
    line-height: 36.62px;
  }
  .arrow-icon {
    position: relative;
    width: 60.48px;
    height: 22.09px;
  }
  .watch-the-demo-parent {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-end;
    gap: var(--gap-base);
  }
  .property-1default {
    border-radius: 42.72px;
    border: 2px solid var(--primary);
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-xs) var(--padding-21xl);
    text-align: left;
    font-size: var(--body-desktop-size);
    color: var(--primary);
    font-family: var(--body-desktop2);
  }
</style>
