<script>

</script>

<template>
  <section class="section_four">
    <div class="part_section_one">
        <div class="title_image">
            showroom
        </div>
        <img src="../assets/images/eclipse.png" alt="" class="eclipse">
        <img src="../assets/images/eclipse.png" alt="" class="eclipse2">
    
        <p class="sub_title">tavoli e panche</p>
    </div>
    <div class="part_section_two">
        <img src="../assets/images/eclipse.png" alt="" class="eclipse3">
        <img src="../assets/images/eclipse.png" alt="" class="eclipse4">
        <p class="sub_title sub_part_two">lavagne</p>
    </div>
    <div class="part_section_three">
        <img src="../assets/images/eclipse.png" alt="" class="eclipse5">
        <p class="sub_title sub_part_three">tribunette</p>
        <img src="../assets/images/triangle_dark_blue.png" alt="" class="triangle">
    </div>

   

    <div class="info">
        <div class="title_info">
            offriamo soluzioni su misura
        </div>
        <div class="description_info">
            <p>
                Ogni scuola merita di essere unica ed originale. Progettare intere aree didattiche è il nostro lavoro da più di vent'anni, fornendo soluzioni perfette per ogni esigenza.Hai un'idea da realizzare? Parliamone!
            </p>
        </div>
        <div class="container_input">
            <div class="input">
                <div class="inputGroup">
                    <input autocomplete="off" required="" type="text" id="name">
                    <label for="name">NOME E COGNOME</label>
                </div>
            </div>
            <div class="input">
                <div class="inputGroup">
                    <input autocomplete="off" required="" type="text" id="telephone">
                    <label for="telephone">TELEFONO</label>
                </div>
            </div>
            <div class="input">
                <div class="inputGroup">
                    <input autocomplete="off" required="" type="text" id="email">
                    <label for="email">EMAIL</label>
                </div>
            </div>
        </div>
        <div class="type_contact">
            <div>
                <span>come preferisci essere contattato?</span>
            </div>
            <div class="container_input_radio">
                <span><input type="radio" class="input_radio">Email </span>
                <span><input type="radio" class="input_radio">Telefono</span>
            </div>
        </div>
        <div class="accept_conditions">
            <div class="checkbox-wrapper-23">
                <input type="checkbox" id="check-23">
                <label for="check-23" style="--size: 30px">
                    <svg viewBox="0,0,50,50">
                    <path d="M5 30 L 20 45 L 45 5"></path>
                    </svg>
                </label>
            </div>
            <span class="text_accept">Ho letto e accetto la politica sulla privacy ai sensi del Regolamento EU n. 679/2016</span>
        </div>
        <button class="send">
            invia
        </button>

        <div class="title_contact">
            Contattaci
        </div>

        <div class="container_contact">
            <div class="container_contact_one">
                <div class="title_contact">Scrivici un messaggio</div>
                <div class="container_input_two">
                    <div class="input input_contact">
                        <div class="inputGroup">
                            <input autocomplete="off" required="" type="text" id="name_two">
                            <label for="name_two" class="label_contact">NOME E COGNOME</label>
                        </div>
                    </div>
                    <div class="input input_contact">
                        <div class="inputGroup">
                            <input autocomplete="off" required="" type="text" id="telephone_two">
                            <label for="telephone_two" class="label_contact">TELEFONO</label>
                        </div>
                    </div>
                    <div class="input input_contact">
                        <div class="inputGroup">
                            <input autocomplete="off" required="" type="text" id="email_two">
                            <label for="email_two" class="label_contact">EMAIL</label>
                        </div>
                    </div>
                    <div class="type_contact type_contact_one prefer_contact">
                        <span class="contact_one">come preferisci essere contattato?</span>
                        <div class="container_input_radio contact_two">
                            <span><input type="radio" class="input_radio">Email </span>
                            <span><input type="radio" class="input_radio">Telefono</span>
                        </div>
                    </div>
                </div>
               
                <div class="input input_contact message">
                    <div class="inputGroup">
                        <textarea autocomplete="off" required="" type="textarea" id="message" class="input_message"></textarea>
                        <label for="message" class="label_message">message</label>
                    </div>
                </div>
            </div>
            <div>
                <div class="container_contact_two">
                    <div class="title_contact">I nostri contatti</div>
                    <div class="sub_container_one">
                        <div class="sub_one">
                            <div class="row_container">
                                <span class="subtitle">Email</span>
                                <span class="text_info">abcompany@gmail.com</span>
                            </div>
                            <div class="row_container">
                                <span class="subtitle">whatsapp</span>
                                <span class="text_info">+39 333 321 3215</span>
                            </div>
                            <div class="row_container">
                                <span class="subtitle">Telefono</span>
                                <span class="text_info">0712311258</span>
                            </div>
                        </div>
                        <div class="sub_two">
                            <span class="subtitle">seguici anche sui social</span>
                            <div class="container_social">
                                <img src="../assets/images/Youtube.png" alt="" class="social">
                                <img src="../assets/images/Instagram.png" alt="" class="social">
                                <img src="../assets/images/Facebook.png" alt="" class="social">
                            </div>
                        </div>
                    </div>
                </div>
                <div class="container_contact_three">
                    <div class="title_contact title_map">dove trovarci</div>

                    <div class="sub_three">
                        <div class="row_container">
                            <span class="subtitle">sede legale</span>
                            <span class="text_info">Via Camerata qualcosa 12, 90003</span>
                        </div>
                        <div class="row_container row_two">
                            <span class="subtitle">sede operativa</span>
                            <span class="text_info">Via Camerata qualcosa 12, 90003</span>
                        </div>
                    </div>
                    <div class="sub_map">
                        <img src="../assets/images/map.png" alt="">
                    </div>
                  
                </div>
            </div>

        </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>

