<template>
<div class="main">
    <div class="main__inform">
        <div class="main__inform-title">
            iSmart
        </div>
        <div class="main__inform-text">
            Получайте дательную глубокую аналитику с помощью сегментации  клиентских баз
        </div>
        <div class="main__inform-btn">
            Попробовать бесплатно
        </div>
    </div>
    <div class="main__bg"></div>
</div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
@import '@/assets/scss/__extends.scss';
@import '@/assets/scss/__fonts.scss';
@import '@/assets/scss/__mixin.scss';
.main {
    height: 580px;
    &__inform {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        width: 500px;
        &-title {
            background: linear-gradient(180deg, #B97A95 0%, #2D62D6 100%);
            font-family: Georgia;
            font-style: normal;
            font-weight: bold;
            font-size: 130px;
            line-height: 148px;
            display: flex;
            align-items: center;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        &-text {
            width: 500px;
            font-family: Montserrat;
            font-style: normal;
            font-weight: normal;
            font-size: 22px;
            line-height: 27px;
            color: $text;
            margin: -20px 0 35px;
        }
        &-btn {
            width: 414px;
            height: 87px;
            background: linear-gradient(270deg, #685BE6 0%, #8980EE 100%);
            border-radius: 20px;
            font-family: Montserrat;
            font-style: normal;
            font-weight: normal;
            font-size: 25px;
            line-height: 30px;
            color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
        }
    }
    &__bg {
        background-image: url(~@/assets/hand.png);
        background-position: right;
        background-repeat: no-repeat;
        height: 750px;
        position: absolute;
        top: 0px;
        width: 100vw;
        z-index: -1;
        right: 0px;
    }
}
</style>
