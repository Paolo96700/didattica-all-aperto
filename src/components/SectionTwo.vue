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
                        position: 1
                    },
                    { 
                        label: '3.Connessione con la Natura', 
                        description:'3.Connessione con la Natura: La didattica all\'aperto crea una connessione significativa con la natura. I bambini imparano a rispettare l\'ambiente circostante, sviluppando una consapevolezza ecologica. Questo contribuisce a formare cittadini consapevoli e responsabili del nostro pianeta.',
                        position: 2
                    },
                    { 
                        label: '4.Inclusività e Collaborazione', 
                        description:  '4.Inclusività e Collaborazione: Gli spazi verdi offrono opportunità per attività di gruppo e cooperazione, promuovendo l\'inclusività e lo spirito di squadra. Attraverso giochi e attività all\'aperto, i bambini imparano a collaborare, a rispettare le differenze e a sviluppare competenze sociali fondamentali.',
                        position: 3
                    },
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
        <div class="content">
            <div class="presentation">
                <div class="title_presentation">
                    il brand
                </div>
                <div class="text_presentation">
                    <p class="paragraph">
                        Benvenuti nel cuore della rivoluzione educativa: 
                        <span class="highlight">
                        DIDATTICA ALL’APERTO
                        </span>
                        , il nuovo brand distintivo di ABCompany dedicato alla creazione di spazi verdi pensati per scuole e aziende con una particolare attenzione ai bambini. La nostra visione unisce innovazione, apprendimento e sostenibilità, trasformando gli spazi esterni in ambienti didattici coinvolgenti. Didattica All'Aperto non è solo un marchio; è un impegno per offrire ai bambini un'educazione unica e stimolante, sviluppando il loro potenziale attraverso esperienze all'aria aperta.
                    </p>
                    <p class="paragraph">
                        Con un focus particolare sull'ecologia, molti dei nostri prodotti sono realizzati con materiali sostenibili, compresa la plastica riciclata. Ci impegniamo a ridurre l'impatto ambientale, creando soluzioni didattiche che promuovono la responsabilità ecologica sin dai primi passi dell'educazione. L'utilizzo di plastica riciclata non solo garantisce la durabilità dei nostri prodotti ma contribuisce anche a un ciclo virtuoso di riciclo.
                    </p>
                    <p class="paragraph">
                        Unirsi a Didattica All'Aperto significa investire nel futuro, creando ambienti educativi che non solo nutrono le menti dei bambini ma coltivano anche una connessione più profonda con la natura. Scoprite con noi il potenziale infinito della didattica all'aperto e contribuite il percorso di apprendimento di ogni bambino, in modo sostenibile ed entusiasmante.
                    </p>
                </div>
                
                
                
                <div class="container_menu">
                    <div class="title_presentation title_two">
                        perchè è importante per i bambini?
                    </div>
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
                                    <img src="../assets/images/bimbi.png" alt="" class="img_menu">
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
            </div>
        </div>
    </section>
</template>



