<script>
  import SectionOne from './components/SectionOne.vue';
  import SectionTwo from './components/SectionTwo.vue';
  import SectionThree from './components/SectionThree.vue';
  import SectionFour from'./components/SectionFour.vue';
  import AppFooter from './components/AppFooter.vue';

  export default{
    data() {
      return {
        
      }
    },
    components: {
      SectionOne,
      SectionTwo,
      SectionThree,
      SectionFour,
      AppFooter,
    }
  }
</script>

<template>
  <div class="container">
    <SectionOne />
    <SectionTwo />
    <SectionThree/>
    <SectionFour/>
  </div>
  <div class="footer_container">
    <!-- <AppFooter /> -->
  </div>
  
</template>

<style>
 
</style>
