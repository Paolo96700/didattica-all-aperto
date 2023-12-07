<script>

</script>

<template>
    <section class="section_one">
        <img src="../assets/images/logo.png" alt="" class="logo">
        <img src="../assets/images/title.png" alt="" class="title">
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
 
        background-image: url(../assets/images/jumbo.png);
        background-repeat: no-repeat;
        background-size: cover;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;

        padding: 150px;
        padding-bottom: 580px;
        gap: 50px;
    }

    //SectionOne - jumbo

    .logo{
        align-self: self-start;
        width: 258px;
        height: 258px;
    }

    .title{
        width: 100%;
        aspect-ratio: 3.4;
        flex-shrink: 0;
    }

    .description_jumbo{
        text-align: right;
        text-shadow: 4px 4px 8px rgba(0, 0, 0, 0.81);
        font-size: 70px;
        font-weight: 400;
        line-height: normal;
        align-self: self-end;
    
        @include staatliches-font-normal-uppercase;
        @include white;
    }

    .one{
        width: 560px;
        height: 110px;
        flex-shrink: 0;
    }

</style>