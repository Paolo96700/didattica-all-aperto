<script>
    export default {
        data() {
            return {
                isHovered: false,
                isMenuHidden: true,
                currentMenuItem: "",
                menuDescriptions: {
                    '1.stimolazioni sensoriali': 'La didattica all\'aperto offre un prezioso beneficio di stimolazione sensoriale agli studenti che possono sperimentare in prima persona i concetti appresi, rende l\'istruzione più tangibile e coinvolgente. Inoltre, l\'ambiente esterno offre molteplici opportunità per stimolare la creatività, favorire la concentrazione e migliorare il benessere emotivo, contribuendo così allo sviluppo globale degli studenti.'
                },
                menuPosition: 0,
                menus: [
                    { label: '1.stimolazioni sensoriali', position: 0, initialWidth: 20},
                    { label: '2.concentrazione migliorata', position: 1},
                    { label: '3.salute mentale e benessere', position: 2},
                    { label: '4.apprendimento esperienzale', position: 3},
                    { label: '5.benefici fisici', position: 4},
                ],
            };
        },
        methods: {
            setMenuHover(menuItem) {
            for (const menu of this.menus) {
                menu.isHovered = menu.label === menuItem;
            }
            },
            mostraMenu(menuItem) {
                this.currentMenuItem = menuItem;
                setTimeout(() => {
                    this.isMenuHidden = false;
                }, 800);
            },
            nascondiMenu() {
                this.currentMenuItem = "";
                this.isMenuHidden = true;
            },
            setMenuPosition(index) {
                const menuLabel = this.menus[index].label;

            if (this.currentMenuItem !== menuLabel) {
                this.nascondiMenu();
            }

                this.menuPosition = this.menus[index].position;
            },
        },
    };
</script>

<template>
  <section class="section_two">
    <!-- <img src="../assets/images/second_background.png" alt="" class="background"> -->
    <div class="content">
        <div class="brand">
            <div class="brand_text">
                Scopri il nostro nuovo brand dedicato esclusivamente alla didattica all’aperto
            </div>
        </div>
        <div class="presentation">
            <div class="title_presentation">
                Chi siamo?
            </div>
            <div class="text_presentation">
                <span>
                    Benvenuti nel mondo di 
                </span>
                <span class="highlight">
                    DIDATTICA ALL’APERTO
                </span>
                <span>
                    , la nuova proposta di ABcompany dedicata a trasformare gli spazi educativi in ambienti coinvolgenti e ispiranti. Il nostro brand si impegna a offrire soluzioni di arredamento studiate appositamente per favorire un apprendimento attivo e stimolante all'aria aperta. Dal design funzionale e resistente per aule all'aperto, a mobili versatili che facilitano l'esplorazione e la creatività degli studenti, il nostro assortimento mira a trasformare ogni ambiente esterno in un'opportunità educativa senza confini. Con materiali di alta qualità e un occhio attento al comfort e alla sicurezza, il brand "Didattica all'Aperto" di ABcompany è la scelta ideale per creare spazi educativi all'avanguardia che favoriscono la crescita e lo sviluppo dei giovani.
                </span>
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
                            @mouseover="setMenuPosition(index); mostraMenu(menu.label)"
                            @mouseout="nascondiMenu"
                    >
                        <div 
                            :class="{ 'line-hover': isHovered }"
                            class="line" 
                        ></div>
                        <div class="rhombus"></div>
                        <div class="title_menu" 
                        
                        >
                        {{ menu.label }}

                        </div>
                    </div>
                    

                    <div
                        v-if="!isMenuHidden && currentMenuItem === menu.label"
                        class="menu"
                    >
                    <div class="menu_img">
                        <img src="../assets/images/bimbi.png" alt="" />
                    </div>
                    <div class="menu_description">
                        <div class="description_menu">
                        {{ menuDescriptions[currentMenuItem] }}
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
                        Benvenuti nel mondo innovativo di "Didattica all’ Aperto" il nuovo brand di ABcompany SNC! Siamo la punta di diamante nel mercato dell'arredamento per la didattica all'aperto, pionieri nell'offrire soluzioni straordinarie per spazi educativi all'aria aperta. 
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
                        Benvenuti nel mondo innovativo di "Didattica all’ Aperto" il nuovo brand di ABcompany SNC! Siamo la punta di diamante nel mercato dell'arredamento per la didattica all'aperto, pionieri nell'offrire soluzioni straordinarie per spazi educativi all'aria aperta. 
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
                        I nostri prodotti sono il risultato tangibile dell'impegno costante verso l'eccellenza e l'innovazione sostenibile. Ogni pezzo del nostro arredamento per scuole è concepito con materiali ecologici e ecosostenibili, un impegno che va oltre la semplice qualità per abbracciare la responsabilità ambientale. La scelta accurata di questi materiali non solo assicura prodotti robusti e affidabili, ma anche un ambiente sano e sicuro per gli studenti.
                    </div>
                </div>
                <div class="card type_one second_line_card">
                    <div class="title_card title_card_four">
                       creatività e apprendimento pratico
                    </div>
                    <div class="description_card description_four">
                        Dai giochi tipo banco da lavoro ai percorsi sensoriali, ogni articolo è pensato per ispirare la creatività e promuovere un apprendimento pratico. I nostri prodotti sono più di semplici strumenti; sono il ponte tra l'educazione e la natura. 
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
    height: 8660px;
    background-image: url(../assets/images/second_background.png);
    background-repeat: no-repeat;
    background-size: cover;
    position: absolute;
    top: -820px;
    position: relative;
    overflow: hidden;
    z-index: 10;
}



