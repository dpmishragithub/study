<template>
  <section>
        
        <div class="py-20 bg-red-50 radius-for-skewed">
          <div class="container mx-auto px-4">
            <div class="mb-16 max-w-md mx-auto text-center">
              <!-- <span class="text-red-600 font-bold">Dolor sit amet consectutar</span> -->
              <h2 class="text-4xl lg:text-5xl font-bold font-heading text-red-700">Popular Courses</h2>
            </div>
            <div class="flex flex-wrap -mx-4">
              <div class="mb-8 lg:mb-0 w-full lg:w-1/3 px-4">
                <div class="py-12 px-6 bg-white rounded shadow-lg text-center transform transition duration-500 hover:scale-105">
                  <span class="mb-6 inline-block p-2 rounded-lg bg-red-100">
                    <svg class="w-10 h-10 text-red-500" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 16l4.586-4.586a2 2 0 012.828 0L16 16m-2-2l1.586-1.586a2 2 0 012.828 0L20 14m-6-6h.01M6 20h12a2 2 0 002-2V6a2 2 0 00-2-2H6a2 2 0 00-2 2v12a2 2 0 002 2z"></path>
                    </svg>
                  </span>
                  <h3 class="px-8 mb-4 text-2xl font-bold font-heading">IIT / JEE</h3>
                  <p class="text-gray-500">Apex Institute give you an excellence in the coaching for three elementary subjects i.e. Physics, Chemistry and Mathematics This course includes Theory Classes to cover the complete syllabus.</p>
                </div>
              </div>
              
              <div class="w-full lg:w-1/3 px-4">
                <div class="py-12 px-6 bg-white rounded shadow-lg text-center transform transition duration-500 hover:scale-105">
                  <span class="mb-6 inline-block p-2 rounded bg-red-100">
                    <svg class="w-10 h-10 text-red-500" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 4v12l-4-2-4 2V4M6 20h12a2 2 0 002-2V6a2 2 0 00-2-2H6a2 2 0 00-2 2v12a2 2 0 002 2z"></path>
                    </svg>
                  </span>
                  <h3 class="px-8 mb-4 text-2xl font-bold font-heading">JEE Main</h3>
                  <p class="text-gray-500">This course is specially designed for class 12th pass students for giving a platform to prepare for JEE Main in a systematic manner. This course includes Theory Classes to cover the complete syllabus.</p>
                </div>
              </div>
              <div class="mb-8 lg:mb-0 w-full lg:w-1/3 px-4">
                <div class="py-12 px-6 bg-white rounded shadow-lg text-center transform transition duration-500 hover:scale-105">
                  <span class="mb-6 inline-block p-2 rounded-lg bg-red-100">
                    <svg class="w-10 h-10 text-red-500" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                      <path d="M3 1a1 1 0 000 2h1.22l.305 1.222a.997.997 0 00.01.042l1.358 5.43-.893.892C3.74 11.846 4.632 14 6.414 14H15a1 1 0 000-2H6.414l1-1H14a1 1 0 00.894-.553l3-6A1 1 0 0017 3H6.28l-.31-1.243A1 1 0 005 1H3zM16 16.5a1.5 1.5 0 11-3 0 1.5 1.5 0 013 0zM6.5 18a1.5 1.5 0 100-3 1.5 1.5 0 000 3z"></path>
                    </svg>
                  </span>
                  <h3 class="px-8 mb-4 text-2xl font-bold font-heading">NEET</h3>
                  <p class="text-gray-500">Apex Institute give you a place to get ready for Pre Medical Test, NEET Exam. With the change in the pattern Medical exams our faculty has already adapted themselves to meet the expectations of thousands of students.</p>
                </div>
              </div>
            </div>
            <div class="justify-center mt-4"><center>
              <nuxt-link to="" class="inline-block py-2 px-6 rounded-l-xl rounded-t-xl bg-red-600 hover:bg-red-700 text-gray-50 font-bold leading-loose outline-none transition duration-200">View More Courses</nuxt-link>
              </center></div>
          </div>
        </div>
        
      </section>
</template>

<script>
export default {
    name: 'Courses',

}
</script>

<style>

</style>