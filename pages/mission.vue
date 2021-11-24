<template>
  <div>
      <Header/>
      <!-- <VueSlickCarousel v-bind="slickOptions">
      <div v-for="i in 5" :key="i" class="img-wrapper">
          <div class="w-full h-32 bg-red-700 text-white">Hello {{i}}</div>
        <img :src="`./${i}-200x100.jpg`" />
      </div>
    </VueSlickCarousel> -->
      <PageBanner/>
      <Mission/>
      <Footer/>
  </div>
</template>

<script>
import Mission from '../components/about/Mission.vue'
export default {
    data() {
    return {
      slickOptions: {
        slidesToShow: 1,
        arrows: true
      }
    }
  },
    
    components:{
        Mission,
    },

}
</script>

<style>

</style>