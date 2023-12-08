<script>

</script>


<template>
    <section class="section_three">
        <div class="title_presentation">
            scopri i nostri prodotti
        </div>
        <div class="container_card">
            
            <div class="type_one card_one">
                <div class="title_card title_card_one">
                ambienti stimolanti
                </div>
                <div class="description_one">
                    <p>
                        Benvenuti nel mondo innovativo di "Didattica all’ Aperto" il nuovo brand di ABcompany SNC! Siamo la punta di diamante nel mercato dell'arredamento per la didattica all'aperto, pionieri nell'offrire soluzioni straordinarie per spazi educativi all'aria aperta. 
                    </p>
                </div>
            </div>
            <div class="type_two card_two">
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
                </div>
                <div class="description_card description_two">
                        <p>
                            Benvenuti nel mondo innovativo di "Didattica all’ Aperto" il nuovo brand di ABcompany SNC! Siamo la punta di diamante nel mercato dell'arredamento per la didattica all'aperto, pionieri nell'offrire soluzioni straordinarie per spazi educativi all'aria aperta. 
                        </p>
                    </div>
            </div>
            <div class="type_two second_line_card third_card">
                <div class="title_card title_card_three">
                    <div class="title_three_one">
                        <div >
                        solo materiali 
                        </div>
                        <img src="../assets/images/Trees2.png" alt="" class="img_trees">
                    </div>
                    <div>
                        eco sostenibili 
                    </div>
                </div>
                <div class="description_three">
                    <p>
                        I nostri prodotti sono il risultato tangibile dell'impegno costante verso l'eccellenza e l'innovazione sostenibile. Ogni pezzo del nostro arredamento per scuole è concepito con materiali ecologici e ecosostenibili, un impegno che va oltre la semplice qualità per abbracciare la responsabilità ambientale. La scelta accurata di questi materiali non solo assicura prodotti robusti e affidabili, ma anche un ambiente sano e sicuro per gli studenti.
                    </p>
                </div>
            </div>
            <div class="type_one second_line_card card_four">
                <div class="title_card title_card_four">
                creatività e apprendimento pratico
                </div>
                <div class="description_four">
                    <p>
                        Dai giochi tipo banco da lavoro ai percorsi sensoriali, ogni articolo è pensato per ispirare la creatività e promuovere un apprendimento pratico. I nostri prodotti sono più di semplici strumenti; sono il ponte tra l'educazione e la natura.
                    </p>
                </div>
            </div>
        </div>
   
    </section>
    <img src="../assets/images/triangle_lightblue.png" alt="" class="triangle">
    
</template>



<style lang="scss" scoped>

    @import '../style/partials/variables.scss';

    .section_three{
        background-image: url(../assets/images/second_background.png);
        background-repeat: no-repeat;
        background-size: cover;
        overflow: hidden;

        padding-bottom: 200px;
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

    .type_one{
        width: 35%;
        aspect-ratio: 0.75;
        border-radius: 30px 30px 0px 0px;
        

        box-shadow: 15px 15px 30px 0px rgba(0, 0, 0, 0.25);
        margin-top: -30px;
        margin-inline: 60px; 
        
        @include gradient-card-type-one;
    }

    .type_two{
        width: 34%;
        aspect-ratio: 0.65;
        margin-inline: 60px;
        
        @include gradient-card-type-two;
    }

    .second_line_card{
        margin-top: 80px;
    }

    .card_one{
        flex-shrink: 0;
        @include white;
        .title_card_one{
            font-size: 60px;
            font-weight: 400;
            letter-spacing: 1.8px;

            margin-top: 40px;
            margin-inline: 50px;

            @include staatliches-font-normal-line-normal;
          
        }
        .description_one{
            width: 85%;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.41);
            font-family: Tauri;
            font-size: 32px;
            font-style: normal;
            font-weight: 400;
            line-height: 44px; 
            letter-spacing: 5.44px;

            padding: 70px;
        }
    }

   

    .card_two{
        margin-top: 30px;
        @include white;

        .title_card_two{
            padding-top: 90px;
            padding-left: 50px;
            padding-right: 60px;
            text-shadow: 5px 5px 15px rgba(0, 0, 0, 0.58);
            
            font-size: 80px;
            font-weight: 400;
            letter-spacing: 2.4px;

            @include staatliches-font-normal-line-normal;
        }
        .description_two{
            width: 90%;
            font-family: Tauri;
            font-size: 28px;
            font-family: Tauri;
            font-size: 28px;
            line-height: 44px;

            padding-top: 40px;
            padding-left: 30px;

        }
    }
    // Title-part - Card Two

    .title_part{
        text-shadow: 5px 5px 15px rgba(0, 0, 0, 0.58);
        display: flex;
        justify-content: end;
        padding-right: 40px;
    }

    // Title-part - part_one

    .part_one{
        flex-shrink: 0;
    }

    // Title-part - part_two

    .part_two{
        width: 100%;
        text-shadow: 5px 5px 15px rgba(0, 0, 0, 0.58);
        font-size: 190px;
        display: flex;
        justify-content: end;
        margin-top: -30px;
    }

    .part{
        display: flex;
        align-items: center;
    }

    // Title-part - part_three

    .part_three{
        @include height-text-shadow;
    }

    // Title-part - part_four

    .part_four{
        width: 90%;
        margin-top: -50px;
        margin-left: 20px;
        @include height-text-shadow;
    }

    // Title-part - part_five

    .part_five{
        @include height-text-shadow;
    }

    
    .third_card{
        flex-shrink: 0;
        font-weight: 400;
        font-style: normal;
        @include white;
        .title_card_three{
            width: 80%;
            text-shadow: 5px 5px 15px rgba(0, 0, 0, 0.58);
            font-family: Staatliches;
            font-size: 80px;
            
            line-height: normal;
            letter-spacing: 2.4px;

            margin-top: 80px;
            margin-left: 60px;
        }
        .img_trees{
            flex-shrink: 0;
        }
        .hidden {
            visibility: hidden;
        }
        .description_three{
            width: 92%;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.41);
            font-family: Tauri;
            font-size: 28px; 
            line-height: 44px;

            margin-left: 30px;
        }
    }

    .title_three_one{
        width: 85%;
        display: flex;
    }

    .card_four{
        flex-shrink: 0;
        font-weight: 400;
        @include white;
        .title_card_four{
            width: 88%;
            font-size: 60px;
            
            letter-spacing: 1.8px;

            margin-top: 30px;
            margin-left: 50px;

            @include staatliches-font-normal-line-normal;
           
        }
        .description_four{
            width: 90%;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.41);
            font-family: Tauri;
            font-size: 32px;
            font-style: normal;
            line-height: 44px;
            letter-spacing: 5.44px;

            margin: 80px 0 0px 50px;
        }

       
    }
    
    .triangle{
        position: absolute;
        width: 100.1%;
        margin-top: -2px;
        margin-right: -10px;
        transform: rotate(180deg);
        z-index: 11;
    }

</style>