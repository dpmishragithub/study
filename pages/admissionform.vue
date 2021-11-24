<template>
  <section>
      <Header/>
      <!-- <div class="mt-4 pb-4">
           <a class="text-3xl font-bold leading-none" href="#">
        <img
          class="h-12"
          src="@/atis-assets/logo/logo.png"
          alt=""
          width="auto"
        />
      </a>
      </div> -->
      <BasicDetails/>
      <!-- <PersonalDetails/> -->
  </section>
</template>

<script>
import BasicDetails from '../components/admissionform/BasicDetails.vue'
import PersonalDetails from '../components/admissionform/PersonalDetails.vue'
export default {

    components:{
        BasicDetails,
        PersonalDetails,
    },

}
</script>

<style>

</style>