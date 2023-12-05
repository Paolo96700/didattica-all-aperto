<script>
    export default {
        data() {
            return {
               
                menus: [
                    { 
                        label: '1.Sviluppo Cognitivo e Creatività',
                        description:  '1.Sviluppo Cognitivo e Creatività: La didattica all\'aperto favorisce lo sviluppo cognitivo dei bambini attraverso esperienze sensoriali e attività stimolanti. Le sessioni all\'aperto incoraggiano la creatività, stimolando la mente dei bambini con nuovi stimoli visivi e tattili, promuovendo la risoluzione creativa dei problemi.',  
                        position: 0
                    },
                    { 
                        label: '2.Benessere Fisico e Mentale', 
                        description:'2.Benessere Fisico e Mentale: Grazie all\'attività fisica all\'aperto, i bambini migliorano il loro benessere fisico e mentale. L\'aria aperta e l\'esercizio fisico contribuiscono a una migliore salute generale, riducono lo stress e promuovono una mentalità positiva, elementi fondamentali per l\'apprendimento ottimale.',
                        position: 1},
                    { 
                        label: '3.Connessione con la Natura', 
                        description:'3.Connessione con la Natura: La didattica all\'aperto crea una connessione significativa con la natura. I bambini imparano a rispettare l\'ambiente circostante, sviluppando una consapevolezza ecologica. Questo contribuisce a formare cittadini consapevoli e responsabili del nostro pianeta.',
                        position: 2},
                    { 
                        label: '4.Inclusività e Collaborazione', 
                        description:  '4.Inclusività e Collaborazione: Gli spazi verdi offrono opportunità per attività di gruppo e cooperazione, promuovendo l\'inclusività e lo spirito di squadra. Attraverso giochi e attività all\'aperto, i bambini imparano a collaborare, a rispettare le differenze e a sviluppare competenze sociali fondamentali.',
                        position: 3},
                    { 
                        label: '5.Apprendimento Pratico e Memorizzazione',
                        description: '5.Apprendimento Pratico e Memorizzazione: La didattica all\'aperto offre un\'apprendimento pratico che facilita la memorizzazione delle informazioni. Le lezioni immersive e coinvolgenti all\'aperto creano ricordi duraturi, rendendo l\'apprendimento un\'esperienza memorabile e significativa per i bambini', 
                        position: 4
                    },

                    
                ],
            };
        },
        methods: {
            
        },
    };
</script>

<template>
    <section class="section_two">
        <!-- <img src="../assets/images/second_background.png" alt="" class="background"> -->
        <div class="content">
            <div class="brand">
                <div class="brand_text">
                    <span>
                        Scopri il nostro nuovo brand dedicato esclusivamente alla didattica all’aperto
                    </span>
                </div>
            </div>
            <div class="presentation">
                <div class="title_presentation">
                    il brand
                </div>
                <div class="text_presentation">
                    <p class="span_of_paragraph">
                        Benvenuti nel cuore della rivoluzione educativa: 
                        <span class="highlight">
                        DIDATTICA ALL’APERTO
                        </span>
                        , il nuovo brand distintivo di ABCompany dedicato alla creazione di spazi verdi pensati per scuole e aziende con una particolare attenzione ai bambini. La nostra visione unisce innovazione, apprendimento e sostenibilità, trasformando gli spazi esterni in ambienti didattici coinvolgenti. Didattica All'Aperto non è solo un marchio; è un impegno per offrire ai bambini un'educazione unica e stimolante, sviluppando il loro potenziale attraverso esperienze all'aria aperta.
                    </p>
                    <p class="span_of_paragraph">
                        Con un focus particolare sull'ecologia, molti dei nostri prodotti sono realizzati con materiali sostenibili, compresa la plastica riciclata. Ci impegniamo a ridurre l'impatto ambientale, creando soluzioni didattiche che promuovono la responsabilità ecologica sin dai primi passi dell'educazione. L'utilizzo di plastica riciclata non solo garantisce la durabilità dei nostri prodotti ma contribuisce anche a un ciclo virtuoso di riciclo.
                    </p>
                    <p class="span_of_paragraph">
                        Unirsi a Didattica All'Aperto significa investire nel futuro, creando ambienti educativi che non solo nutrono le menti dei bambini ma coltivano anche una connessione più profonda con la natura. Scoprite con noi il potenziale infinito della didattica all'aperto e contribuite il percorso di apprendimento di ogni bambino, in modo sostenibile ed entusiasmante.
                    </p>
                </div>
                
                <div class="title_presentation title_two">
                    perchè è importante per i bambini?
                </div>
                
                <div class="container_menu">
                    <div
                        v-for="(menu, index) in menus"
                        :key="index"
                        class="div_line div_line_two"
                    >
                        <div class="sub_div_line"
                            :class="'sub_div_line sub_div_line_' + index"
                        >   
                            <div class="menu_label">
                                <div class="line" ></div>
                                <div class="rhombus"></div>
                                <div class="title_menu" >
                                    {{ menu.label }}
                                </div>
                            </div>
                            <div class="menu">
                                <div class="menu_img">
                                    <img src="../assets/images/bimbi.png" alt="" />
                                </div>
                                <div class="menu_description">
                                    <div class="description_menu">
                                    {{ menu.description }}
                                    </div>
                                </div>
                            </div>
                        </div>
                        

                        
                    </div>
                </div>
                
                
                <div class="title_presentation title_three">
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
                    <div class="card type_two">
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
            </div>
        </div>
    </section>
