<template>
  <div class="auto-layout-vertical45">
    <div class="auto-layout-vertical46">
      <img class="line-icon16" alt="" src="/line8.svg" />
      <div class="auto-layout-horizontal72">
        <div class="auto-layout-horizontal73">
          <b class="gr-3">GR-консалтинг, подготовка законопроектов</b>
          <div class="auto-layout-horizontal74">
            <img class="icon-down-up" alt="" src="/icon-down-up.svg" />
          </div>
        </div>
      </div>
    </div>
    <img class="line-icon16" alt="" src="/line8.svg" />
    <div class="auto-layout-vertical47">
      <div class="auto-layout-horizontal72">
        <div class="auto-layout-horizontal72">
          <b class="b26">Арбитражные споры, банкротство</b>
        </div>
      </div>
    </div>
    <img class="line-icon16" alt="" src="/line8.svg" />
    <div class="auto-layout-vertical48">
      <div class="auto-layout-horizontal72">
        <div class="auto-layout-horizontal72">
          <b class="b26">Правовое сопровождение бизнеса</b>
        </div>
      </div>
    </div>
    <img class="line-icon16" alt="" src="/line8.svg" />
    <div class="auto-layout-vertical49">
      <div class="auto-layout-horizontal72">
        <div class="auto-layout-horizontal72">
          <b class="b28">Экспертные заключения</b>
        </div>
      </div>
    </div>
    <div class="auto-layout-vertical50">
      <img class="line-icon16" alt="" src="/line8.svg" />
      <div class="auto-layout-horizontal72">
        <div class="auto-layout-horizontal72">
          <b class="b26">Налоговый консалтинг</b>
        </div>
      </div>
      <img class="line-icon16" alt="" src="/line8.svg" />
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "AutoLayoutVertical",
  });
</script>
<style scoped>
  .line-icon16 {
    position: relative;
    width: 660px;
    height: 2px;
  }
  .gr-3 {
    position: relative;
    letter-spacing: -1.29px;
    line-height: 120%;
    display: inline-block;
    width: 629px;
    flex-shrink: 0;
  }
  .icon-down-up {
    position: relative;
    width: 32px;
    height: 32px;
    overflow: hidden;
    flex-shrink: 0;
  }
  .auto-layout-horizontal74 {
    width: 31px;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    transform: rotate(-90deg);
    transform-origin: 0 0;
  }
  .auto-layout-horizontal73 {
    width: 629px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: var(--gap-90xl);
  }
  .auto-layout-horizontal72 {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
  }
  .auto-layout-vertical46 {
    width: 545px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: center;
    gap: var(--gap-3xl);
    color: var(--primary);
  }
  .b26 {
    position: relative;
    letter-spacing: -1.29px;
    line-height: 120%;
    display: inline-block;
    width: 520px;
    flex-shrink: 0;
  }
  .auto-layout-vertical47 {
    width: 660px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: center;
  }
  .auto-layout-vertical48 {
    width: 545px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: center;
  }
  .b28 {
    position: relative;
    letter-spacing: -1.29px;
    line-height: 120%;
    display: inline-block;
    width: 670px;
    flex-shrink: 0;
  }
  .auto-layout-vertical49 {
    width: 779px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: center;
  }
  .auto-layout-vertical50 {
    width: 660px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: center;
    gap: var(--gap-3xl);
  }
  .auto-layout-vertical45 {
    position: absolute;
    top: 1659px;
    left: 329px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-lg);
    text-align: left;
    font-size: var(--font-size-11xl);
    color: var(--black);
    font-family: var(--body-desktop2);
  }
</style>
