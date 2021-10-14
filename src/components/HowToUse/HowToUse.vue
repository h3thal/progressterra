<template>
  <div class="howtouse">
      <div class="wrapper">
          <div class="howtouse__block">
              <div class="howtouse__block-title">
                  Как использовать
              </div>
              <div class="howtouse__block-items">
                  <div class="item">
                      <span>1</span>
                      <div class="item-text">
                        Нажмите на кнопку “Попробовать бесплатно”
                      </div>
                  </div>
                  <div class="item">
                      <span>2</span>
                      <div class="item-text">
                        После нажатия копки, вы попадете на страницу с тестовым ключом доступа
                      </div>
                  </div>
                  <div class="item">
                      <span>3</span>
                      <div class="item-text">
                        Скачайте готовые компоненты и передайте их в ваш отдел IT
                      </div>
                  </div>
                  <div class="item">
                      <span>4</span>
                      <div class="item-text">
                        На установку у вас уйдет  10 минут, после этого продуктом можно пользоваться
                      </div>
                  </div>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang='scss'>
@import '@/assets/scss/__extends.scss';
@import '@/assets/scss/__fonts.scss';
@import '@/assets/scss/__mixin.scss';
.howtouse {
    .wrapper {
        .howtouse__block {
            &-title {
                font-family: Montserrat;
                font-style: normal;
                font-weight: 800;
                font-size: 40px;
                line-height: 49px;
                color: $text;
                margin-bottom: 70px;
            }
            &-items {
                display: flex;
                flex-direction: row;
                flex-wrap: wrap;
                .item {
                  display: flex;
                  flex-direction: row;
                  width: calc(1200px / 2);
                  margin: 10px 0px;
                    span {
                      font-family: Montserrat;
                      font-style: normal;
                      font-weight: 300;
                      font-size: 60px;
                      line-height: 60px;
                      color: $text;
                      width: 40px;
                    }
                    &-text {
                      font-family: Montserrat;
                      font-style: normal;
                      font-weight: 300;
                      font-size: 25px;
                      line-height: 138.9%;
                      color: $text;
                      box-sizing: border-box;
                      padding: 0px 30px;
                    }
                }
            }
        }
    }
}
</style>
