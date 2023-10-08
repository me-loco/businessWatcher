<template>
  <img
    class="icon-chevron-left-28"
    alt=""
    :src="iconChevronLeft28IconChev"
    :style="iconChevronLeft28Style"
  />
</template>
<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "IconChevronLeft28",
    props: {
      iconChevronLeft28IconChev: { type: String },
      iconChevronLeft28Width: {
        type: [Object, Array, String, Number, Boolean],
      },
      iconChevronLeft28Height: {
        type: [Object, Array, String, Number, Boolean],
      },
      iconChevronLeft28Position: { type: String },
      iconChevronLeft28FlexShrink: { type: String },
    },
    computed: {
      iconChevronLeft28Style() {
        return {
          width: this.iconChevronLeft28Width,
          height: this.iconChevronLeft28Height,
          position: this.iconChevronLeft28Position,
          flexShrink: this.iconChevronLeft28FlexShrink,
        };
      },
    },
  });
</script>
<style scoped>
  .icon-chevron-left-28 {
    width: 56px;
    height: 56px;
    overflow: hidden;
  }
</style>
