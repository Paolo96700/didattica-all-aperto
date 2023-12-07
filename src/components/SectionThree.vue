<script>

</script>


<template>
    <section class="section_three">
        <div class="title_presentation">
            scopri i nostri prodotti
        </div>
        <div class="container_card">
            
            <div class="card type_one">
                <div class="title_card title_card_one">
                ambienti stimolanti
                </div>
                <div class="description_card description_one">
                    <p>
                        Benvenuti nel mondo innovativo di "Didattica all’ Aperto" il nuovo brand di ABcompany SNC! Siamo la punta di diamante nel mercato dell'arredamento per la didattica all'aperto, pionieri nell'offrire soluzioni straordinarie per spazi educativi all'aria aperta. 
                    </p>
                </div>
            </div>
            <div class="card type_two card_two">
                <div class="title_card title_card_two">
                    <div class="title_part part_one">
                        con più di 
                    </div>
                    <div class="part">
                        <div class="part_two">
                        +20
                        </div>
                        <div class="title_part part_three">
                        anni
                        </div>
                    </div>
                    <div class="title_part part_four">
                        di esperienza
                    </div>
                    <div class="title_part part_five">
                        nel settore
                    </div>
                    <div class="description_card description_two">
                        <p>
                            Benvenuti nel mondo innovativo di "Didattica all’ Aperto" il nuovo brand di ABcompany SNC! Siamo la punta di diamante nel mercato dell'arredamento per la didattica all'aperto, pionieri nell'offrire soluzioni straordinarie per spazi educativi all'aria aperta. 
                        </p>
                    </div>
                </div>
            </div>
            <div class="card type_two second_line_card third_card">
                <div class="title_card title_card_three">
                    solo 
                    <span class="hidden">con</span> 
                    materiali 
                    <img src="../assets/images/Trees2.png" alt="" class="img_trees"> 
                    eco sostenibili
                </div>
                <div class="description_card description_three">
                    <p>
                        I nostri prodotti sono il risultato tangibile dell'impegno costante verso l'eccellenza e l'innovazione sostenibile. Ogni pezzo del nostro arredamento per scuole è concepito con materiali ecologici e ecosostenibili, un impegno che va oltre la semplice qualità per abbracciare la responsabilità ambientale. La scelta accurata di questi materiali non solo assicura prodotti robusti e affidabili, ma anche un ambiente sano e sicuro per gli studenti.
                    </p>
                </div>
            </div>
            <div class="card type_one second_line_card">
                <div class="title_card title_card_four">
                creatività e apprendimento pratico
                </div>
                <div class="description_card description_four">
                    <p>
                        Dai giochi tipo banco da lavoro ai percorsi sensoriali, ogni articolo è pensato per ispirare la creatività e promuovere un apprendimento pratico. I nostri prodotti sono più di semplici strumenti; sono il ponte tra l'educazione e la natura.
                    </p>
                </div>
            </div>
        </div>
    </section>
</template>