@import '../style/partials/variables.scss';

.section_four{
    z-index:10;
}
 
// Section Four - Part One

.part_section_one{
    width: 100%;
    aspect-ratio: 1.38;

    flex-shrink: 0;
    color: #FFF;
    font-style: normal;
    font-weight: 400;
    text-transform: uppercase;
    

    background-image: url(../assets/images/back1.png);
    background-repeat: no-repeat;
    background-size: cover;
    box-shadow: 26px 43px 115.3px 0px rgba(0, 0, 0, 0.81) inset;
    border-bottom: 10px solid white;
    position: relative;
    overflow: hidden;

    .title_image{
        width: 100%;
        aspect-ratio: 6;
        
        text-shadow: 10px 10px 30px #000;
        font-family: Staatliches;
        font-size: 160px;

        background: rgba(0, 0, 0, 0.28);
        backdrop-filter: blur(3.60px);

        display: flex;
        align-items: center;
        justify-content: center;
        
        position: absolute;
        top: 285px;

        z-index: 10;
    }
    .eclipse{
        width: 41px;
        height: 41px;
        flex-shrink: 0;
        position: absolute;
        top: 895px;
        left: 220px;
    }
    .eclipse2{
        width: 41px;
        height: 41px;
        flex-shrink: 0;
        position: absolute;
        top: 1100px;
        left: 1050px;
    }
}

.sub_title{
    color: rgba(255, 255, 255, 0.91);

    text-shadow: 5px 5px 12px #000;
    font-family: Sansita;
    font-size: 74px;
    text-transform: uppercase;
    
    position: absolute;
    bottom:-40px;
    right:140px;
}




// Section Four - Part Two

.part_section_two{
    width: 100%;
    aspect-ratio: 2.25;
    flex-shrink: 0;
    background-image: url(../assets/images/back2.png);
    background-repeat: no-repeat;
    background-size: cover;
    box-shadow: 26px 43px 115.3px 0px rgba(0, 0, 0, 0.81) inset;
    position: relative;
    
    border-bottom: 10px solid white;

    position: relative;
    overflow: hidden;
    
    .eclipse3{
        width: 41px;
        height: 41px;
        flex-shrink: 0;
        position: absolute;
        top: 275px;
        left: 450px;
    }

    .eclipse4{
        width: 41px;
        height: 41px;
        flex-shrink: 0;
        position: absolute;
        top: 200px;
        left: 920px;
    }
    
    .sub_part_two{  
        right: 360px;
    }
}

// Section Four - Part Three

.part_section_three{
    width: 100%;
    height: 1075px;
    flex-shrink: 0;
    background-image: url(../assets/images/back3.png);
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
    overflow: hidden;
    box-shadow: 26px 43px 115.3px 0px rgba(0, 0, 0, 0.81) inset;

    position: relative;

    .eclipse5{
        width: 41px;
        height: 41px;
        flex-shrink: 0;
        position: absolute;
        top: 600px;
        left: 940px;
    }
    .sub_part_three{
        bottom: 110px;
        right: 270px;
    }


}

.triangle{
    position: absolute;
    width: 100.5%;
    bottom: 0;
    margin-left: -5px;
    margin-bottom: -2px;
    z-index: 11;
}

// Section Four - Container Contact