</template>



<style lang="scss">

    @import '../style/partials/variables.scss';
    

    //SectionTwo

    .section_two{
        height: 10500px;
        background-image: url(../assets/images/second_background.png);
        background-repeat: no-repeat;
        background-size: cover;
        top: -820px;
        position: relative;
        overflow: hidden;
        z-index: 10;
    }



    .brand{
        font-kerning: none;
        font-size: 66px;
        font-weight: 400;
        line-height: normal;
        letter-spacing: 17.16px;
        position: absolute;
        white-space: nowrap;
        transform: rotate(13deg);
        top: 800px;
        left: -70px;
        
        @include lightblue;
        @include background-white;
        @include staatliches-font-normal-uppercase;
    }

    //************Animazione testo**************/

    .brand_text{
        white-space: nowrap; 
        overflow: hidden; 
        animation: moveText 18s linear infinite; 
    }


    @keyframes moveText {
        0% {
            transform: translateX(65%);
        }
        100% {
            transform: translateX(-100%);
        }
    }

    //******************************************/

    .content{
        display: flex;
        justify-content: center;
    }

    .presentation{
        width: 100%;
        margin-top: 1100px;
        @include flex-column-center
    }

    .title_presentation{
        width: 743px;
        height: 330px;

        text-align: center;
        flex-shrink: 0;

        text-shadow: 4px 4px 4px rgba(0, 0, 0, 0.25);
        font-size: 160px;
        font-weight: 400;
        line-height: 98%;

        
        @include staatliches-font-normal-uppercase;
        @include white;
    }

    .title_two{
        width: 1224px;
        height: 332px;

        text-align: left;

        margin-top: 550px;
        margin-bottom: 250px;
    }

    .title_three{
        width: 1432px;
        height: 254px;

        text-align: left;
    }

    .text_presentation{
        width: 1042px;
        height: 480px;
        flex-shrink: 0;

        text-align: center;
        text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.25);
        font-family: Tauri;
        font-size: 28px;
        @include font-normal-weight-line;
        .highlight{
            font-family: Teko;
            font-size: 35px;
            font-weight: 600;
            line-height: 44px;
            margin-left: 12px;
        }

        margin-bottom:150px;
        @include white;
        
    }

    // Menù Option

    .container_menu{
        width: 100%;
    }

    //Menù Option - Line activaction

    .div_line{
        width: 100%;
    }

    .div_line_two{
        margin-bottom:800px;
    }


    .sub_div_line{
        height:80px;
        cursor: pointer;
    }

    .menu_label{
        display: flex;
        align-items: center;
    }


    //Menù Option - Line

    .line{
        border: 5px solid #FFF;
        flex-shrink: 0; 
        stroke-width: 5px;
        transition: width 0.6s ease;
        @include white;
    }

    .menu {
        width: 0;
        height: 0;
        flex-shrink: 0;
        
        @include flex-center;
        @include gradient-menu;
        opacity: 0;
        
        overflow: hidden;
        transition: opacity 0.8s ease, width 0.8s ease, height 0.8s ease;
    }

    // Hover Line - si allunga nel momento ci si va sopra con il mouse

    .sub_div_line:hover .line {
        width: 50%;
    }

    .sub_div_line:hover .menu {
        opacity: 1;
        width: 100%;
        height: 666px;
    }
    
    //Lunghezze iniziali delle Line

    .sub_div_line_0 .line {
    width: 15%; 
    }

    .sub_div_line_1 .line {
    width: 20%; 
    }

    .sub_div_line_2 .line {
    width: 25%; 
    }

    .sub_div_line_3 .line {
    width: 30%; 
    }

    .sub_div_line_4 .line {
    width: 35%; 
    }

    //Menù Option - Rhombus

    .rhombus {
        width: 25px;
        height: 25px;
        
        transform: rotate(45deg);
        @include background-white;
    }


    //Menù Option - Title menù

    .title_menu{
        font-family: Sintony;
        font-size: 50px;
        
        font-weight: 700;
        line-height: 98%; 
    
        margin-left:100px;

        @include normal-uppercase;
        @include white;
    }


    //Menù Option - Menù


    .menu_img{
        width: 784px;
        height: 524px;
        flex-shrink: 0;
    }

    .menu_description{
        width: 1200px;
        height: 452px;
        flex-shrink: 0;
        background: rgba(19, 48, 74, 0.39);
    }

    .description_menu{
        width: 821px;
        height: 352px;
        flex-shrink: 0;
        
        text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.25);
        font-size: 28px;
        font-weight: 400;
        line-height: 44px;
        margin: 50px;

        @include normal-tauri;
        @include white
    }

    //Container Card

    .container_card{
        width: 90%;
        margin: auto;
        flex-wrap: wrap;
        @include flex-center-center;
    }

    .card{
        flex-shrink: 0; 
    }

    .type_one{
        width: 641px;
        height: 884px;
        border-radius: 30px 30px 0px 0px;
        

        box-shadow: 15px 15px 30px 0px rgba(0, 0, 0, 0.25);
        margin-inline: 60px; 
        
        @include gradient-card-type-one;
    }

    .type_two{
        width: 600px;
        height: 890px;
        margin-inline: 60px;

        @include gradient-card-type-two;
    }

    .second_line_card{
        margin-top: 100px;
    }

    .third_card{
        width: 600px;
        height: 1020px;
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

    .title_card_two{
        margin-inline: 50px;

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