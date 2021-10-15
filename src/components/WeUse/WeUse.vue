<template>
  <div class="weuse">
    <div class="wrapper">
      <div class="weuse__block">
        <div class="weuse__block-title">
          Технологии, которые мы используем
        </div>
        <div class="weuse__block-items">
          <div class="item">
            <img src="@/assets/use1.png" alt="" height="128,59px" width="128,59px">
            <div class="title">
              SwiftUI
            </div>
          </div>
          <div class="item">
            <img src="@/assets/use2.png" alt="" height="119,6px" width="162,77px">
            <div class="title">
              ЯндексОблако
            </div>
          </div>
          <div class="item">
            <img src="@/assets/use3.png" alt="" height="128,59px" width="128,59px">
            <div class="title">
              Kotlin
            </div>
          </div>
          <div class="item">
            <img src="@/assets/use4.png" alt="" height="145,68px" width="145,68px">
            <div class="title">
              .NET Core
            </div>
          </div>
          <div class="item">
            <img src="@/assets/use5.png" alt="" height="183,45px" width="221,22px">
            <div class="title">
              MicrosoftAzure
            </div>
          </div>
          <div class="item">
            <img src="@/assets/use6.png" alt="" height="143,88px" width="164,56px">
            <div class="title">
              ReactJS
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
.weuse {
  .wrapper {
    .weuse__block {
      &-title {
        font-family: Montserrat;
        font-style: normal;
        font-weight: 800;
        font-size: 40px;
        line-height: 49px;
        color: $text;
        text-align: center;
      }
      &-items {
        display: flex;
        flex-direction: row;
        flex-wrap: nowrap;
        .item {
          width: calc(1200px / 6);
          display: flex;
          flex-direction: column;
          justify-content: center;
          img {

          }
          .title {
            font-family: Montserrat;
            font-style: normal;
            font-weight: 600;
            font-size: 26px;
            line-height: 32px;
            text-align: center;
            color: $text;
          }
        }
      }
    }
  }
}
</style>
