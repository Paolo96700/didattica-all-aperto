<script>

</script>

<template>
    <section class="section_one">
        <div class="container_one">
            <img src="../assets/images/logo.png" alt="" class="logo">
            <img src="../assets/images/title.png" alt="" class="title">
            <!-- <img src="../assets/images/bimbo.png" alt="" class="image_child"> -->
            <div class="sub_title_jumbo">
        
                esplora il futuro dell’apprendimento
            
            </div>
        </div>
        <img src="../assets/images/triangle_lightblue_two.png" alt="" class="triangle">
        <div class="brand">
            <div class="brand_text">
                <span>
                    Scopri il nostro nuovo brand dedicato esclusivamente alla didattica all’aperto
                </span>
            </div>
        </div>
    </section>
    
</template>

<style lang="scss" scoped>

    @import '../style/partials/variables.scss';

    //SectionOne

    .section_one{
        background-image: url(../assets/images/jumbo.png);
        background-repeat: no-repeat;
        background-size: cover;
        
        overflow: hidden;
        .container_one{
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            padding-top: 50px;
            padding-inline:50px;
        }
    }

   
    .triangle{
        width: 170%;
        padding:0;
        margin: 0;
    }


    //SectionOne - jumbo

    .logo{
        align-self: self-start;
        width: 15%;
        aspect-ratio: 1;
    }

    .title{
        width: 80%;
        aspect-ratio: 3.4;
        flex-shrink: 0;
    }

    .sub_title_jumbo{
        width: 40%;
        aspect-ratio: 3.8;

        flex-shrink: 0;
        align-self: self-end;

        text-align: right;
        text-shadow: 4px 4px 8px rgba(0, 0, 0, 0.81);
        font-size: 70px;
        font-weight: 400;
        line-height: normal;
        align-self: self-end;

        margin-top:450px;
    
        @include staatliches-font-normal-uppercase;
        @include white;

        
    }

    
    .brand{
        width: 250%;
        font-kerning: none;
        font-size: 66px;
        font-weight: 400;
        line-height: normal;
        letter-spacing: 17.16px;
        white-space: nowrap;
        transform: rotate(13deg);

        margin-top:-120px;
        margin-bottom: 25px;
        margin-left: -300px; 
     
        @include lightblue;
        @include background-white;
        @include staatliches-font-normal-uppercase;

        z-index: 10;
    }

    //************Animazione testo**************/

    .brand_text{
        white-space: nowrap; 
        overflow: hidden; 
        animation: moveText 17s linear infinite; 
    }


    @keyframes moveText {
        0% {
            transform: translateX(48%);
        }
        100% {
            transform: translateX(-70%);
        }
    }

    //******************************************/


    //Media Query
    @media only screen and (max-width: 1024px) {

        .sub_title_jumbo{
            margin-top:150px;
            font-size: 40px;
        }

        .brand{
            font-size:40px
        }
    }

</style>