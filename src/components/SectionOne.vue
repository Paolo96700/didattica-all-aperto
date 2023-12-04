<script>

</script>

<template>
    <section class="section_one">
        <img src="../assets/images/logo.png" alt="" class="logo">
        <div class="title_jumbo">
           didattica all'aperto
        </div>
        <img src="../assets/images/bimbo.png" alt="" class="image_child">
        <div class="description_jumbo one">
            ai bambini serve
        </div>
        <div class="description_jumbo two">
            molto più che una
        </div>
        <div class="description_jumbo three">
            classe chiusa tra
        </div>
        <div class="description_jumbo four">
            4 pareti...
        </div>
    </section>
</template>

<style lang="scss">

    @import '../style/partials/variables.scss';

    //SectionOne

    .section_one{
        height: 1700px;
        background-image: url(../assets/images/jumbo.png);
        background-repeat: no-repeat;
        background-size: cover;
        position: relative;
    }

    //SectionOne - jumbo

    .logo{
        position: absolute;
        left: 37px;
        top: 32px;
    }

    .title_jumbo {
        width: 1431px;
        height: 413px;
        flex-shrink: 0;

        color: #F2F2F2;
        text-align: center;
        font-size: 216px;
        font-weight: 800;
        line-height: 86%;
        letter-spacing: 2.16px;
       
        position: absolute;
        top: 385px;
        left: 148px;

        text-shadow: -3px -3px 0 black, 3px -3px 0 black, -3px 3px 0 black, 3px 3px 0 black;

        @include  work-sans-font-normal-uppercase;
    }



    .image_child{
        width: 530px;
        height: 405px;

        position: absolute;
        bottom: 540px;
        right: 170px;
    }

    .description_jumbo{
        color: #FFF;

        text-align: right;
        text-shadow: 4px 4px 8px rgba(0, 0, 0, 0.81);
        font-size: 70px;
        font-weight: 400;
        line-height: normal;
    
        @include staatliches-font-normal-uppercase;
    }

    .one{
        width: 706px;
        height: 137px;
        flex-shrink: 0;

        position: absolute;
        left: 551px;
        top: 868px;
    }

    .two{
        width: 924px;
        height: 109px;
        flex-shrink: 0;

        position: absolute;
        left: 407px;
        top: 1005px;
    }

    .three{
        width: 817px;
        height: 110px;
        flex-shrink: 0;

        position: absolute;
        right: 70px;
        bottom: 370px;
        left: 749px;
        top: 1131px;
    }

    .four{
        width: 817px;
        height: 110px;
        flex-shrink: 0;

        position: absolute;
        left: 749px;
        top: 1241px;
    }

</style>