<script>

</script>

<template>
    <footer>
    <div class="container_footer">
        <img src="../assets/images/logo.png" alt="" class="logo_footer">
        <div class="sub_container_footer">
            <div class="title_footer">
                sede operativa
            </div>
            <div class="sub_title_footer">
                <p>via De Amicis 2560033 Chiaravalle (AN)</p> 
            </div>
        </div>
        <div class="sub_container_footer">
            <div class="title_footer">
                sede legale
            </div>
            <div class="sub_title_footer">
                <p>via De Amicis 2560033 Chiaravalle (AN)</p>
            </div>
        </div>
        <div class="sub_container_footer">
            <div class="title_footer">
                documenti legali
            </div>
            <div class="sub_title_footer">
                <p>privacy policy</p>
                <p>termini e condizioni</p>
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

    .container_footer{
        
        width: 100%;
        height: 347px;
        max-width: 2200px;
        display: flex;
        align-items: center;
        
        margin: auto;
        @include background-blue-night;
    }

    .sub_container_footer{
        margin-inline: 50px;
    }

    .logo_footer{
        width: 176px;
        height: 176px;
        margin-inline: 80px;
    }

    .title_footer{
        width: 285px;
        height: 60px;
        flex-shrink: 0;

        font-family: Staatliches;
        font-size: 36px;
        font-style: normal;
        font-weight: 400;
        line-height: 98%;
        text-transform: uppercase;

        @include white;
    }

    .sub_title_footer{
        width: 285px;
        height: 60px;
        flex-shrink: 0; 

        font-family: Staatliches;
        font-size: 24px;
        font-style: normal;
        font-weight: 400;
        line-height: 98.125%;
        text-transform: uppercase;

        @include lightblue-two;
    }


    .container_footer_two{
        height: 51px;  
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
</style>