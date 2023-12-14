<script>

</script>


<template>
    <section class="section_three">
        <div class="container_card">
            
            <div class="card background_one">
                <div class="title_card">
                ambienti stimolanti
                </div>
                <div class="description_card description_type_one">
                    <p>
                        Benvenuti nel mondo innovativo di "Didattica all’ Aperto" il nuovo brand di ABcompany SNC! Siamo la punta di diamante nel mercato dell'arredamento per la didattica all'aperto, pionieri nell'offrire soluzioni straordinarie per spazi educativi all'aria aperta. 
                    </p>
                </div>
            </div>
            <div class="card background_two box_shadow">
                <div class="title_card title_type_one title_card_two">
                    con più di <span class="highlight_number">+20</span> anni di esperienza nel settore
                </div>
                <div class="description_card description_type_two">
                        <p>
                            Benvenuti nel mondo innovativo di "Didattica all’ Aperto" il nuovo brand di ABcompany SNC! Siamo la punta di diamante nel mercato dell'arredamento per la didattica all'aperto, pionieri nell'offrire soluzioni straordinarie per spazi educativi all'aria aperta. 
                        </p>
                    </div>
            </div>
            <div class="card background_two box_shadow">
                <div class="title_card title_type_one">
                    <div class="part_title_card_three">
                        <div class="sub_part_title_card_three">solo materiali </div>
                        <div class="sub_part_title_card_three">
                            <img src="../assets/images/Trees2.png" alt="" class="img_trees">
                        </div>
                        
                    </div>
                    eco sostenibili 
                </div>
                <div class="description_card description_type_two">
                    <p>
                        I nostri prodotti sono il risultato tangibile dell'impegno costante verso l'eccellenza e l'innovazione sostenibile. Ogni pezzo del nostro arredamento per scuole è concepito con materiali ecologici e ecosostenibili, un impegno che va oltre la semplice qualità per abbracciare la responsabilità ambientale. La scelta accurata di questi materiali non solo assicura prodotti robusti e affidabili, ma anche un ambiente sano e sicuro per gli studenti.
                    </p>
                </div>
            </div>
            <div class="card background_one">
                <div class="title_card">
                    creatività e apprendimento pratico
                </div>
                <div class="description_card description_type_one">
                    <p>
                        Dai giochi tipo banco da lavoro ai percorsi sensoriali, ogni articolo è pensato per ispirare la creatività e promuovere un apprendimento pratico. I nostri prodotti sono più di semplici strumenti; sono il ponte tra l'educazione e la natura.
                    </p>
                </div>
            </div>
        </div>
   
    </section>
    <div class="container_triangle">
        <div class="title_image">
            showroom
        </div>
        <img src="../assets/images/triangle.png" alt="" class="triangle">
    </div>
    
    
    
</template>



<style lang="scss" scoped>

    @import '../style/partials/variables.scss';

    .section_three{
        overflow: hidden;

        padding-bottom: 200px;
        padding-top: 100px;
    }

    //Container Card

    .container_card{
        width: 80%;
        margin: auto;
        flex-wrap: wrap;
        align-items: start;
        @include flex-justify-center;
    }

    .card{
        width: 400px;
        height: auto;
       
        
        box-shadow: 15px 15px 30px 0px rgba(0, 0, 0, 0.25);
        margin: -30px 60px 60px 0px;
        padding: 35px 0px 0px 20px;
     
        @include white;
        .title_card{
            width: 100%;
            font-size: 40px;
            font-family: Staatliches;
            text-shadow: 3px 3px 15px rgba(0, 0, 0, 0.5);

            padding: 0px 0px 40px 10px;
        }

        .description_card{
            font-size: 22px;
            font-family: Tauri;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.41);
        }
    }

    .background_one{
        border-radius: 30px 30px 0px 0px;
        @include gradient-card-type-one;
    }
    .background_two{
        @include gradient-card-type-two;
    }

    .title_type_one{
        width: 80% !important;
        font-size: 55px !important;
        padding: 30px 0px 30px 0px !important;
    }

    //Titolo Card Two

    .title_card_two{
        text-align: end;
        line-height: 50px;
    }
    
    .highlight_number{
        font-size: 130px;
        line-height: 130px;
    }


    .container_triangle{
        position: relative;
        .title_image{
            width: 100%;
            height: 150px;
            
            text-shadow: 10px 10px 30px #000;
            font-family: Staatliches;
            font-size: 110px;
            display: flex;
            align-items: center;
            justify-content: center;

            position: absolute;
            top: -50px;
            @include white;
            z-index: 12;

        }
        .triangle{
            position: absolute;
            width: 100%;
            margin-top: -2px;
            margin-right: -10px;
            transform: rotate(180deg);
            z-index: 11;
        }
    }
    

    

    //Titolo Card Three

    .part_title_card_three{
        display: flex;
        .sub_part_title_card_three{
            .img_trees{
                width: 90px;
            }
        }       
    }

    .description_type_one{
        line-height: 38px;
        letter-spacing: 2.5px;
        padding: 20px 35px 80px 10px;
    }

    .description_type_two{
        align-items: start;
        font-size: 19px !important;
        line-height: 34px;
        padding: 20px 25px 20px 0px; 
    }

    @media (max-width: 1024px) {
        
        // CARD
        .card{
            margin: 0px 0px 30px;
        }

    }

    @media (max-width: 864px) {
        
        // CARD

        .card{
            margin: 0px 0px 30px;
        }
       
    }

    .title_image{
        font-size: 100px !important;
        top: -100px !important;
    }

</style>