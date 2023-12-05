<script>

</script>

<template>
    <section class="section_one">
        <img src="../assets/images/logo.png" alt="" class="logo">
        <div class="title_jumbo">
            <img src="../assets/images/Intersect.png" alt="" class="intersect">
            <div class="part_title_one">didattica</div>
            <div class="part_title_two">all<div class="apostrofo">,</div></div>  <div class="part_title_three">aperto</div>
        </div>
        <!-- <img src="../assets/images/bimbo.png" alt="" class="image_child"> -->
        <div class="description_jumbo one">
            esplora il futuro dell’apprendimento
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
        font-family: Work Sans;
        font-size: 216px;
        font-style: normal;
        font-weight: 800;
        line-height: 86.016%;
        letter-spacing: 2.16px;
        text-transform: uppercase;
       
        position: relative;
        position: absolute;
        top: 425px;
        left: 300px;
    }

    .part_title_one{
        position: absolute;
        left: 110px;
    }

    .part_title_two{
        position: absolute;
        top:185px;
    }

    .part_title_three{
        position: absolute;
        top:185px;
        left:508px;
    }

    .apostrofo{
        position: absolute;
        top: -108px;
        left: 384px;
    }

    .intersect{
        width: 1417.758px;
        height: 357.065px;

        position: absolute;
        top: 10px;
        right: 30px;
    }


    // .image_child{
    //     width: 530px;
    //     height: 405px;

    //     position: absolute;
    //     bottom: 540px;
    //     right: 170px;
    // }

    .description_jumbo{
        text-align: right;
        text-shadow: 4px 4px 8px rgba(0, 0, 0, 0.81);
        font-size: 70px;
        font-weight: 400;
        line-height: normal;
    
        @include staatliches-font-normal-uppercase;
        @include white;
    }

    .one{
        width: 560px;
        height: 110px;
        flex-shrink: 0;

        position: absolute;
        left: 1390px;
        top: 1075px;
    }

</style>