.brand{
    background-color: #FFF;
    color: #86B0D6;
    font-kerning: none;
    font-size: 66px;
    font-weight: 400;
    line-height: normal;
    letter-spacing: 17.16px;
    position: absolute;
    white-space: nowrap;
    transform: rotate(13deg);
    top: 800px;
    left: -50px;
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

    @include ffcc
}

.title_presentation{
    width: 743px;
    height: 330px;


    //proprietà ereditabili
    text-align: center;
    flex-shrink: 0;

    text-shadow: 4px 4px 4px rgba(0, 0, 0, 0.25);
    font-size: 160px;
    font-weight: 400;
    line-height: 98%;
    @include white-staatliches-font-normal-uppercase;
}

.title_two{
    width: 1224px;
    height: 332px;

    text-align: left;

    margin-top: 550px;
}

.title_three{
    width: 1432px;
    height: 254px;

    text-align: left;

    margin-top: 400px;
}


.text_presentation{
    width: 1042px;
    height: 480px;
    flex-shrink: 0;

    color: #FFF;
    text-align: center;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.25);
    font-family: Tauri;
    font-size: 28px;
    @include font-normal-weight-line;
    .highlight{
        color: #FFF;
        font-family: Teko;
        font-size: 35px;
        font-weight: 600;
        line-height: 44px;
        margin-left: 12px;
    }
    
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
    margin-top:200px;
}


.sub_div_line{
    display: flex;
    align-items: center;
    height:80px;
    cursor: pointer;
}


//Menù Option - Line

.line{
    width: 10%;
    height: 0px;
    border: 5px solid #FFF;
    flex-shrink: 0; 
    stroke-width: 5px;
    color: #FFF;
    transition: width 0.6s ease;
}

// Hover Line - si allunga nel momento ci si va sopra con il mouse

.sub_div_line:hover .line {
    width: 50%;
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
    background-color: #FFF;
    transform: rotate(45deg);
}


//Menù Option - Title menù

.title_menu{
    font-family: Sintony;
    font-size: 50px;
    
    font-weight: 700;
    line-height: 98%; 
    @include white-normal-uppercase;

    margin-left:100px
}


//Menù Option - Menù

.menu{
    width: 100%;
    height: 666px;

    margin-top: -10px;
    flex-shrink: 0;
    background: radial-gradient(280.86% 219.74% at 75.46% 228.3%, #86B0D6 0%, #144470 56.26%, #A2CEF6 67.1%, #86B0D6 75.11%, #86B0D6 84.25%, #86B0D6 92.85%, #86B0D6 100%);

    transition: opacity 1s ease, height 0.5s ease;

    @include fc;
}

.menu.active {
    opacity: 1;
    height: 666px; 
}


.menu.hidden {
    display: none;
    transition: opacity 1s ease, height 0.5s ease;
}

.menu_img{
    width: 784px;
    height: 524px;
    flex-shrink: 0;
}

.menu_description{
    width: 1015px;
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

    @include white-normal-tauri;
}

//Container Card

.container_card{
    width: 90%;
    margin: auto;
    flex-wrap: wrap;
    @include fcc;

}

.card{
    flex-shrink: 0; 
}

.type_one{
    width: 641px;
    height: 884px;
    border-radius: 30px 30px 0px 0px;
    background: radial-gradient(238.57% 135.53% at 90.03% 94.18%, #6E97BB 0%, #16D6E1 100%);

    box-shadow: 15px 15px 30px 0px rgba(0, 0, 0, 0.25);
    margin-inline: 60px; 
    
}

.type_two{
    width: 600px;
    height: 890px;

    background: radial-gradient(107.26% 73.15% at 89.18% 78.17%, rgba(136, 214, 174, 0.89) 0%, rgba(65, 168, 174, 0.88) 100%);

    margin-inline: 60px;
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

    @include white-staatliches-font-normal-line-normal;
}

.title_card_two{
    margin-inline: 50px;

    text-shadow: 5px 5px 15px rgba(0, 0, 0, 0.58);
    
    font-size: 80px;
    font-weight: 400;
    letter-spacing: 2.4px;

    @include white-staatliches-font-normal-line-normal
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

    @include white-staatliches-font-normal-line-normal
}


.description_card{
    color: #FFF;

    text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.41);
    font-family: Tauri;
    font-size: 28px;
    @include font-normal-weight-line;
}

.description_one{
    margin-top: 120px;
    margin-inline: 60px;

    width: 550px;
    height: 354.774px;
    flex-shrink: 0;
    color: #FFF;

    text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.41);
    font-family: Tauri;
    font-size: 32px;
    font-style: normal;
    font-weight: 400;
    line-height: 44px; 
    letter-spacing: 5.44px;
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
    color: #FFF;
    color: #FFF;

    text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.41);
    font-family: Tauri;
    font-size: 28px;
    font-style: normal;
    font-weight: 400;
    line-height: 44px;

    margin-left: 30px;
}


.description_four{
    width: 559px;
    height: 452px;
    flex-shrink: 0;
    color: #FFF;

    text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.41);
    font-family: Tauri;
    font-size: 32px;
    font-style: normal;
    font-weight: 400;
    line-height: 44px;
    letter-spacing: 5.44px;

    margin-left: 50px;
    margin-top: 80px;
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
    color: #FFF;

    text-shadow: 5px 5px 15px rgba(0, 0, 0, 0.58);
    font-family: Staatliches;
    font-size: 80px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    letter-spacing: 2.4px;
    margin-left: 60px;
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