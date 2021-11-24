<template>
  <div>
<section>
        
        <div class="py-20 bg-gray-50 radius-for-skewed">
          <div class="container mx-auto px-4">
            <div class="mb-12">
              <h2 class="text-4xl text-red-500 text-center lg:text-5xl font-bold font-heading border-b-2 border-gray-100">Contact</h2>
              <p class="text-gray-500 text-center leading-loose">Got any question? Let&rsquo;s talk about it.</p>
            </div>
            <div class="flex flex-wrap">
              <div class="w-full lg:w-1/2 mb-16 lg:mb-0">
                <div class="flex flex-wrap">
                  <div class="mb-12 w-full">
                    <h3 class="mb-2 text-2xl lg:text-3xl font-bold">Office Address</h3>
                    <p class="text-gray-400">CMO Office Lane, Kabir Nagar,</p>
                    <p class="text-gray-400">Durgakund, Varanasi</p>
                  </div>
                  <div class="mb-12 w-full ">
                    <h3 class="mb-2 text-2xl lg:text-3xl font-bold">Email Address</h3>
                    <p class="text-gray-400">apexclassesonline.com</p>
                  </div>
                  <div class="mb-12 w-full ">
                    <h3 class="mb-2 text-2xl lg:text-3xl font-bold">Phone Number</h3>
                    <p class="text-gray-400">8960972920, 7007519673</p>
                  </div>
                  <!-- <div class="w-full ">
                    <h3 class="mb-2 text-2xl lg:text-3xl font-bold">Socials</h3>
                    <div class="flex">
                      <a class="mr-3" href="#">
                        <img src="@/atis-assets/social/facebook.svg" alt="">
                      </a>
                      <a class="mr-3" href="#">
                        <img src="@/atis-assets/social/twitter.svg" alt="">
                      </a>
                      <a href="#">
                        <img src="@/atis-assets/social/instagram.svg" alt="">
                      </a>
                    </div>
                  </div> -->
                </div>
              </div>
              <div class="w-full lg:w-1/2">
                <div class="max-w-md lg:mx-auto">
                  <form action="">
                    <div class="mb-4 text-sm">
                      <span class="mr-4 text-2xl font-semibold">Inquiry Now</span>
                      <!-- <label class="mr-4">
                        <input class="mr-1" type="radio" name="department" value="1" checked="">
                        <span>Support</span>
                      </label> -->
                      <!-- <label>
                        <input class="mr-1" type="radio" name="department" value="2">
                        <span>Sales</span>
                      </label> -->
                    </div>
                    <div class="mb-4">
                      <input class="w-full p-4 text-xs font-semibold leading-none bg-white rounded focus:border-red-600" type="text" placeholder="Subject">
                    </div>
                    <div class="mb-4">
                      <input class="w-full p-4 text-xs font-semibold leading-none bg-white rounded focus:border-red-600" type="text" placeholder="Name">
                    </div>
                    <div class="mb-4">
                      <input class="w-full p-4 text-xs font-semibold leading-none bg-white rounded focus:border-red-600" type="email" placeholder="name@example.com">
                    </div>
                    <div class="mb-4"><textarea class="w-full h-24 p-4 text-xs font-semibold leading-none resize-none bg-white rounded focus:border-red-600" type="text" placeholder="Message..."></textarea></div>
                   
                    <div class="flex justify-between items-center">
                      <button class="inline-block py-2 px-6 rounded-l-xl rounded-t-xl bg-red-600 hover:bg-red-700 text-gray-50 font-bold leading-loose transition duration-200">Send Now</button>
                    </div>
                  </form>
                </div>
              </div>
            </div>
          </div>
        </div>
        
      </section>
  </div>
</template>

<script>
export default {
    name: 'Contact-Details'

}
</script>

<style>

</style>