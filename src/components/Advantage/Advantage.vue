<template>
<div class="advantage">
    <div class="wrapper">
        <div class="advantage__block">
            <div class="advantage__block-title">
                Преимущества
            </div>
            <div class="advantage__block-items">
                <div class="item">
                    <img src="@/assets/1.png" alt="">
                    <div class="item-text">
                        Интеграция в вашу CRM или самостоятельное использование
                    </div>
                </div>
                <div class="item">
                    <img src="@/assets/2.png" alt="">
                    <div class="item-text">
                        Бесплатный тестовый ключ для iOS, Kotlin и ReactJS
                    </div>
                </div>
                <div class="item">
                    <img src="@/assets/3.png" alt="">
                    <div class="item-text">
                        Вариативность  фильтраций и выборок
                    </div>
                </div>
                <div class="item">
                    <img src="@/assets/4.png" alt="">
                    <div class="item-text">
                        Детальная статистика и аналитика
                    </div>
                </div>
                <div class="item">
                    <img src="@/assets/5.png" alt="">
                    <div class="item-text">
                        Установка за 10 минут
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
.advantage {
    margin: 80px 0px;
    .wrapper {
        .advantage__block {
            &-title {
                font-family: Montserrat;
                font-style: normal;
                font-weight: 800;
                font-size: 40px;
                line-height: 49px;
                color: $text;
            }
            &-items {
                display: flex;
                flex-direction: row;
                flex-wrap: wrap;
                justify-content: center;
                .item {
                    display: flex;
                    flex-direction: row;
                    width: calc(1200px / 3);
                    padding: 50px 15px;
                    box-sizing: border-box;
                    align-self: flex-start;
                    img {
                        height: 40px;
                        width: 40px;
                    }
                    &-text {
                        font-family: Montserrat;
                        font-style: normal;
                        font-weight: 300;
                        font-size: 25px;
                        line-height: 30px;
                        display: flex;
                        align-items: center;
                        padding-left: 20px;
                        color: $text;
                    }
                }
            }
        }
    }
}
</style>
