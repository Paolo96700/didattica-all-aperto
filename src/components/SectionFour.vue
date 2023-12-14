<script>

</script>

<template>
  <section class="section_four">
    <div class="part_section_one">
       
        <img src="../assets/images/eclipse.png" alt="" class="eclipse eclipse1">
        <img src="../assets/images/eclipse.png" alt="" class="eclipse eclipse2">
    
        <p class="sub_title">tavoli e panche</p>
    </div>
    <div class="part_section_two">
        <img src="../assets/images/eclipse.png" alt="" class="eclipse eclipse3">
        <img src="../assets/images/eclipse.png" alt="" class="eclipse eclipse4">
        <p class="sub_title">lavagne</p>
    </div>
    <div class="part_section_three">
        <img src="../assets/images/eclipse.png" alt="" class="eclipse eclipse5">
        <p class="sub_title five_sub_title">tribunette</p>
        <img src="../assets/images/triangle.png" alt="" class="triangle">
    </div>

   

    <div class="info">
        <div class="title_info">
            offriamo soluzioni su misura
        </div>
        <div class="description_info">
            <p>
                Ogni scuola merita di essere unica ed originale. Progettare intere aree didattiche è il nostro lavoro da più di vent'anni, fornendo soluzioni perfette per ogni esigenza. Hai un'idea da realizzare? Parliamone!
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
            <div class="text_contact">
                <span>Come preferisci essere contattato?</span>
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

        <div class="title_info title_contact_principal">
            Contattaci
        </div>

        <div class="container_contact">
            <div class="container_contact_one">
                <div class="title_contact title_contact_one">Scrivici un messaggio</div>
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
                        <span class="text_contact_two">Come preferisci essere contattato?</span>
                        <div class="container_input_radio container_input_radio_two">
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
            <div class="container_contact_two">
                <div class="sub_container_contact_one">
                    <div class="title_contact title_contact_one ">I nostri contatti</div>
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
                <div class="sub_container_contact_two ">
                    <div class="title_contact title_contact_one">dove trovarci</div>

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
                        <img src="../assets/images/map.png" alt="" class="map">
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
    overflow: hidden;
}
 
// Section Four - Part One

.eclipse{
    width: 31px;
    height: 31px;
}

.sub_title{
    color: rgba(255, 255, 255, 0.91);

    text-shadow: 5px 5px 12px #000;
    font-family: Sansita;
    font-size: 54px;
    text-transform: uppercase;
    
    position: absolute;
    bottom:20px;
    right:30px;
}

.part_section_one{
    width: 100%;
    aspect-ratio: 1.68;
    
    background-image: url(../assets/images/back1.png);
    background-repeat: no-repeat;
    background-size: cover;
    box-shadow: 26px 43px 115.3px 0px rgba(0, 0, 0, 0.81) inset;
    border-bottom: 5px solid white;
    position: relative;

    @include white;

  
    .eclipse1{
        position: absolute;
        top: 750px;
        left: 200px;
    }
    .eclipse2{
        position: absolute;
        top: 740px;
        left: 760px;
    }
}

// Section Four - Part Two

.part_section_two{
    width: 100%;
    aspect-ratio: 2.25;;
    background-image: url(../assets/images/back2.png);
    background-repeat: no-repeat;
    background-size: cover;
    box-shadow: 26px 43px 115.3px 0px rgba(0, 0, 0, 0.81) inset;
    position: relative;
    
    border-bottom: 5px solid white;

    position: relative;
    
    .eclipse3{
        position: absolute;
        top: 205px;
        left: 300px;
    }

    .eclipse4{
        position: absolute;
        top: 160px;
        left: 710px;
    }
}

// Section Four - Part Three

