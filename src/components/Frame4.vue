<template>
  <div class="frame15" :style="frameStyle">
    <b class="b17">
      <p class="p8">Закрыли накопленный убыток</p>
      <p class="p8">в 5,5 млн рублей</p>
    </b>
    <div class="auto-layout-vertical37">
      <div class="auto-layout-horizontal50">
        <div class="auto-layout-horizontal51">
          <b class="b18">Строительство</b>
        </div>
        <div class="auto-layout-horizontal52">
          <b class="b18">Торговля</b>
        </div>
      </div>
      <div class="div102">
        <p class="p8">
          Научный сотрудник Центра судебного права, старший преподаватель
          кафедры подготовки юристов правоохранительных органов, уголовного
          судопроизводства, правозащитной деятельности Института
          законодательства и сравнительного правоведения при Правительстве
          Российской Федерации, кандидат юридических наук.
        </p>
        <p class="p8">
          Научный сотрудник Центра судебного права, старший преподаватель
          кафедры подготовки юристов правоохранительных органов, уголовного
          судопроизводства, правозащитной деятельности Института
        </p>
        <p class="p12">Читать далее</p>
      </div>
    </div>
  </div>
</template>
<script>
  import { defineComponent } from "vue";

  export default defineComponent({
    name: "Frame4",
    props: {
      propMarginLeft: { type: [Object, Array, String, Number, Boolean] },
    },
    computed: {
      frameStyle() {
        return {
          marginLeft: this.propMarginLeft,
        };
      },
    },
  });
</script>
<style scoped>
  .p8 {
    margin: 0;
  }
  .b17 {
    position: absolute;
    height: 21.89%;
    width: 80.2%;
    top: 9.06%;
    left: 6.66%;
    letter-spacing: -0.22px;
    line-height: 130%;
    display: inline-block;
  }
  .b18 {
    position: relative;
    letter-spacing: -0.01em;
    line-height: 21.44px;
  }
  .auto-layout-horizontal51 {
    border-radius: 25.01px;
    border: 0.9px solid var(--grey);
    box-sizing: border-box;
    width: 180px;
    height: 42px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    padding: 9.824912071228027px 0px;
  }
  .auto-layout-horizontal52 {
    border-radius: 25.01px;
    border: 0.9px solid var(--grey);
    box-sizing: border-box;
    width: 131px;
    height: 42px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    padding: 9.824912071228027px 0px;
  }
  .auto-layout-horizontal50 {
    width: 318px;
    height: 42px;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    gap: 7.07px;
  }
  .p12 {
    margin: 0;
    color: var(--primary);
  }
  .div102 {
    position: relative;
    font-size: 19.29px;
    letter-spacing: -0.01em;
    line-height: 33.75px;
    font-family: var(--font-open-sans);
    display: inline-block;
    width: 1100px;
    color: var(--black);
  }
  .auto-layout-vertical37 {
    position: absolute;
    top: 175px;
    left: 0px;
    border-radius: var(--br-3xs);
    width: 1186px;
    height: 306px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    padding: 0px 0px 0px 80.998291015625px;
    box-sizing: border-box;
    gap: 28.29px;
    font-size: 15.91px;
    color: var(--grey);
    font-family: var(--body-desktop2);
  }
  .frame15 {
    position: relative;
    border-radius: var(--br-3xs);
    background-color: var(--white);
    box-shadow: 0px 8.919146537780762px 26.76px rgba(12, 68, 204, 0.1);
    width: 1202px;
    height: 530px;
    text-align: left;
    font-size: 34.71px;
    color: var(--black);
    font-family: var(--font-open-sans);
  }
</style>
