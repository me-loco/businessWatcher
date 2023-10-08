<template>
  <div class="frame16">
    <div class="auto-layout-horizontal53">
      <Frame4 /><Frame4 propMarginLeft="-765px" />
    </div>
    <div class="frame17">
      <div class="auto-layout-horizontal54">
        <b class="b20">
          <p class="p13">Закрыли накопленный убыток</p>
          <p class="p13">в 5,5 млн рублей</p>
        </b>
      </div>
      <div class="auto-layout-vertical38">
        <div class="auto-layout-horizontal55">
          <div class="auto-layout-horizontal56">
            <b class="b21">Строительство</b>
          </div>
          <div class="auto-layout-horizontal57">
            <b class="b21">Торговля</b>
          </div>
        </div>
        <div class="div103">
          <p class="p13">
            Научный сотрудник Центра судебного права, старший преподаватель
            кафедры подготовки юристов правоохранительных органов, уголовного
            судопроизводства, правозащитной деятельности Института
            законодательства и сравнительного правоведения при Правительстве
            Российской Федерации, кандидат юридических наук.
          </p>
          <p class="p13">
            Научный сотрудник Центра судебного права, старший преподаватель
            кафедры подготовки юристов правоохранительных органов, уголовного
            судопроизводства, правозащитной деятельности Института
          </p>
          <p class="p17">Читать далее</p>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";
  import Frame4 from "./Frame4.vue";

  export default defineComponent({
    name: "Frame3",
    components: { Frame4 },
  });
</script>
<style scoped>
  .auto-layout-horizontal53 {
    position: absolute;
    top: 45px;
    left: calc(50% - 820px);
    width: 1640px;
    height: 530px;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
  }
  .p13 {
    margin: 0;
  }
  .b20 {
    position: relative;
    letter-spacing: -0.25px;
    line-height: 130%;
  }
  .auto-layout-horizontal54 {
    position: absolute;
    top: 60px;
    left: 0px;
    border-radius: var(--br-base);
    width: 1360px;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    padding: var(--padding-3xs) var(--padding-41xl);
    box-sizing: border-box;
  }
  .b21 {
    position: relative;
    letter-spacing: -0.01em;
    line-height: 24.25px;
  }
  .auto-layout-horizontal56 {
    border-radius: 28.29px;
    border: 1px solid var(--grey);
    box-sizing: border-box;
    width: 204px;
    height: 47px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    padding: 11.112314224243164px 0px;
  }
  .auto-layout-horizontal57 {
    border-radius: 28.29px;
    border: 1px solid var(--grey);
    box-sizing: border-box;
    width: 148px;
    height: 47px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    padding: 11.112314224243164px 0px;
  }
  .auto-layout-horizontal55 {
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-5xs);
  }
  .p17 {
    margin: 0;
    color: var(--primary);
  }
  .div103 {
    position: relative;
    font-size: 21.81px;
    letter-spacing: -0.01em;
    line-height: 38.17px;
    font-family: var(--font-open-sans);
    display: inline-block;
    width: 1240px;
    color: var(--black);
  }
  .auto-layout-vertical38 {
    position: absolute;
    top: 214px;
    left: 0px;
    border-radius: var(--br-base);
    width: 1360px;
    height: 346px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px var(--padding-41xl);
    box-sizing: border-box;
    gap: var(--gap-13xl);
    font-size: var(--font-size-lg);
    color: var(--grey);
    font-family: var(--body-desktop2);
  }
  .frame17 {
    position: absolute;
    top: 0px;
    left: 140px;
    border-radius: var(--br-xs);
    background-color: var(--white);
    box-shadow: 697px 0px 195px rgba(0, 0, 0, 0),
      446px 4px 178px rgba(59, 97, 186, 0.01),
      236px 4px 150px rgba(59, 97, 186, 0.04),
      111px 0px 111px rgba(59, 97, 186, 0.07),
      -656px 0px 184px rgba(59, 97, 186, 0),
      -420px 0px 168px rgba(59, 97, 186, 0.01),
      -236px 0px 142px rgba(59, 97, 186, 0.04),
      -105px 0px 105px rgba(59, 97, 186, 0.07);
    width: 1360px;
    height: 620px;
    font-size: 39.26px;
  }
  .frame16 {
    position: absolute;
    top: 4822px;
    left: 140px;
    width: 1640px;
    height: 620px;
    text-align: left;
    font-size: 34.71px;
    color: var(--black);
    font-family: var(--font-open-sans);
  }
</style>
