<script>

</script>

<template>
    <footer>
    <div class="container_footer">
        <img src="../assets/images/logo.png" alt="" class="logo_footer">
        <div class="sub_container_footer">
            <div class="sub_container_footer_two">
                <div class="title_footer">
                    sede operativa
                </div>
                <div class="sub_title_footer">
                    <p>via De Amicis 2560033 Chiaravalle (AN)</p> 
                </div>
            </div>
            <div class="sub_container_footer_two">
                <div class="title_footer">
                    sede legale
                </div>
                <div class="sub_title_footer">
                    <p>via De Amicis 2560033 Chiaravalle (AN)</p>
                </div>
            </div>
            <div class="sub_container_footer_two">
                <div class="title_footer">
                    documenti legali
                </div>
                <div class="sub_title_footer">
                    <p class="privacy">privacy policy</p>
                    <p>termini e condizioni</p>
                </div>
            </div>
        </div>
        
        
    </div>
    <div class="container_footer_two">
        <span class="span_footer">
            © 2023 AB Company SNC P.IVA e C.F. 01555000429
        </span>
        <span class="span_footer">
            sito web disegnato e realizzato da future +
        </span>
    </div>
   
  </footer>
</template>

<style lang="scss">

    @import '../style/partials/variables.scss';

    p{
        margin-block-start: 0em;
        margin-block-end: 0em;
    }

    .container_footer{   
        width: 100%;
        aspect-ratio: 5.85;
        max-width: 2200px;
        display: flex;
        align-items: center;
        margin: auto;

        @include background-blue-night;
    }

    .logo_footer{
        width: 12%;
        aspect-ratio: 1;
        margin-left:50px;
    }

    .sub_container_footer{
        margin-left: 110px;
        height: 100%;
        display: flex;
        align-items: center;
    }

    .sub_container_footer_two{
        width: 31.5%;
        height: 29.5%;

        .title_footer{
            width: 100%;
            height: 30%;
            flex-shrink: 0;

            font-family: Staatliches;
            font-size: 36px;
            font-style: normal;
            font-weight: 400;
            line-height: 98%;
            text-transform: uppercase;

            margin-bottom:20px; 

            @include white;
        }
    }

   

    .sub_title_footer{
        width: 100%;
        height: 70%;
        flex-shrink: 0; 

        font-family: Staatliches;
        font-size: 24px;
        font-style: normal;
        font-weight: 400;
        line-height: 98.125%;
        text-transform: uppercase;

        @include lightblue-two;
    }

    .privacy{
        margin-bottom: 10px;
    }


    .container_footer_two{
        width: 100%;
        aspect-ratio: 35.3; 
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;

        @include background-blue-dark-night
    }

    .span_footer{
        font-family: Yantramanav;
        font-size: 12px;
        font-style: normal;
        font-weight: 600;
        line-height: 98.125%; 
        text-transform: uppercase;

        @include white;
    }



    @media only screen and (max-width: 1024px) {
        .title_footer{
            font-size: 26px !important;
        }

        .sub_title_footer{
            font-size: 20px !important;
        }

        .span_footer{
            font-size: 8px !important;
        }
    }

    @media only screen and (max-width: 864px) {
        .sub_container_footer_two{
            margin-top: -30px;
            .title_footer{
                font-size: 22px !important;
            }
            .sub_title_footer{
                font-size: 16px !important;
            }

        }
        
        

        .span_footer{
            font-size: 6px !important;
        }
    }
</style>