.part_section_three{
    width: 100%;
    aspect-ratio: 1.8;
    background-image: url(../assets/images/back3.png);
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
    box-shadow: 26px 43px 115.3px 0px rgba(0, 0, 0, 0.81) inset;

    position: relative;

    .eclipse5{
        position: absolute;
        top: 400px;
        left: 740px;
    }

    .five_sub_title{
        bottom: 80px;
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
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    margin-top: 320px;
    .title_info{
        width: 65%;

        text-shadow: 4px 4px 16px rgba(0, 0, 0, 0.35);
        font-family: Staatliches;
        font-size: 110px;
       
        padding-left: 34px;

        @include white
    }
}



.description_info{
    width: 80%;

    font-family: Tauri;
    font-size: 20px;
    padding-top: 120px;
    padding-left: 60px;

    @include white
}


//*************************** input ******************************/

.container_input{
    width: 70%;
    margin-top: 70px;
    position: relative;

    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;

}

// Imput - Container Input

.input{ 
    .inputGroup {
        margin: 1em 0em 1em 0;
        width: 80%;

        position: relative;
    }  

    .inputGroup input {
        padding: 0.8em;
        padding-inline: 1.5em;
        outline: none;
        border: 5px solid #FFF;
        background-color: transparent;
        border-radius: 106px;
        width: 100%;

        font-family: Tauri;
        font-size: 20px;

        @include white
    }

    .inputGroup label {
        font-size: 100%;
        position: absolute;
        top:22px;
        left: 20px;
        font-size: 20px;
        padding-inline:0.5em;
        font-family: Staatliches;
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
        @include background-dark-green;
    }

    .inputGroup :is(input:focus, input:valid) {
        border-color:#FFF;
    }
}

//****************************************************************/

.type_contact{
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-family: Tauri;
    font-size: 20px;

    margin-top: 70px;

    @include white;

    .text_contact{
        margin-right:150px;
    }
    .container_input_radio{
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
    border-radius: 106px;

    box-shadow: 4px 6px 4px 0px rgba(0, 0, 0, 0.25);

    text-align: center;
    font-family: Staatliches;
    font-size: 48px;
    text-transform: uppercase;

    margin-top:20px;

    padding: 8px 100px 8px 100px;

    @include white;
    @include background-button;
}

.title_contact_principal{
    display: flex;
    justify-content: center;

    margin-top: 450px;
    padding-left: 0 !important;
}

.title_contact{
    width: 100%;

    text-shadow: 10px 10px 30px rgba(0, 0, 0, 0.50);
    font-family: Staatliches;
    text-transform: uppercase;

    display: flex;
    justify-content: center;

    @include white;
}

.container_contact{
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 50px;

    padding-top: 100px;
  
    margin-bottom: 600px;
    .container_contact_one{
        width: 643px;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        
        border-radius: 49px;
        border: 5px solid #FFF;
        box-shadow: 5px 5px 10px 0px rgba(0, 0, 0, 0.25);

        margin-bottom: 20px;

        @include background-dark-green-contact;
    }


    .sub_container_contact_one{
        width: 806px;
        aspect-ratio: 1.80;
        border-radius: 49px;
        border: 5px solid #FFF;
    
        box-shadow: 5px 5px 10px 0px rgba(0, 0, 0, 0.25);

        display: flex;
        flex-direction: column;
        align-items: center;

        @include background-dark-green-contact;
    }
    .sub_container_contact_two{
        width: 806px;
        aspect-ratio: 1.5;

        border-radius: 49px;
        border: 5px solid #FFF;
        box-shadow: 5px 5px 10px 0px rgba(0, 0, 0, 0.25);

        margin-top: 30px;

        display: flex;
        flex-direction: column;
        align-items: center;

        @include background-dark-green-contact;
    }
}



.title_contact_one{
    margin-top: 30px;
    font-size: 50px;
}

.container_input_two{ 
    width: 100%;
    padding-top:30px;

    @include flex-column-center
}

.input_contact{
    padding-bottom: 10px;
}

.inputGroup input:is(input:focus, input:valid)~.label_contact{
    @include background-dark-green-contact
}

.text_contact_two{
   width: 70%; 
}

.prefer_contact{
    width: 60%;
    margin-top: 20px;
    margin-left: 20px;
}

.container_input_radio_two{
    width: 30%; 
    margin-left: 0px;

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
    @include background-dark-green-contact;
}

//*******************************************************************/

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
     
    text-transform: uppercase;

    margin-top: 15px;
    margin-bottom: 15px;

    @include white;
}

.text_info{
    font-family: Tauri;
    font-size: 20px;
     
    @include white;
}

.container_social{
    margin-top: 50px;
    display: flex;
    justify-content: space-between;
}

.sub_container_contact_two{
    padding-bottom: 30px;

    .sub_three{
        display: flex;
        margin-top: 20px;
    }
    .row_two{
        margin-left: 90px;
    }
    .sub_map{
        width: 90%;
        aspect-ratio: 1.8 !important;
        border-radius: 23px;
        background: url(<path-to-image>), lightgray 50% / cover no-repeat;
        .map{
            width: 100%;
            height: 100%;
        }
    }
}


@media (max-width: 1024px) {
        
    // SHOWROOM

    .sub_title{
        right: 55px !important;
        bottom: 5px !important;
        font-size: 45px !important;
    }

    .eclipse{
        width: 20px !important;
        height: 20px !important;
        top: 460px !important;
        left: 120px !important;
    }

    .eclipse2{
        width: 20px !important;
        height: 20px !important;
        top: 550px !important;
        left: 560px !important;
    }

    .eclipse3{
        width: 20px !important;
        height: 20px !important;
        top: 150px !important;
        left: 210px !important;
    }

    .eclipse4{
        width: 20px !important;
        height: 20px !important;
        top: 120px !important;
        left: 430px !important;
    }

    .eclipse5{
        width: 20px !important;
        height: 20px !important;
        top: 250px !important;
        left: 480px !important;
    }

    .five_sub_title{
        bottom: 70px !important;
    }

    // OFFRIAMO SOLUZIONI SU MISURA

    .info{
        margin-top: 150px;
    }


    .title_info{
        width: 82% !important;
        font-size: 100px !important;
    }

    .description_info{
        width: 90%;
        font-size: 20px !important;
        padding-left: 50px !important;
    }

    .container_input{
        width: 50%;
    }

    .container_input{
        justify-content: center;
    }

    .title_contact_principal{
        margin-top: 200px;
    }
       
}

    @media only screen and (max-width: 864px) {
        
    // SHOWROOM

    .sub_title{
        right: 55px !important;
        bottom: 5px !important;
        font-size: 35px !important;
    }

    .eclipse{
        width: 20px !important;
        height: 20px !important;
        top: 360px !important;
        left: 90px !important;
    }

    .eclipse2{
        width: 20px !important;
        height: 20px !important;
        top: 400px !important;
        left: 400px !important;
    }
     
    .sub_part_two{
        bottom: 5px !important;
        right: 160px !important;
    }
    
    .eclipse3{
        width: 20px !important;
        height: 20px !important;
        top: 110px !important;
        left: 160px !important;
    }

    .eclipse4{
        width: 20px !important;
        height: 20px !important;
        top: 90px !important;
        left: 330px !important;
    }

    .five_sub_title{
        bottom:60px !important;
    }

    .eclipse5{
        width: 20px !important;
        height: 20px !important;
        top: 230px !important;
        left: 410px !important;
    }

    // OFFRIAMO SOLUZIONI SU MISURA

    .title_info{
        width: 80%;
        font-size: 85px !important;
    }

    .description_info{
        width: 95%;
        font-size: 18px !important;
    }

    .container_input{
        margin-right: 30px;
        width: 50%;
    }

    .container_input{
        justify-content: center;
    }

    .send{
        margin-left:15px;
    }
    
    .title_contact{
        font-size: 85px !important;
    }

    .container_contact{
        margin-bottom: 300px !important;
    }

    .container_contact_one{
        width: 60% !important;
    }

    .title_contact_one{
        margin-top: 40px;
        font-size: 30px !important;
    }

    .input_contact{
        margin-right: 10px;
    }

    .inputGroup{
        width: 90% !important;
    }
    .input .inputGroup input{
        padding: 1em !important;
    }

    .prefer_contact{
        width: 90%;
        margin-left: 10px;
    }

    .inputGroup textarea{
        padding: 1.1em !important;
    }
    
    .container_contact_two{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

    .sub_container_contact_one{
       width: 60% !important;
       padding: 35px;
       .subtitle{
            font-size: 25px !important;
        }
    }

    .sub_one{
        width: 60% !important;
        margin: 0;
    }

    
    .sub_two{
        margin: 0 !important;
        margin-top: 120px !important;
        width: 40%;
    }

    .container_social img{
        width: 40px;
    }

    .sub_container_contact_two{
       width: 70% !important;
       aspect-ratio: 1.18;
        .subtitle{
            font-size: 25px !important;
        }
        .sub_three{
            width: 90%;
        }
        .row_two{
            margin-left: 130px !important;
        }
        .sub_map{
            width: 90% !important;
            aspect-ratio: 1.8 !important;
        }
    }
}


</style>