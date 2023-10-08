<template>
  <div class="auto-layout-horizontal69">
    <Frame2
      prop="Компании сегмента МСП"
      iconCheckmark="/icon-checkmark.svg"
      prop1="Юридический консалтинг"
      iconCheckmark1="/icon-checkmark.svg"
      prop2="Защита интеллектуальной собственности"
      iconCheckmark2="/icon-checkmark1.svg"
      prop3="Проверка контрагентов"
      iconCheckmark3="/icon-checkmark1.svg"
      prop4="Антикоррупционный комплаенс"
      iconCheckmark4="/icon-checkmark1.svg"
      prop5="Безопасность бизнеса, защита бизнеса"
      iconCheckmark5="/icon-checkmark1.svg"
      prop6="Автоматизация бизнес-процессов"
    /><Frame2
      prop="Компании со значительными темпами роста"
      iconCheckmark="/icon-checkmark2.svg"
      prop1="Налоговый консалтинг"
      iconCheckmark1="/icon-checkmark3.svg"
      prop2="Урегулирование налоговых проверок"
      iconCheckmark2="/icon-checkmark3.svg"
      prop3="Законная оптимизация налогов"
      iconCheckmark3="/icon-checkmark3.svg"
      prop4="Сопровождение проверок ФНС и ГУЭБиПК"
      iconCheckmark4="/icon-checkmark3.svg"
      prop5="Арбитражные споры"
      iconCheckmark5="/icon-checkmark3.svg"
      prop6="Безопасность бизнеса"
      propWidth="440px"
      propWidth1="452px"
    /><Frame1
      prop="Компании со значительными темпами развития"
      iconCheckmark="/icon-checkmark4.svg"
      prop1="Управленческий и правовой консалтинг"
      iconCheckmark1="/icon-checkmark5.svg"
      prop2="Комплексное сопровождение развития бизнеса"
      iconCheckmark2="/icon-checkmark5.svg"
      prop3="Международное структурирование ВЭД"
      iconCheckmark3="/icon-checkmark5.svg"
      prop4="Автоматизация бизнес-процессов"
      iconCheckmark4="/icon-checkmark5.svg"
      gR="GR, лоббизм и привлечение финансирования"
    /><Frame1
      prop="Компании – участники банкротных споров"
      iconCheckmark="/icon-checkmark.svg"
      prop1="Защита лиц, которых банкротят, физических лиц – КДЛ, кредиторов"
      iconCheckmark1="/icon-checkmark1.svg"
      prop2="Сопровождение процедуры банкротства"
      iconCheckmark2="/icon-checkmark1.svg"
      prop3="Списание долгов по кредитным и другим обязательствам"
      iconCheckmark3="/icon-checkmark1.svg"
      prop4="Подготовка и подача процессуальных документов"
      iconCheckmark4="/icon-checkmark1.svg"
      gR="Подбор опытного арбитражного управляющего"
      propWidth="309px"
      propWidth1="404px"
    />
    <div class="frame20">
      <div class="line3" />
      <div class="auto-layout-vertical43">
        <b class="b25">Компании с долговыми проблемами по кредитам и займам</b>
        <div class="auto-layout-vertical44">
          <div class="auto-layout-horizontal70">
            <img class="icon-checkmark11" alt="" src="/icon-checkmark6.svg" />
            <div class="div114">
              · Судебное представительство, представление интересов в ФССП
            </div>
          </div>
          <div class="auto-layout-horizontal71">
            <img class="icon-checkmark11" alt="" src="/icon-checkmark7.svg" />
            <div class="div114">
              · Получение судебного решения и/или исполнительного документа
            </div>
          </div>
        </div>
      </div>
    </div>
    <Frame1
      prop="Строительные компании"
      iconCheckmark="/icon-checkmark6.svg"
      prop1="· Строительный консалтинг"
      iconCheckmark1="/icon-checkmark6.svg"
      prop2="· Технический надзор"
      iconCheckmark2="/icon-checkmark7.svg"
      prop3="· Юридическое сопровождение строительства"
      iconCheckmark3="/icon-checkmark7.svg"
      prop4="· Строительная документация"
      iconCheckmark4="/icon-checkmark7.svg"
      gR="· Управление недвижимостью"
      propWidth="440px"
      propWidth1="452px"
    />
  </div>
</template>
<script>
  import { defineComponent } from "vue";
  import Frame2 from "./Frame2.vue";
  import Frame1 from "./Frame1.vue";

  export default defineComponent({
    name: "AutoLayoutHorizontal",
    components: { Frame2, Frame1 },
  });
</script>
<style scoped>
  .line3 {
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
  .b25 {
    position: relative;
    letter-spacing: -0.01em;
    line-height: 36.44px;
    display: inline-block;
    width: 440px;
  }
  .icon-checkmark11 {
    position: relative;
    width: 28px;
    height: 28px;
    overflow: hidden;
    flex-shrink: 0;
  }
  .div114 {
    position: relative;
    letter-spacing: -0.01em;
    line-height: 30px;
    display: inline-block;
    width: 404px;
    flex-shrink: 0;
  }
  .auto-layout-horizontal70 {
    width: 285px;
    height: 28px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: 7.73px;
  }
  .auto-layout-horizontal71 {
    width: 285px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: 7.73px;
  }
  .auto-layout-vertical44 {
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
  .auto-layout-vertical43 {
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
  .frame20 {
    position: relative;
    border-radius: 6.63px;
    background-color: var(--white);
    box-shadow: 0px 4.417364597320557px 13.25px rgba(12, 68, 204, 0.1);
    width: 520px;
    height: 507px;
    transform: rotate(180deg);
    transform-origin: 0 0;
  }
  .auto-layout-horizontal69 {
    position: absolute;
    top: 3868px;
    left: 140px;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    gap: var(--gap-21xl);
    text-align: left;
    font-size: var(--font-size-5xl-3);
    color: var(--black1);
    font-family: var(--body-desktop2);
  }
</style>
