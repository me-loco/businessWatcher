<template>
  <div class="frame7">
    <input class="group3" placeholder="Ваш e-mail" type="text" />
    <input class="frame8" type="text" />
    <div class="auto-layout-horizontal39">
      <input class="rectangle7" type="checkbox" />
      <div class="div88">
        Согласен с условиями обработки персональных данных
      </div>
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "Frame6",
  });
</script>
<style scoped>
  .group3 {
    border: none;
    font-family: var(--body-desktop2);
    font-size: var(--body-desktop-size);
    background-color: transparent;
    position: absolute;
    top: 0px;
    left: 1px;
    width: 379px;
    height: 39px;
  }
  .frame8 {
    border: none;
    background-color: transparent;
    position: absolute;
    top: 61px;
    left: 1px;
    width: 379px;
    height: 39px;
  }
  .rectangle7 {
    position: relative;
    border-radius: 5.46px;
    background-color: var(--white);
    border: 1.1px solid var(--grey);
    box-sizing: border-box;
    width: 27px;
    height: 27px;
  }
  .div88 {
    position: relative;
    letter-spacing: -0.01em;
    line-height: 143.5%;
    display: inline-block;
    width: 332px;
    flex-shrink: 0;
  }
  .auto-layout-horizontal39 {
    position: absolute;
    top: 122px;
    left: 0px;
    width: 380px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: 15.29px;
  }
  .frame7 {
    position: relative;
    width: 380px;
    height: 160px;
    text-align: left;
    font-size: var(--font-size-smi);
    color: var(--grey);
    font-family: var(--font-inter);
  }
</style>
