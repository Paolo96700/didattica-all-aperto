<script>
  import SectionOne from './components/SectionOne.vue';
  import SectionTwo from './components/SectionTwo.vue';
  import SectionThree from './components/SectionThree.vue';

  export default{
    data() {
      return {
        
      }
    },
    components: {
      SectionOne,
      SectionTwo,
      SectionThree,
    }
  }
</script>

<template>
  <div class="container">
    <SectionOne />
    <SectionTwo />
    <SectionThree/>
  </div>
</template>

<style>
 
</style>
