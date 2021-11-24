<template>
  <div>
      <section>
        
        <div class="py-20 bg-gray-900 radius-for-skewed">
          <div class="container mx-auto px-4">
            <div class="flex flex-wrap">
              <div class="w-full lg:w-1/3 mb-16 lg:mb-0">
                <a class="inline-block mb-3 text-white text-3xl font-bold leading-none" href="#">
                  <img class="mb-3 h-12" src="@/atis-assets/logo/apexlogo.svg" alt="" width="auto">
                </a>
                <p class="mb-4 max-w-sm text-gray-400 leading-loose">Apex Education is an educational Institute founded with a sole motto of propagating quality education for the students those who are seeking career in engineering /medical entrance examination.</p>
                <div>
                  <a class="inline-block w-10 mr-2 p-2 bg-gray-800 hover:bg-gray-700 rounded" href="#">
                    <img class="mx-auto" src="@/atis-assets/social/facebook-f.svg">
                  </a>
                  <a class="inline-block w-10 mr-2 p-2 bg-gray-800 hover:bg-gray-700 rounded" href="#">
                    <img class="mx-auto" src="@/atis-assets/social/twitter-f.svg">
                  </a>
                  <a class="inline-block w-10 p-2 bg-gray-800 hover:bg-gray-700 rounded" href="#">
                    <img class="mx-auto" src="@/atis-assets/social/instagram-f.svg">
                  </a>
                </div>
              </div>
              <div class="w-full lg:w-2/3 lg:pl-16 flex flex-wrap justify-between">
                <div class="w-full md:w-1/3 lg:w-auto mb-16 md:mb-0">
                  <h3 class="mb-6 text-2xl font-bold text-white">Other Links</h3>
                  <ul>
                    <li class="mb-4"><nuxt-link to="/oneyear" class="text-gray-400 hover:text-gray-300" >One Year Courses</nuxt-link></li>
                    <li class="mb-4"><nuxt-link to="/twoyear" class="text-gray-400 hover:text-gray-300" >Two Year Courses</nuxt-link></li>
                    <li class="mb-4"><nuxt-link to="/foundation" class="text-gray-400 hover:text-gray-300" >Foundation</nuxt-link></li>
                    <li class="mb-4"><nuxt-link to="/onlinecourse" class="text-gray-400 hover:text-gray-300">Online Course</nuxt-link></li>
                     <li><nuxt-link to="/oneyeartarget" class="text-gray-400 hover:text-gray-300" >Target Course</nuxt-link></li>
                  </ul>
                </div>
                <div class="w-full md:w-1/3 lg:w-auto mb-16 md:mb-0">
                  <h3 class="mb-6 text-2xl font-bold text-white">Important Links</h3>
                  <ul>
                    
                    <li class="mb-4"><nuxt-link to="/privacypolicy" class="text-gray-400 hover:text-gray-300" >Privacy policy</nuxt-link></li>
                    <li class="mb-4"><nuxt-link to="/studentzone" class="text-gray-400 hover:text-gray-300" >Student Zone</nuxt-link></li>
                    <li class="mb-4"><nuxt-link to="/admissionform" class="text-gray-400 hover:text-gray-300" >Apply Online</nuxt-link></li>
                    <li class="mb-4"><nuxt-link to="" class="text-gray-400 hover:text-gray-300" >Terms &amp; Conditions</nuxt-link></li>
                    <li><nuxt-link to="/faq" class="text-gray-400 hover:text-gray-300" >FAQs</nuxt-link></li>
                  </ul>
                </div>
                <div class="w-full md:w-1/3 lg:w-auto">
                  <h3 class="mb-6 text-2xl font-bold text-white text-center">Contact Details</h3>
                  <p class="text-gray-400 hover:text-gray-300 w-30 mt-2 mb-4">
                    <span class="font-bold">Address :-</span>CMO Office Lane,<br/> Kabir Nagar,Durgakund, Varanasi</p>
                    <p class="text-gray-400 hover:text-gray-300 w-30 text-sm mt-2 mb-2">
                    <span class="font-bold">Email ID :-</span> hallo@gamil.com</p>
                    <p class="text-gray-400 hover:text-gray-300 w-30 text-sm mt-2">
                    <span class="font-bold">Mobile No. :-</span> 8960972920, 7007519673</p>
                </div>
              </div>
            </div>
            <p class="lg:text-center text-sm text-gray-400 border-t border-gray-800 pt-12 mt-16">&copy; 2021. All rights reserved by <a class="cursor-pointer">Osizone Services Pvt. Ltd</a>.</p>
          </div>
        </div>
        
      </section>
  </div>
</template>

<script>
export default {
    name: 'Footer',

}
</script>

<style>

</style>