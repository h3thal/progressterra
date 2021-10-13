<template>
  <div class="about">
    <div class="wrapper">
      <img src="@/assets/about-img.png" alt="" class="about__img">
      <div class="about__block">
        <div class="about__block-title">О сервисе</div>
        <div class="about__block-text">
          <p>
            Сервис работы с сегментами клиентов дает возможность более глубокого изучения и фильтрации вашей аудитории. Предоставляет API для создания статических сегментов с четким набором клиентов и динамических сегментов с изменяющимся пулом клиентов.
          </p>
          <p>
            Благодаря ISmart вы сможете провести детальную аналитику вашей базы и использовать эти данные при создании рекламных кампаний и любых других маркетинговых активностей.
          </p>
          <p>
            Протестируйте бесплатно уже сегодня!
          </p>
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
.about {
    width: 100vw;
    background-color: $bg-color;
    padding-top: 50px;
    .wrapper {
      display: flex;
      flex-direction: row;
        .about__img {
            height: 530px;
            width: 500px;
        }
        .about__block {
          margin-top: 25px;
          &-title {
            font-family: Montserrat;
            font-style: normal;
            font-weight: 800;
            font-size: 40px;
            line-height: 49px;
            color: #FCFDFF;
          }
          &-text {
            p {
              font-family: Montserrat;
              font-style: normal;
              font-weight: 300;
              font-size: 20px;
              line-height: 24px;
              color: #FCFDFF;
            }
          }
        }
    }
}
</style>