<style lang="scss" scoped>

    @import '../style/partials/variables.scss';

    .section_three{
        background-image: url(../assets/images/second_background.png);
        background-repeat: no-repeat;
        background-size: cover;
        overflow: hidden;
    }

    //Container Card

    .container_card{
        width: 100%;
        margin: auto;
        flex-wrap: wrap;
        @include flex-center-center;
    }

    .title_presentation{
        text-align: center;
        flex-shrink: 0;

        text-shadow: 4px 4px 4px rgba(0, 0, 0, 0.25);
        font-size: 160px;
        font-weight: 400;
        line-height: 98%;

        margin-top: 150px; 
        margin-bottom: 150px; 
        
        @include staatliches-font-normal-uppercase;
        @include white;
    }

    .card{
        flex-shrink: 0; 
    }

    .type_one{
        width: 35%;
        aspect-ratio: 0.75;
        border-radius: 30px 30px 0px 0px;
        

        box-shadow: 15px 15px 30px 0px rgba(0, 0, 0, 0.25);
        margin-inline: 60px; 
        
        @include gradient-card-type-one;
    }

    .type_two{
        width: 33%;
        aspect-ratio: 0.65;
        margin-inline: 60px;
        
        @include gradient-card-type-two;
    }

    

    .second_line_card{
        margin-top: 100px;
    }

    .title_card_one{
        width: 517px;
        height: 100.188px;
        flex-shrink: 0;

        font-size: 60px;
        font-weight: 400;
        letter-spacing: 1.8px;

        margin-top: 40px;
        margin-inline: 50px;

        @include staatliches-font-normal-line-normal;
        @include white;
    }

    .card_two{
        margin-top: 30px;
    }

    .title_card_two{
       padding: 40px;

        text-shadow: 5px 5px 15px rgba(0, 0, 0, 0.58);
        
        font-size: 80px;
        font-weight: 400;
        letter-spacing: 2.4px;

        @include staatliches-font-normal-line-normal;
        @include white;
    }



    .title_card_four{
        width: 588px;
        height: 150px;
        flex-shrink: 0;

        font-size: 60px;
        font-weight: 400;
        letter-spacing: 1.8px;

        margin-top: 20px;
        margin-left: 50px;

        @include staatliches-font-normal-line-normal;
        @include white;
    }


    .description_card{
        text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.41);
        font-family: Tauri;
        font-size: 28px;

        @include font-normal-weight-line;
        @include white;
    }

    .description_one{
        margin-top: 120px;
        margin-inline: 60px;

        width: 550px;
        height: 354.774px;
        flex-shrink: 0;

        text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.41);
        font-family: Tauri;
        font-size: 32px;
        font-style: normal;
        font-weight: 400;
        line-height: 44px; 
        letter-spacing: 5.44px;

        @include white;
    }

    .description_two{
        width: 550px;
        height: 275px;
        margin-top: 0px;
        margin-inline:-25px;
        font-size: 25px;

        margin-top: 50px;
    }

    .description_three{
        width: 550px;
        height: 511px;
        flex-shrink: 0;

        text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.41);
        font-family: Tauri;
        font-size: 28px;
        font-style: normal;
        font-weight: 400;
        line-height: 44px;

        margin-left: 30px;

        @include white;
    }


    .description_four{
        width: 559px;
        height: 452px;
        flex-shrink: 0;

        text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.41);
        font-family: Tauri;
        font-size: 32px;
        font-style: normal;
        font-weight: 400;
        line-height: 44px;
        letter-spacing: 5.44px;

        margin-left: 50px;
        margin-top: 80px;

        @include white;
    }

    // Title-part

    .title_part{
        text-shadow: 5px 5px 15px rgba(0, 0, 0, 0.58);
    }

    // Title-part - part_one

    .part_one{
        width: 400px;
        height: 83px;
        flex-shrink: 0;

        margin-top: 60px;
        margin-left: 150px;  
    }

    // Title-part - part_two

    .part_two{
        width: 250px;
        height: 148px;
        text-shadow: 5px 5px 15px rgba(0, 0, 0, 0.58);
        font-size: 190px;
        margin: 0;
        margin-left: 40px;
    }

    .part{
        display: flex;
        margin-top: -20px;
    }

    // Title-part - part_three

    .part_three{
        width: 199px;
        margin-left: 30px;
        margin-top: 100px;
        @include height-text-shadow;
    }

    // Title-part - part_four

    .part_four{
        width: 533px;
        margin-left: 40px;
        @include height-text-shadow;
    }

    // Title-part - part_five

    .part_five{
        width: 378px;
        margin-left: 80px;
        @include height-text-shadow;
    }

    // Title card three

    .title_card_three{
        width: 514px;
        height: 379px;
        flex-shrink: 0;

        text-shadow: 5px 5px 15px rgba(0, 0, 0, 0.58);
        font-family: Staatliches;
        font-size: 80px;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
        letter-spacing: 2.4px;
        margin-top: 80px;
        margin-left: 60px;

        @include white;
    }

    .img_trees{
        width: 137px;
        height: 182px;
        flex-shrink: 0;
        margin-top: -120px;
    }

    .hidden {
        visibility: hidden;
    }
</style>