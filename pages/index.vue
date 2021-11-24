<template>
  <div class=""> 
    
      <section class="overflow-hidden">
        <Header />
        <Banner/>
        <WelcomeSection/>
      </section>
      <Courses/>
      <!-------------------------------->
      <section>
        <div class="py-20 radius-for-skewed">
          <div class="container mx-auto px-4">
            <div class="flex flex-wrap items-center">
              <div class="w-full lg:w-1/2 mb-12 lg:mb-0">
                <StudentSay/>
              </div>
              <div class="w-full lg:w-1/2 flex flex-wrap -mx-4">
                <News/>
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-------------------------------->
      <!-- <ChoosePlan/> -->
      <Pedagogy/>
      <!-- <Facilities/> -->
      <Teachers/>
      <SignUpHome/>
      <Footer/>
    </div>
</template>

<script>
import Pedagogy from '../components/Pedagogy.vue'
export default {
  components: { Pedagogy },}
</script>