.info{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

.title_info{
    width: 65%;
    flex-shrink: 0;

    text-shadow: 4px 4px 16px rgba(0, 0, 0, 0.35);
    font-family: Staatliches;
    font-size: 160px;
    font-style: normal;
    font-weight: 400;
    line-height: 98.125%; 
    text-transform: uppercase;

    margin-top: 180px;
    margin-left: 34px;

    @include white
}

.description_info{
    width: 70%;
    flex-shrink: 0;

    font-family: Tauri;
    font-size: 32px;
    font-style: normal;
    font-weight: 400;
    line-height: 98.125%;

    margin-top: 180px;

    @include white
}


//*************************** input ******************************/

.container_input{
    width: 100%;
    margin-top: 70px;
    position: relative;

    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

// Imput - Container Input

.input{
    margin-right: 110px;  
    .inputGroup {
        margin: 1em 0 1em 0;
        width: 326px;

        position: relative;
    }  

    .inputGroup input {
        padding: 1.0em;
        padding-inline: 2em;
        outline: none;
        border: 5px solid #FFF;
        background-color: transparent;
        border-radius: 106px;
        width: 100%;

        font-family: Tauri;
        font-size: 20px;
        font-style: normal;
        font-weight: 400;

        @include white
    }

    .inputGroup label {
        font-size: 100%;
        position: absolute;
        top:25px;
        left: 20px;
        font-size: 20px;
        padding-inline:0.5em;
        font-family: Staatliches;
        font-weight: 400;

        margin-left: 0.5em;
        pointer-events: none;

        transition: all 0.3s ease;

        @include white
    }

    .inputGroup :is(input:focus, input:valid)~label {
        transform: translateY(-50%) scale(.9);
        top:5px;
        margin: 0em;
        margin-left: 1.2em;
        @include background-dark-blue;
    }

    .inputGroup :is(input:focus, input:valid) {
        border-color:#FFF;
    }
}

//****************************************************************/

.type_contact{
    display: flex;
    flex-shrink: 0;

    font-family: Tauri;
    font-size: 20px;
    font-style: normal;
    font-weight: 400;
    line-height: 98%;

    margin-top: 70px;

    @include white;
    .container_input_radio{
        margin-left: 150px;

        .input_radio{
            width: 18px;
            height: 18px;
            margin-right: 10px;
            fill: rgba(217, 217, 217, 0.00);

            stroke-width: 2px;
            stroke: #FFF;
        }
    }
}


.accept_conditions{
    display: flex;
    align-items: center;

    font-family: Tajawal;
    font-size: 20px;
    font-style: normal;
    font-weight: 400;
    line-height: 98%;

    margin-top: 70px;
    margin-bottom: 20px;

    @include white
}

//***************************checkbox ******************************/

.checkbox-wrapper-23 *,
.checkbox-wrapper-23 *:after,
.checkbox-wrapper-23 *:before {
    box-sizing: border-box;
}

.checkbox-wrapper-23 input {
  position: absolute;
  opacity: 0;
}

.checkbox-wrapper-23 input:checked + label svg path {
  stroke-dashoffset: 0;
}

.checkbox-wrapper-23 input:focus + label {
  transform: scale(1.03);
}

.checkbox-wrapper-23 input + label {
  display: block;
  border: 5px solid rgb(253, 237, 237);
  width: var(--size);
  height: var(--size);
  border-radius: 6px;
  cursor: pointer;
  transition: all .2s ease;
}

.checkbox-wrapper-23 input + label:active {
  transform: scale(1.05);
  border-radius: 12px;
}

.checkbox-wrapper-23 input + label svg {
  pointer-events: none;
  padding: 5%;
}

.checkbox-wrapper-23 input + label svg path {
  fill: none;
  stroke: rgb(247, 247, 247);
  stroke-width: 4px;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-dasharray: 100;
  stroke-dashoffset: 101;
  transition: all 250ms cubic-bezier(1,0,.37,.91);
}

//******************************************************************/

.text_accept{
    margin-top: 5px;
    margin-left: 10px;
}


.send{
    flex-shrink: 0;
    border-radius: 106px;

    box-shadow: 4px 6px 4px 0px rgba(0, 0, 0, 0.25);

    text-align: center;
    font-family: Staatliches;
    font-size: 48px;
    font-style: normal;
    font-weight: 400;
    line-height: 44px;
    text-transform: uppercase;

    margin-top:20px;

    padding: 10px 80px 10px 80px;

    @include white;
    @include background-button;
}
  

.title_contact{
    width: 100%;
    flex-shrink: 0;

    text-shadow: 10px 10px 30px rgba(0, 0, 0, 0.50);
    font-family: Staatliches;
    font-size: 160px;
    font-style: normal;
    font-weight: 400;
    line-height: 98%;
    text-transform: uppercase;

    margin-top: 400px;

    @include white;

    display: flex;
    justify-content: center;
}

.container_contact{
    display: flex;
    flex-wrap: wrap;
    justify-content: center;

    margin-top: 180px;
  
    margin-bottom: 600px;
    .container_contact_one{
        width: 90%;
        flex-shrink: 0; 
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        
        border-radius: 49px;
        border: 5px solid #FFF;
        box-shadow: 5px 5px 10px 0px rgba(0, 0, 0, 0.25);

        margin-bottom: 20px;

        @include background-dark-blue-contact;
    }
}



.title_contact{
    flex-shrink: 0;

    text-shadow: 10px 10px 27px rgba(0, 0, 0, 0.30);
    font-family: Staatliches;
    font-size: 50px;
    font-style: normal;
    font-weight: 400;
    line-height: 98.125%;
    text-transform: uppercase;

    margin-top: 40px;

    @include white;
    @include flex-center-center;
}

.container_input_two{ 
    margin-top: 50px;

    @include flex-column-center
}

.input_contact{
    margin-left: 30px;
    margin-top: 20px;
}

.inputGroup :is(input:focus, input:valid)~.label_contact{
    @include background-dark-blue-contact;
}

.type_contact_one{
    margin-top: 0px;
}

.contact_one{
   
    margin-left: 70px;
}

.prefer_contact{
    margin-top: 20px;
}

.contact_two{
    margin-left: 30px;

    display: flex;
    flex-direction: column;
}

//*************************** message *******************************/

.message{
    margin-top: 100px;
    margin-bottom: 50px;
}

.inputGroup textarea {

    width: 80%;
    aspect-ratio: 1.2;

    padding: 1.0em;
    padding-inline: 2em;
    outline: none;
    border: 5px solid #FFF;
    background-color: transparent;
    border-radius: 33px;
    width: 100%;
    font-family: Tauri;
    font-size: 20px;
    font-style: normal;
    font-weight: 400;
    resize: none;

    @include white;
}

.inputGroup label {
    font-size: 100%;
    position: absolute;
    top: 25px;
    left: 20px;
    font-size: 20px;
    padding-inline: 0.5em;
    font-family: Staatliches;
    font-weight: 400;
    margin-left: 0.5em;
    pointer-events: none;
    transition: all 0.3s ease;

    @include white;
}

.inputGroup textarea:focus,
.inputGroup textarea:valid {
    border-color: #FFF;
}

.inputGroup textarea:focus + label,
.inputGroup textarea:valid + label {
    transform: translateY(-50%) scale(.9);
    top: 5px;
    margin: 0em;
    margin-left: 1.2em;
    @include background-dark-blue-contact;
}

//*******************************************************************/


.container_contact_two{
    width: 90%;
    height: 427px;
    flex-shrink: 0;
    border-radius: 49px;
    border: 5px solid #FFF;
  
    box-shadow: 5px 5px 10px 0px rgba(0, 0, 0, 0.25);

    display: flex;
    flex-direction: column;
    align-items: center;

    margin-left: 50px;

    @include background-dark-blue-contact;
}

.sub_container_one{
    display: flex;
    margin-top: 15px;
}

.sub_one{
    margin-inline:50px;
}

.sub_two{
    margin-top: 110px;
    margin-inline:50px;
}

.row_container{
    display: flex;
    flex-direction: column;
    margin-bottom: 15px;
}

.subtitle{
    font-family: Staatliches;
    font-size: 30px;
    font-style: normal;
    font-weight: 400;
    line-height: 98%; 
    text-transform: uppercase;

    margin-top: 15px;
    margin-bottom: 15px;

    @include white;
}

.text_info{
    font-family: Tauri;
    font-size: 20px;
    font-style: normal;
    font-weight: 400;
    line-height: 98%; 

    @include white;
}

.container_social{
    margin-top: 50px;
    display: flex;
    justify-content: space-between;
}

.container_contact_three{
    width: 90%;
    height: 681px;
    flex-shrink: 0;

    border-radius: 49px;
    border: 5px solid #FFF;
    box-shadow: 5px 5px 10px 0px rgba(0, 0, 0, 0.25);

    margin-top: 20px;
    margin-left: 50px;

    display: flex;
    flex-direction: column;
    align-items: center;

    @include background-dark-blue-contact;
}

.title_map{
    margin-top: 50px;
}

.sub_three{
    display: flex;
    margin-top: 20px;
}

.row_two{
    margin-left: 90px;
}

.sub_map{

    height: 400px;
    flex-shrink: 0;

    margin-inline: 20px;

    border-radius: 23px;
    border: 6px solid #3074CB;
    background: url(<path-to-image>), lightgray 50% / cover no-repeat;
}

</style>