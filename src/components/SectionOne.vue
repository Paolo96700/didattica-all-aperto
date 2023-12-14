<script>

</script>

<template>
    <section class="section_one">
        <div class="container_one">
            <img src="../assets/images/logo.png" alt="" class="logo">
            <img src="../assets/images/title.png" alt="" class="title">
            <div class="sub_title_jumbo">
        
                esplora il futuro dell’apprendimento
            
            </div>
        </div>

        <img src="../assets/images/triangle.png" alt="" class="triangle">
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
            }
            .sub_title_jumbo{
                width: 30%;
                aspect-ratio: 3.8;

                text-align: right;
                text-shadow: 4px 4px 8px rgba(0, 0, 0, 0.8);
                font-size: 50px;
                align-self: self-end;
                font-family: Staatliches;

                padding-top: 250px;
            }
        }

        .triangle{
            width: 110%;
            margin-bottom: -40px;
        }

        
        .brand{
            width: 200%;
            font-size: 30px;
            letter-spacing: 17px;
            transform: rotate(13deg);

            font-family: Staatliches;
            text-transform: uppercase;

            position: absolute;
            top: 1400px;
            left: -60px;

            @include dark-green;
            @include background-white;
            z-index: 12;

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
            transform: translateX(55%);
        }
        100% {
            transform: translateX(-80%);
        }
    }

    //******************************************/


    // Media Query
    @media (max-width: 1024px) {

        .logo{
            width: 20% !important;
        }

        .title{
            padding-top: 90px !important;
            width: 95% !important;
        }

        .sub_title_jumbo{
            margin: 0 !important;
            padding-top: 110px !important;
            font-size: 35px !important;
        }

        .triangle{
            margin-bottom: -10px !important;
        }

        .brand{
            width: 220% !important;
            top: 1120px !important;
        }

        @keyframes moveText {
            0% {
                transform: translateX(60%);
            }
            100% {
                transform: translateX(-100%);
            }
        }
    }

    @media (max-width: 864px) {

        .title{
            padding-top: 90px !important;
            width: 100% !important;
        }

        .sub_title_jumbo{
            font-size: 30px !important;
        }

        .brand{
            width: 295% !important;
            top: 1000px !important;
            font-size:22px;
        }
    }

    @media (max-width: 480px) {

        .logo{
            width: 35% !important;
        }

        .title{
            padding-top: 90px !important;
            width: 110% !important;
        }

        .sub_title_jumbo{
            width: 70% !important;
            margin-right: -20px !important;
            font-size: 20px !important;
        }

        .brand{
            width: 500% !important;
            top: 820px !important;
            font-size:20px!important;
        }

        @keyframes moveText {
            0% {
                transform: translateX(22%);
            }
            100% {
                transform: translateX(-100%);
            }
        }
    }


</style>