<style lang="scss" scoped>

    @import '../style/partials/variables.scss';
    

    //SectionTwo

    .section_two{
        background-image: url(../assets/images/second_background.png);
        background-repeat: no-repeat;
        background-size: cover;
        overflow: hidden;
    }

    .brand{
        font-kerning: none;
        font-size: 66px;
        font-weight: 400;
        line-height: normal;
        letter-spacing: 17.16px;
        white-space: nowrap;

     
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

    .content{
        display: flex;
        justify-content: center;
    }

    // IL BRAND

    .presentation{
        width: 100%;

        margin-top: 100px; 

        @include flex-column-center;
        .title_presentation{
            text-align: center;
            flex-shrink: 0;

            text-shadow: 4px 4px 4px rgba(0, 0, 0, 0.25);
            font-size: 160px;
            font-weight: 400;
            line-height: 98%;

            margin-bottom: 150px; 
            
            @include staatliches-font-normal-uppercase;
            @include white;
        }

        .text_presentation{
            width: 45%;
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
            
            .paragraph{
                margin-bottom: 40px;
            }
        }

    }

    // Menù Option

    .container_menu{
        width: 100%;

        .title_two{
            padding-inline: 200px; 
            text-align: left;
            margin-top: 250px;
            margin-bottom: 250px;
        }

        .div_line{
            width: 100%;
            
            .sub_div_line{
                cursor: pointer;
                display: flex;
                flex-direction: column;

                .menu_label{
                    display: flex;
                    align-items: center;

                    .line{
                        border: 5px solid #FFF;
                        flex-shrink: 0; 
                        stroke-width: 5px;
                        transition: width 0.6s ease;
                        @include white;
                    }
                    
                    .rhombus {
                        width: 1.5%;
                        aspect-ratio: 1;
                        
                        transform: rotate(45deg);
                        color: white;
                        @include background-white;
                        transition:  width 0.6s ease;
                    }

                    .title_menu{
                        font-family: Sintony;
                        font-size: 50px;
                        
                        font-weight: 700;
                        line-height: 98%; 
                    
                        margin-left:85px;

                        @include normal-uppercase;
                        @include white;
                    }

                }
            }
        }
        .div_line_two{
            margin-bottom:300px;
        }
    }

    //Lunghezze iniziali delle Line

    .sub_div_line_0 .line {
        width: 10%; 
    }

    .sub_div_line_1 .line {
        width: 15%; 
    }

    .sub_div_line_2 .line {
        width: 20%; 
    }

    .sub_div_line_3 .line {
        width: 25%; 
    }

    .sub_div_line_4 .line {
        width: 30%; 
    }

    // Hover Line - si allunga nel momento ci si va sopra con il mouse

    .sub_div_line:hover .line {
        width: 35%;
    }

    //Menù Option - Line

    .menu {
        width: 0;
        height: 0;
        flex-shrink: 0;
        
        @include flex-center;
        @include gradient-menu;
        opacity: 0;
        
        overflow: hidden;
        transition: opacity 0.8s ease, width 0.8s ease, height 0.8s ease;

        .menu_img{
            width: 40%;
            flex-shrink: 0;
        }

        .menu_description{
            width: 60%;
            flex-shrink: 0;
            background: rgba(19, 48, 74, 0.39);

            padding: 60px;

            .description_menu{
                width: 85%;
                flex-shrink: 0;
                
                text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.25);
                font-size: 28px;
                font-weight: 400;
                line-height: 44px;

                padding-top: 50px;
                padding-bottom:50px;
            
                @include normal-tauri;
                @include white
            }
        }

    }

    .sub_div_line:hover .menu {
        opacity: 1;
        width: 100%;
        height: 666px;
    }


    //Media Query - 1024px

    @media only screen and (max-width: 1024px) {
        
        // IL BRAND

        .title_presentation{
            font-size: 100px !important;
        }

        .title_two{
            width: 80%;
            padding-left: 120px !important;
            margin-top: 40px !important;
            margin-bottom: 150px !important;
        }
        .text_presentation{
            font-size: 24px !important;
        }

        //PERCHE E IMPORTANTE PER I BAMBINI?

        .div_line{
            margin-bottom:100px !important;
        }

        .line{
            border: 3px solid #FFF !important; 
        }

        .rhombus{
            width: 15px;
            height: 15px;
            margin-left: -10px;
        }

        .sub_div_line:hover .menu {
            opacity: 1;
            width: 100%;
            height: 266px;
        }

        .title_menu{
            font-size: 24px !important;
        }

       
        .menu_img{
            width: 350px !important;
            height: 100% !important;
        } 
        .img_menu{
            width: 100% !important;
            height: 100% !important;
        }

        .menu_description{
            height: 100% !important;
            padding: 30px !important;
        }
        .description_menu{
            font-size: 14px !important;
            padding: 30px !important;
        }

    }



    //Media Query - 864px

    @media only screen and (max-width: 864px) {
        
        // IL BRAND
        .title_presentation{
            width: 90%;
            font-size: 70px !important;
        }
        .text_presentation{
            width: 70% !important;
            font-size: 22px !important;
        }

        .title_two{
            width: 70%;
            padding-left: 120px !important;
            margin-top: 40px !important;
            margin-bottom: 150px !important;
        }
        //PERCHE E IMPORTANTE PER I BAMBINI?

        .div_line{
            margin-bottom:100px !important;
        }

        .line{
            border: 3px solid #FFF !important; 
        }

        .rhombus{
            width: 50%;
            height: 50%;
            margin-left: -10px;
        }

        .sub_div_line:hover .menu {
            opacity: 1;
            width: 100%;
            height: 266px;
        }

        .title_menu{
            font-size: 22px !important;
        }

        .menu_img{
            width: 350px !important;
            height: 100% !important;
        } 
        .img_menu{
            width: 100% !important;
            height: 100% !important;
        }

        .menu_description{
            width: 80%;
            height: 100% !important;
            padding: 30px !important;
            display: flex;
            align-items: center;
        }
        .description_menu{
            padding: 0 !important;
            font-size: 14px !important;
            line-height: 30px !important;
        }
    
    }
</style>