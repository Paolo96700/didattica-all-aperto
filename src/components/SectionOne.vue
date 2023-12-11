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
        text-transform: uppercase;
        @include white;
        
        overflow: hidden;
        .container_one{
            padding-top: 50px;
            padding-inline:50px;

            @include flex-center-center-column;
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
                width: 30%;
                aspect-ratio: 3.8;

                text-align: right;
                text-shadow: 4px 4px 8px rgba(0, 0, 0, 0.8);
                font-size: 50px;
                align-self: self-end;
                font-family: Staatliches;

                margin-top:250px;
            }
        }
        .triangle{
            width: 170%;
            padding:0;
            margin: 0;
        }
        .brand{
            width: 250%;
            font-size: 50px;
            letter-spacing: 17px;
            transform: rotate(13deg);

            font-family: Staatliches;
            font-style: normal;
            text-transform: uppercase;

            margin: -50px 0px -60px -100px;

            @include lightblue;
            @include background-white;
            z-index: 10;
        }
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
            transform: translateX(-80%);
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

            @keyframes moveText {
            0% {
                transform: translateX(100%);
            }
            100% {
                transform: translateX(-100%);
            }
        }
    }

    //Media Query
    @media only screen and (max-width: 864px) {

        .sub_title_jumbo{
            margin-top:150px;
            font-size: 30px;
        }

        .brand{
            width: 260% !important;
            font-size:22px;
        }
    }

</style>