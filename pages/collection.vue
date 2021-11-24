<template>
  <div class=""> 
    
      <section class="overflow-hidden">
        <nav class="relative px-6 py-6 flex justify-between items-center bg-white">
          <a class="text-3xl font-bold leading-none" href="#">
            <img class="h-12" src="@/atis-assets/logo/atis/atis-mono-black.svg" alt="" width="auto">
          </a>
          <div class="lg:hidden">
            <button class="navbar-burger flex items-center text-gray-400 p-3">
              <svg class="block h-4 w-4 fill-current" viewbox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                <title>Mobile menu</title>
                <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path>
              </svg>
            </button>
          </div>
          <ul class="hidden absolute top-1/2 left-1/2 transform -translate-y-1/2 -translate-x-1/2 lg:flex lg:mx-auto lg:flex lg:items-center lg:w-auto lg:space-x-6">
            <li><a class="text-sm text-gray-400 hover:text-gray-500" href="#">Start</a></li>
            <li class="text-gray-300">
              <svg class="w-4 h-4 current-fill" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 5v.01M12 12v.01M12 19v.01M12 6a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2z"></path>
              </svg>
            </li>
            <li><a class="text-sm text-red-600 font-bold" href="#">About Us</a></li>
            <li class="text-gray-300">
              <svg class="w-4 h-4 current-fill" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 5v.01M12 12v.01M12 19v.01M12 6a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2z"></path>
              </svg>
            </li>
            <li><a class="text-sm text-gray-400 hover:text-gray-500" href="#">Services</a></li>
            <li class="text-gray-300">
              <svg class="w-4 h-4 current-fill" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 5v.01M12 12v.01M12 19v.01M12 6a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2z"></path>
              </svg>
            </li>
            <li><a class="text-sm text-gray-400 hover:text-gray-500" href="#">Platform</a></li>
            <li class="text-gray-300">
              <svg class="w-4 h-4 current-fill" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 5v.01M12 12v.01M12 19v.01M12 6a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2z"></path>
              </svg>
            </li>
            <li><a class="text-sm text-gray-400 hover:text-gray-500" href="#">Testimonials</a></li>
          </ul>
          <a class="hidden lg:block py-2 px-6 bg-red-600 hover:bg-red-700 text-sm text-white font-bold rounded-l-xl rounded-t-xl transition duration-200" href="#">Contact Us</a>
        </nav>
        <div class="relative bg-gray-50 pt-20 pb-24 lg:py-40 overflow-hidden">
          <div class="container mx-auto px-4">
            <div class="flex flex-wrap -mx-4">
              <div class="w-full lg:w-1/2 px-4 flex items-center">
                <div class="w-full text-center lg:text-left">
                  <img class="hidden lg:block absolute inset-0 w-full" src="@/atis-assets/background/lines.svg" alt="">
                  <div class="relative max-w-md mx-auto lg:mx-0">
                    <h2 class="mb-3 text-4xl lg:text-5xl font-bold font-heading">
                      <span>Build &amp; Launch without</span>
                      <span class="text-red-600">problems</span>
                    </h2>
                  </div>
                  <div class="relative max-w-sm mx-auto lg:mx-0">
                    <p class="mb-6 text-gray-400 leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque efficitur nisl sodales egestas lobortis.</p>
                    <div><a class="inline-block mb-3 lg:mb-0 lg:mr-3 w-full lg:w-auto py-2 px-6 leading-loose bg-red-600 hover:bg-red-700 text-white font-semibold rounded-l-xl rounded-t-xl transition duration-200" href="#">Get Started</a><a class="inline-block w-full lg:w-auto py-2 px-6 leading-loose font-semibold bg-white hover:bg-gray-50 rounded-l-xl rounded-t-xl transition duration-200" href="#">How it works</a></div>
                  </div>
                </div>
              </div>
              <div class="w-full lg:w-1/2 px-4">
                <img class="lg:absolute top-0 my-12 lg:my-0 h-full w-full lg:w-1/2 rounded-3xl lg:rounded-none object-cover" src="https://images.unsplash.com/photo-1572521165329-b197f9ea3da6?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=1050&amp;q=80" alt="">
              </div>
            </div>
          </div>
        </div>
        <div class="hidden navbar-menu relative z-50">
          <div class="navbar-backdrop fixed inset-0 bg-gray-800 opacity-25"></div>
          <nav class="fixed top-0 left-0 bottom-0 flex flex-col w-5/6 max-w-sm py-6 px-6 bg-white border-r overflow-y-auto">
            <div class="flex items-center mb-8">
              <a class="mr-auto text-3xl font-bold leading-none" href="#">
                <img class="h-10" src="@/atis-assets/logo/atis/atis-mono-black.svg" alt="" width="auto">
              </a>
              <button class="navbar-close">
                <svg class="h-6 w-6 text-gray-400 cursor-pointer hover:text-gray-500" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
                </svg>
              </button>
            </div>
            <div>
              <ul>
                <li class="mb-1"><a class="block p-4 text-sm font-semibold text-gray-400 hover:bg-red-50 hover:text-red-600 rounded" href="#">Start</a></li>
                <li class="mb-1"><a class="block p-4 text-sm font-semibold text-gray-400 hover:bg-red-50 hover:text-red-600 rounded" href="#">About Us</a></li>
                <li class="mb-1"><a class="block p-4 text-sm font-semibold text-gray-400 hover:bg-red-50 hover:text-red-600 rounded" href="#">Services</a></li>
                <li class="mb-1"><a class="block p-4 text-sm font-semibold text-gray-400 hover:bg-red-50 hover:text-red-600 rounded" href="#">Platform</a></li>
                <li class="mb-1"><a class="block p-4 text-sm font-semibold text-gray-400 hover:bg-red-50 hover:text-red-600 rounded" href="#">Testimonials</a></li>
              </ul>
            </div>
            <div class="mt-auto">
              <div class="pt-6"><a class="block px-4 py-3 mb-3 leading-loose text-xs text-center font-semibold leading-none bg-gray-50 hover:bg-gray-100 rounded-l-xl rounded-t-xl" href="#">Sign In</a><a class="block px-4 py-3 mb-2 leading-loose text-xs text-center text-white font-semibold bg-red-600 hover:bg-red-700 rounded-l-xl rounded-t-xl" href="#">Sign Up</a></div>
              <p class="my-4 text-xs text-center text-gray-400">
                <span>&copy; 2020 All rights reserved.</span>
              </p>
              <div class="text-center">
                <a class="inline-block px-1" href="#">
                  <img src="@/atis-assets/social/facebook.svg" alt="">
                </a>
                <a class="inline-block px-1" href="#">
                  <img src="@/atis-assets/social/twitter.svg" alt="">
                </a>
                <a class="inline-block px-1" href="#">
                  <img src="@/atis-assets/social/instagram.svg" alt="">
                </a>
              </div>
            </div>
          </nav>
        </div>
      </section>
    
      <section>
      
        <div class="py-20 bg-gray-50 ">
          <div class="container mx-auto px-4">
            <div class="relative flex">
              <div class="hidden xl:absolute inset-y-0 left-0 -ml-6 xl:flex items-center">
                <button class="p-4 bg-red-600 hover:bg-red-700 rounded-l-xl rounded-t-xl text-white z-10">
                  <svg class="w-4 h-4" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 19l-7-7m0 0l7-7m-7 7h18"></path>
                  </svg>
                </button>
              </div>
              <div class="w-full xl:w-4/5 xl:ml-auto">
                <img class="md:max-w-xl xl:max-w-4xl mx-auto relative object-cover rounded" src="https://images.unsplash.com/photo-1489493512598-d08130f49bea?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=1048&amp;q=80" alt="">
                <div class="xl:hidden mt-12 text-center">
                  <button class="p-4 bg-red-600 hover:bg-red-700 rounded-l-xl rounded-t-xl text-white z-10 transition duration-200">
                    <svg class="w-4 h-4" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 19l-7-7m0 0l7-7m-7 7h18"></path>
                    </svg>
                  </button>
                  <button class="p-4 bg-red-600 hover:bg-red-700 rounded-r-xl rounded-t-xl text-white transition duration-200">
                    <svg class="w-4 h-4" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path>
                    </svg>
                  </button>
                </div>
                <div class="xl:absolute top-0 left-0 mt-12 xl:mt-20 max-w-xl mx-auto xl:mx-0 p-6 xl:py-24 rounded bg-white border-gray-50 shadow text-center">
                  <span class="font-bold text-red-600">Dolor sit amet consectutar</span>
                  <h2 class="text-5xl font-bold font-heading">Build &amp; Launch without problems</h2>
                  <p class="max-w-xs mx-auto text-gray-500 leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque efficitur nisl sodales egestas lobortis.</p>
                </div>
              </div>
              <div class="hidden xl:absolute inset-y-0 right-0 -mr-8 xl:flex items-center">
                <button class="p-4 bg-red-600 hover:bg-red-700 rounded-r-xl rounded-t-xl text-white">
                  <svg class="w-4 h-4" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path>
                  </svg>
                </button>
              </div>
            </div>
          </div>
        </div>
      
      </section>
    
      <section>
        
        <div class="py-20 bg-gray-50 radius-for-skewed">
          <div class="container mx-auto px-4">
            <div class="flex flex-wrap items-center -mx-4">
              <div class="mb-12 lg:mb-0 w-full lg:w-1/2 flex px-4">
                <div class="max-w-md">
                  <span class="text-red-600 font-bold">Dolor sit amet consectutar</span>
                  <h2 class="mb-6 text-4xl lg:text-5xl font-bold font-heading">Build &amp; Launch without problems</h2>
                  <div class="mb-6 max-w-sm">
                    <p class="text-gray-500 leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque efficitur nisl sodales egestas lobortis.</p>
                  </div>
                  <div class="flex flex-wrap lg:-ml-5">
                    <button class="lg:w-auto py-2 px-6 leading-loose lg:ml-5 text-gray-50 font-bold bg-red-600 hover:bg-red-700 transition duration-200 rounded-l-xl rounded-t-xl">Get Started</button>
                  </div>
                </div>
              </div>
              <div class="w-full lg:w-1/2">
                <div class="mb-4 flex flex-wrap items-end">
                  <div class="mb-4 lg:mb-0 w-full lg:w-2/3 px-3">
                    <img class="w-full h-32 lg:h-48 object-cover rounded" src="https://images.unsplash.com/photo-1604701145653-ab3c97c63467?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=634&amp;q=80" alt="">
                  </div>
                  <div class="w-full lg:w-1/3 px-3">
                    <img class="w-full h-32 object-cover rounded" src="https://images.unsplash.com/photo-1521581171443-58a6b508b9ac?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=1050&amp;q=80" alt="">
                  </div>
                </div>
                <div class="flex flex-wrap items-start">
                  <div class="mb-4 lg:mb-0 w-full lg:w-1/3 px-3">
                    <img class="w-full h-32 object-cover rounded" src="https://images.unsplash.com/photo-1501706649056-3cb79cccec52?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=701&amp;q=80" alt="">
                  </div>
                  <div class="w-full lg:w-2/3 px-3">
                    <img class="w-full h-32 lg:h-48 object-cover rounded" src="https://images.unsplash.com/photo-1489058535093-8f530d789c3b?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=1050&amp;q=80" alt="">
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        
      </section>
    
      <!-- <section>
        
        <div class="py-20 bg-gray-50 radius-for-skewed">
          <div class="container mx-auto px-4">
            <div class="mb-16 max-w-md mx-auto text-center">
              <span class="text-red-600 font-bold">Dolor sit amet consectutar</span>
              <h2 class="text-4xl lg:text-5xl font-bold font-heading">Build &amp; Launch without problems</h2>
            </div>
            <div class="flex flex-wrap -mx-4">
              <div class="mb-8 lg:mb-0 w-full lg:w-1/3 px-4">
                <div class="py-12 px-6 bg-white rounded shadow text-center">
                  <span class="mb-6 inline-block p-2 rounded-lg bg-red-100">
                    <svg class="w-10 h-10 text-red-500" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 16l4.586-4.586a2 2 0 012.828 0L16 16m-2-2l1.586-1.586a2 2 0 012.828 0L20 14m-6-6h.01M6 20h12a2 2 0 002-2V6a2 2 0 00-2-2H6a2 2 0 00-2 2v12a2 2 0 002 2z"></path>
                    </svg>
                  </span>
                  <h3 class="px-8 mb-4 text-2xl font-bold font-heading">Lorem ipsum dolor sit amet</h3>
                  <p class="text-gray-500">Fusce quam tellus, placerat eu metus ut, viverra aliquet purus.</p>
                </div>
              </div>
              <div class="mb-8 lg:mb-0 w-full lg:w-1/3 px-4">
                <div class="py-12 px-6 bg-white rounded shadow text-center">
                  <span class="mb-6 inline-block p-2 rounded-lg bg-red-100">
                    <svg class="w-10 h-10 text-red-500" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                      <path d="M3 1a1 1 0 000 2h1.22l.305 1.222a.997.997 0 00.01.042l1.358 5.43-.893.892C3.74 11.846 4.632 14 6.414 14H15a1 1 0 000-2H6.414l1-1H14a1 1 0 00.894-.553l3-6A1 1 0 0017 3H6.28l-.31-1.243A1 1 0 005 1H3zM16 16.5a1.5 1.5 0 11-3 0 1.5 1.5 0 013 0zM6.5 18a1.5 1.5 0 100-3 1.5 1.5 0 000 3z"></path>
                    </svg>
                  </span>
                  <h3 class="px-8 mb-4 text-2xl font-bold font-heading">Ut congue nec leo eget aliquam</h3>
                  <p class="text-gray-500">Ut tempus tellus ac nisi vestibulum tempus. Nunc tincidunt lectus libero.</p>
                </div>
              </div>
              <div class="w-full lg:w-1/3 px-4">
                <div class="py-12 px-6 bg-white rounded shadow text-center">
                  <span class="mb-6 inline-block p-2 rounded bg-red-100">
                    <svg class="w-10 h-10 text-red-500" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 4v12l-4-2-4 2V4M6 20h12a2 2 0 002-2V6a2 2 0 00-2-2H6a2 2 0 00-2 2v12a2 2 0 002 2z"></path>
                    </svg>
                  </span>
                  <h3 class="px-8 mb-4 text-2xl font-bold font-heading">Proin fringilla eleifend justo</h3>
                  <p class="text-gray-500">Donec ut ligula nunc. Mauris blandit vel est et facilisis. Integer sapien felis.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        
      </section> -->
    
      <section>
        
        <div class="py-20 bg-gray-50 radius-for-skewed">
          <div class="container mx-auto px-4">
            <div class="flex flex-wrap items-center -mx-4">
              <div class="mb-12 lg:mb-0 w-full lg:w-1/2 px-4">
                <div class="max-w-md">
                  <span class="text-red-600 font-bold">Dolor sit amet consectutar</span>
                  <h2 class="mb-6 text-4xl lg:text-5xl font-bold font-heading">Build &amp; Launch without problems</h2>
                  <ul>
                    <li class="flex mb-4">
                      <div>
                        <svg class="mr-3 w-8 h-8 text-red-600" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4"></path>
                        </svg>
                      </div>
                      <div class="max-w-xs">
                        <h3 class="font-bold font-heading">Easy to Customize</h3>
                        <p class="text-gray-500 leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                      </div>
                    </li>
                    <li class="flex mb-4">
                      <div>
                        <svg class="mr-3 w-8 h-8 text-red-600" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4"></path>
                        </svg>
                      </div>
                      <div class="max-w-xs">
                        <h3 class="font-bold font-heading">Flexible Software</h3>
                        <p class="text-gray-500 leading-loose">Praesent viverra, nisi at placerat placerat, urna elit viverra magna, varius auctor mauris.</p>
                      </div>
                    </li>
                    <li class="flex">
                      <div>
                        <svg class="mr-3 w-8 h-8 text-red-600" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4"></path>
                        </svg>
                      </div>
                      <div class="max-w-xs">
                        <h3 class="font-bold font-heading">Best access for all of the resources</h3>
                        <p class="text-gray-500 leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                      </div>
                    </li>
                  </ul>
                </div>
              </div>
              <div class="flex flex-wrap items-center w-full lg:w-1/2 px-4">
                <div class="mb-6 w-full lg:w-1/2 px-3">
                  <img class="mb-6 w-full h-64 object-cover rounded-lg" src="https://images.unsplash.com/photo-1472214103451-9374bd1c798e?ixlib=rb-1.2.1&amp;ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;auto=format&amp;fit=crop&amp;w=1050&amp;q=80" alt="">
                  <img class="w-full h-64 object-cover rounded-lg" src="https://images.unsplash.com/photo-1469827160215-9d29e96e72f4?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=1052&amp;q=80" alt="">
                </div>
                <div class="w-full lg:w-1/2 px-3">
                  <img class="w-full h-64 object-cover rounded-lg" src="https://images.unsplash.com/photo-1605201100110-1f07883d2882?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=634&amp;q=80" alt="">
                </div>
              </div>
            </div>
          </div>
        </div>
        
      </section>
    
      <section>
        <div class="flex flex-wrap">
          <div class="pt-6 lg:pt-16 pb-6 w-full lg:w-1/2">
            <div class="max-w-md mx-auto">
              <div class="mb-6 lg:mb-20 w-full px-3 flex items-center justify-between">
                <a class="text-3xl font-bold leading-none" href="#">
                  <img class="h-12" src="@/atis-assets/logo/atis/atis-mono-black.svg" alt="" width="auto">
                </a>
                <a class="py-2 px-6 text-xs rounded-l-xl rounded-t-xl bg-red-100 hover:bg-red-200 text-red-600 font-bold transition duration-200" href="#">Sign In</a>
              </div>
              <div>
                <div class="mb-6 px-3">
                  <span class="text-gray-500">Sign Up</span>
                  <h3 class="text-2xl font-bold">Create an account</h3>
                </div>
                <form action="">
                  <div class="flex flex-wrap">
                    <div class="mb-3 w-full lg:w-1/2 px-2">
                      <input class="w-full p-4 text-xs bg-gray-50 outline-none rounded" type="text" placeholder="First Name">
                    </div>
                    <div class="mb-3 w-full lg:w-1/2 px-2">
                      <input class="w-full p-4 text-xs bg-gray-50 outline-none rounded" type="text" placeholder="Last Name">
                    </div>
                  </div>
                  <div class="mb-3 flex p-4 mx-2 bg-gray-50 rounded">
                    <input class="w-full text-xs bg-gray-50 outline-none" type="email" placeholder="name@email.com">
                    <svg class="h-6 w-6 ml-4 my-auto text-gray-300" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 12a4 4 0 10-8 0 4 4 0 008 0zm0 0v1.5a2.5 2.5 0 005 0V12a9 9 0 10-9 9m4.5-1.206a8.959 8.959 0 01-4.5 1.207"></path>
                    </svg>
                  </div>
                  <div class="mb-6 flex p-4 mx-2 bg-gray-50 rounded">
                    <input class="w-full text-xs bg-gray-50 outline-none" type="password" placeholder="Enter your password">
                    <button>
                      <svg class="h-6 w-6 ml-4 my-auto text-gray-300" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"></path>
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M2.458 12C3.732 7.943 7.523 5 12 5c4.478 0 8.268 2.943 9.542 7-1.274 4.057-5.064 7-9.542 7-4.477 0-8.268-2.943-9.542-7z"></path>
                      </svg>
                    </button>
                  </div>
                  <div class="px-3 text-center">
                    <button class="mb-2 w-full py-4 bg-red-600 hover:bg-red-700 rounded text-sm font-bold text-gray-50 transition duration-200">Sign Up</button>
                    <span class="text-gray-400 text-xs">
                      <span>Already have an account?</span>
                      <a class="text-red-600 hover:underline" href="#">Sign In</a>
                    </span>
                    <p class="mt-16 text-xs text-gray-400"><a class="underline hover:text-gray-500" href="#">Policy privacy</a> and <a class="underline hover:text-gray-500" href="#">Terms of Use</a></p>
                  </div>
                </form>
              </div>
            </div>
          </div>
          <div class="hidden lg:block relative w-full lg:w-1/2">
            <div class="absolute inset-0 bg-gray-800 z-10 opacity-50"></div>
            <img class="absolute inset-0 h-full ml-auto object-cover z-0" src="https://images.unsplash.com/photo-1565120130276-dfbd9a7a3ad7?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=1050&amp;q=80" alt="">
            <div class="absolute bottom-0 inset-x-0 mx-auto mb-12 max-w-xl text-center" style="z-index: 10;">
              <h2 class="mb-2 text-2xl text-white font-bold font-heading">So much more than a business analytics tool</h2>
              <div class="max-w-lg mx-auto mb-6">
                <p class="text-gray-300 leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque efficitur nisl sodales egestas lobortis.</p>
              </div>
              <a class="inline-block py-2 px-6 rounded-t-xl leading-loose rounded-l-xl bg-red-600 hover:bg-red-700 text-gray-50 font-bold transition duration-200" href="#">Get Started</a>
              <div class="mt-12 flex justify-center space-x-3">
                <button class="p-1 bg-gray-500 rounded-full"></button>
                <button class="p-1 bg-gray-500 rounded-full"></button>
                <button class="p-1 bg-red-600 rounded-full"></button>
                <button class="p-1 bg-gray-500 rounded-full"></button>
              </div>
            </div>
          </div>
          <div class="lg:hidden">
            <div class="relative w-full">
              <img class="relative mb-4 object-cover" src="https://images.unsplash.com/photo-1565120130276-dfbd9a7a3ad7?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=1050&amp;q=80" alt="">
              <div class="absolute bottom-0 inset-x-0 mb-10 flex justify-center space-x-3">
                <button class="p-1 bg-gray-500 rounded-full"></button>
                <button class="p-1 bg-gray-500 rounded-full"></button>
                <button class="p-1 bg-red-600 rounded-full"></button>
                <button class="p-1 bg-gray-500 rounded-full"></button>
              </div>
            </div>
            <div class="py-10 px-3 text-center" style="z-index: 10;">
              <h2 class="mb-2 text-2xl font-bold">So much more than a business analytics tool</h2>
              <p class="mb-6 text-gray-500 leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque efficitur nisl sodales egestas lobortis.</p>
              <a class="inline-block py-2 px-6 rounded-t-xl rounded-l-xl bg-red-600 hover:bg-red-700 text-gray-50 font-bold transition duration-200" href="#">Get Started</a>
            </div>
          </div>
        </div>
      </section>
    
      <section>
    
        <div class="py-20 bg-gray-50 overflow-hidden radius-for-skewed">
          <div class="container mx-auto px-4">
            <div class="mb-16 max-w-md text-center mx-auto">
              <span class="text-red-600 font-bold">Dolor sit amet consectutar</span>
              <h2 class="mb-2 text-4xl lg:text-5xl font-bold font-heading">Build &amp; Launch without problems</h2>
            </div>
            <div class="relative flex flex-wrap -mx-4 z-0">
              <img class="h-128 hidden xl:block absolute top-0 right-0 -mt-4 -mr-16" style="z-index: -1;" src="@/atis-assets/elements/line.svg" alt="">
              <div class="mb-10 lg:mb-32 w-full md:w-1/2 lg:w-1/3 px-4">
                <div class="max-w-xs">
                  <span class="mb-4 lg:mb-10 flex w-16 h-16 items-center justify-center bg-red-600 rounded-full font-bold text-white text-2xl">1</span>
                  <h3 class="mb-4 text-2xl font-bold font-heading">Lorem ipsum dolor sit amet consectutar</h3>
                  <p class="text-gray-500 leading-loose">Fusce quam tellus, placerat eu metus ut, viverra aliquet purus. Suspendisse potenti. Nulla non nibh feugiat.</p>
                </div>
              </div>
              <div class="mb-10 lg:mb-32 w-full md:w-1/2 lg:w-1/3 px-4">
                <div class="max-w-xs">
                  <span class="mb-4 lg:mb-10 flex w-16 h-16 items-center justify-center bg-red-600 rounded-full font-bold text-white text-2xl">2</span>
                  <h3 class="mb-4 text-2xl font-bold font-heading">Lorem ipsum dolor sit amet consectutar</h3>
                  <p class="text-gray-500 leading-loose">Fusce quam tellus, placerat eu metus ut, viverra aliquet purus. Suspendisse potenti. Nulla non nibh feugiat.</p>
                </div>
              </div>
              <div class="mb-10 lg:mb-32 w-full md:w-1/2 lg:w-1/3 px-4">
                <div class="max-w-xs">
                  <span class="mb-4 lg:mb-10 flex w-16 h-16 items-center justify-center bg-red-600 rounded-full font-bold text-white text-2xl">3</span>
                  <h3 class="mb-4 text-2xl font-bold font-heading">Lorem ipsum dolor sit amet consectutar</h3>
                  <p class="text-gray-500 leading-loose">Fusce quam tellus, placerat eu metus ut, viverra aliquet purus. Suspendisse potenti. Nulla non nibh feugiat.</p>
                </div>
              </div>
              <div class="mb-10 w-full md:w-1/2 lg:w-1/3 px-4 order-last lg:order-1">
                <div class="max-w-xs">
                  <span class="mb-4 lg:mb-10 flex w-16 h-16 items-center justify-center bg-red-600 rounded-full font-bold text-white text-2xl">6</span>
                  <h3 class="mb-4 text-2xl font-bold font-heading">Lorem ipsum dolor sit amet consectutar</h3>
                  <p class="text-gray-500 leading-loose">Fusce quam tellus, placerat eu metus ut, viverra aliquet purus. Suspendisse potenti. Nulla non nibh feugiat.</p>
                </div>
              </div>
              <div class="mb-10 md:mb-0 w-full md:w-1/2 lg:w-1/3 px-4 order-1 lg:order-0">
                <div class="max-w-xs">
                  <span class="mb-4 lg:mb-10 flex w-16 h-16 items-center justify-center bg-red-600 rounded-full font-bold text-white text-2xl">5</span>
                  <h3 class="mb-4 text-2xl font-bold font-heading">Lorem ipsum dolor sit amet consectutar</h3>
                  <p class="text-gray-500 leading-loose">Fusce quam tellus, placerat eu metus ut, viverra aliquet purus. Suspendisse potenti. Nulla non nibh feugiat.</p>
                </div>
              </div>
              <div class="w-full md:w-1/2 lg:w-1/3 px-4 lg:order-last">
                <div class="max-w-xs">
                  <span class="mb-4 lg:mb-10 flex w-16 h-16 items-center justify-center bg-red-600 rounded-full font-bold text-white text-2xl">4</span>
                  <h3 class="mb-4 text-2xl font-bold font-heading">Lorem ipsum dolor sit amet consectutar</h3>
                  <p class="text-gray-500 leading-loose">Fusce quam tellus, placerat eu metus ut, viverra aliquet purus. Suspendisse potenti. Nulla non nibh feugiat.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
       
      </section>
    
      <section class="pb-20">
        <div class="py-20 mb-12" style="background-image: url('https://images.unsplash.com/photo-1473773508845-188df298d2d1?ixlib=rb-1.2.1&amp;ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;auto=format&amp;fit=crop&amp;w=967&amp;q=80'); background-repeat: no-repeat; background-size: cover;">
          <div class="container mx-auto px-4">
            <div class="max-w-2xl mx-auto text-center">
              <a class="uppercase text-base lg:text-xl text-red-500 hover:text-red-400 hover:underline" href="#">Travel</a>
              <span class="text-base lg:text-xl text-white">24 Jan, 2021</span>
              <div class="mt-2">
                <h2 class="mb-6 text-4xl lg:text-5xl text-white font-bold">Curabitur vestibulum odio maximus ipsum</h2>
                <div class="flex justify-center">
                  <div class="mr-4">
                    <img class="w-12 h-12 object-cover object-top rounded-full" src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=334&amp;q=80" alt="">
                  </div>
                  <div class="text-left">
                    <a href="#">
                      <h3 class="text-white hover:underline font-bold">Alice Bradley</h3>
                    </a>
                    <a href="#">
                      <span class="text-xs text-red-600 font-bold">Author</span>
                    </a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="container mx-auto px-4">
          <div class="max-w-2xl mx-auto">
            <p class="mb-6 leading-loose text-gray-500">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent commodo est eget consequat imperdiet. Suspendisse laoreet scelerisque lobortis. Mauris facilisis hendrerit nulla at vehicula. Suspendisse potenti. Ut in nulla a purus bibendum convallis. Suspendisse id nunc maximus, suscipit ante ac, vulputate massa. Sed ut nunc suscipit, bibendum arcu a, interdum elit. Nullam laoreet mollis dictum. Ut suscipit, magna at elementum iaculis, erat erat fermentum justo, sit amet ultrices enim leo sit amet purus. Nulla sed erat molestie, auctor mauris lobortis, iaculis justo.</p>
            <p class="leading-loose text-gray-500">Duis hendrerit dui in dui ornare luctus. Nullam gravida tincidunt lorem cursus suscipit. Integer scelerisque sem et sem porta, eu volutpat mi tempor. Duis interdum sodales lacus non tempor. Nam mattis, sapien a commodo ultrices, nunc orci tincidunt ante, tempus tempus turpis metus laoreet lacus. Praesent condimentum, arcu ut fringilla tincidunt, augue diam pretium augue, sit amet vestibulum nunc felis vel metus. Duis dolor nulla, pellentesque non ultrices ut, convallis eu felis. Duis luctus tempor arcu, vitae elementum massa porta non. Morbi aliquet, neque ut volutpat sodales, dui enim facilisis enim, ut dictum lacus neque in urna. Nam metus elit, ullamcorper pretium nisi at, aliquet gravida lectus. Nullam id lectus pellentesque, suscipit dolor eget, consequat velit. Pellentesque finibus commodo nisl, id interdum leo. Maecenas aliquam felis justo, ut sagittis nunc maximus ut.</p>
          </div>
        </div>
      </section>
    
      <section>
        
        <div class="py-20 bg-gray-50 radius-for-skewed">
          <div class="container mx-auto px-4">
            <div class="mb-16 max-w-md mx-auto text-center">
              <span class="text-red-600 font-bold">Dolor sit amet consectutar</span>
              <h2 class="text-4xl lg:text-5xl font-bold font-heading">Build &amp; Launch without problems</h2>
            </div>
            <div class="flex flex-wrap -mx-3">
              <div class="mb-6 w-full lg:w-1/2 px-3">
                <div class="p-6 flex flex-wrap bg-white shadow rounded-lg">
                  <div>
                    <span class="mb-4 lg:mb-0 mr-6 inline-block p-3 md:p-5 rounded-lg bg-red-100">
                      <svg class="h-8 w-8 md:w-12 md:h-12 text-red-500" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 16l4.586-4.586a2 2 0 012.828 0L16 16m-2-2l1.586-1.586a2 2 0 012.828 0L20 14m-6-6h.01M6 20h12a2 2 0 002-2V6a2 2 0 00-2-2H6a2 2 0 00-2 2v12a2 2 0 002 2z"></path>
                      </svg>
                    </span>
                  </div>
                  <div class="w-full lg:w-2/3">
                    <h3 class="mb-2 text-2xl font-bold font-heading">Ut congue nec leo eget</h3>
                    <p class="text-gray-500">Donec ut ligula nunc. Mauris blandit vel est et facilisis. Integer sapien felis, aliquet.</p>
                  </div>
                </div>
              </div>
              <div class="mb-6 w-full lg:w-1/2 px-3">
                <div class="p-6 flex flex-wrap bg-white shadow rounded-lg">
                  <div>
                    <span class="mb-4 lg:mb-0 mr-6 inline-block p-3 md:p-5 rounded-lg bg-red-100">
                      <svg class="h-8 w-8 md:w-12 md:h-12 text-red-500" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                        <path d="M3 1a1 1 0 000 2h1.22l.305 1.222a.997.997 0 00.01.042l1.358 5.43-.893.892C3.74 11.846 4.632 14 6.414 14H15a1 1 0 000-2H6.414l1-1H14a1 1 0 00.894-.553l3-6A1 1 0 0017 3H6.28l-.31-1.243A1 1 0 005 1H3zM16 16.5a1.5 1.5 0 11-3 0 1.5 1.5 0 013 0zM6.5 18a1.5 1.5 0 100-3 1.5 1.5 0 000 3z"></path>
                      </svg>
                    </span>
                  </div>
                  <div class="w-full lg:w-2/3">
                    <h3 class="mb-2 text-2xl font-bold font-heading">Lorem ipsum dolor sit amet</h3>
                    <p class="text-gray-500">Donec ut ligula nunc. Mauris blandit vel est et facilisis. Integer sapien felis, aliquet.</p>
                  </div>
                </div>
              </div>
              <div class="mb-6 lg:mb-0 w-full lg:w-1/2 px-3">
                <div class="p-6 flex flex-wrap bg-white shadow rounded-lg">
                  <div>
                    <span class="mb-4 lg:mb-0 mr-6 inline-block p-3 md:p-5 rounded bg-red-100">
                      <svg class="h-8 w-8 md:w-12 md:h-12 text-red-500" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 4v12l-4-2-4 2V4M6 20h12a2 2 0 002-2V6a2 2 0 00-2-2H6a2 2 0 00-2 2v12a2 2 0 002 2z"></path>
                      </svg>
                    </span>
                  </div>
                  <div class="w-full lg:w-2/3">
                    <h3 class="mb-2 text-2xl font-bold font-heading">Morbi sagittis ligula sit</h3>
                    <p class="text-gray-500">Donec ut ligula nunc. Mauris blandit vel est et facilisis. Integer sapien felis, aliquet.</p>
                  </div>
                </div>
              </div>
              <div class="w-full lg:w-1/2 px-3">
                <div class="p-6 flex flex-wrap bg-white shadow rounded-lg">
                  <div>
                    <span class="mb-4 lg:mb-0 mr-6 inline-block p-3 md:p-5 rounded bg-red-100">
                      <svg class="h-8 w-8 md:w-12 md:h-12 text-red-500" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M6 6V5a3 3 0 013-3h2a3 3 0 013 3v1h2a2 2 0 012 2v3.57A22.952 22.952 0 0110 13a22.95 22.95 0 01-8-1.43V8a2 2 0 012-2h2zm2-1a1 1 0 011-1h2a1 1 0 011 1v1H8V5zm1 5a1 1 0 011-1h.01a1 1 0 110 2H10a1 1 0 01-1-1z" clip-rule="evenodd"></path>
                        <path d="M2 13.692V16a2 2 0 002 2h12a2 2 0 002-2v-2.308A24.974 24.974 0 0110 15c-2.796 0-5.487-.46-8-1.308z"></path>
                      </svg>
                    </span>
                  </div>
                  <div class="w-full lg:w-2/3">
                    <h3 class="mb-2 text-2xl font-bold font-heading">Proin fringilla eleifend justo</h3>
                    <p class="text-gray-500">Donec ut ligula nunc. Mauris blandit vel est et facilisis. Integer sapien felis, aliquet.</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        
      </section>
    
      <section>
        
        <div class="py-20 bg-gray-50 radius-for-skewed">
          <div class="container mx-auto px-4">
            <div class="mb-16 max-w-2xl mx-auto text-center">
              <div class="max-w-lg mx-auto">
                <span class="text-red-600 font-bold">Dolor sit amet consectutar</span>
                <h2 class="mb-2 text-4xl lg:text-5xl font-bold font-heading">All the tools you need in one workspace.</h2>
                <p class="mb-8 text-gray-500">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
              </div>
              <div class="flex flex-wrap justify-center">
                <label class="md:mr-4 w-full sm:w-auto flex items-center mr-8 mb-2">
                  <input type="radio" name="billing" value="1">
                  <span class="mx-2 font-semibold">Monthly Billing</span>
                  <span class="inline-flex items-center justify-center w-12 h-10 bg-red-600 text-white font-semibold rounded-lg">$59</span>
                </label>
                <label class="flex w-full sm:w-auto items-center mb-2">
                  <input type="radio" name="billing" value="2">
                  <span class="mx-2 font-semibold">Annual Billing</span>
                  <span class="inline-flex items-center justify-center w-12 h-10 bg-red-600 text-white font-semibold rounded-lg">$99</span>
                </label>
              </div>
            </div>
            <div class="flex flex-wrap bg-white rounded shadow">
              <div class="w-full md:w-1/2 mb-8 md:mb-0">
                <div class="px-6 py-8 lg:px-8 text-center">
                  <span class="text-gray-400">Sign In</span>
                  <h4 class="mb-8 text-2xl font-heading">Finish your payment</h4>
                  <form class="mb-4" action="">
                    <div class="flex mb-4 px-4 bg-gray-50 rounded">
                      <input class="w-full py-4 text-xs placeholder-gray-400 font-semibold leading-none bg-gray-50 focus:outline-none" type="email" placeholder="pat@shuffle.com">
                      <svg class="h-6 w-6 ml-4 my-auto text-gray-300" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 12a4 4 0 10-8 0 4 4 0 008 0zm0 0v1.5a2.5 2.5 0 005 0V12a9 9 0 10-9 9m4.5-1.206a8.959 8.959 0 01-4.5 1.207"></path>
                      </svg>
                    </div>
                    <div class="flex mb-6 px-4 bg-gray-50 rounded">
                      <input class="w-full py-4 text-xs placeholder-gray-400 font-semibold leading-none bg-gray-50 focus:outline-none" type="password" placeholder="Enter your password">
                      <button class="ml-4">
                        <svg class="h-6 w-6 my-auto text-gray-300" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"></path>
                          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M2.458 12C3.732 7.943 7.523 5 12 5c4.478 0 8.268 2.943 9.542 7-1.274 4.057-5.064 7-9.542 7-4.477 0-8.268-2.943-9.542-7z"></path>
                        </svg>
                      </button>
                    </div>
                    <div class="text-left mb-5 text-sm text-gray-400">
                      <label class="flex">
                        <input type="checkbox" name="terms" value="1">
                        <span class="ml-1 text-xs">By signing up, you agree to our <a class="text-red-600 font-bold hover:text-red-700" href="#">Terms,</a><a class="text-red-600 font-bold hover:text-red-700" href="#">Data Policy</a> and <a class="text-red-600 font-bold hover:text-red-700" href="#">Cookies Policy.</a></span>
                      </label>
                    </div>
                    <button class="block w-full p-4 text-center text-white font-bold leading-none bg-red-600 hover:bg-red-700 rounded-l-xl rounded-t-xl transition duration-200">Buy Monthly Supply</button>
                  </form>
                  <p class="text-xs text-gray-400 text-xs">Already have an account? <a class="text-red-600 hover:underline" href="#">Sign In</a></p>
                </div>
              </div>
              <div class="py-10 w-full md:w-1/2 bg-red-600 lg:rounded-r overflow-hidden flex flex-col">
                <img class="w-full md:max-w-xs mx-auto my-auto" src="@/atis-assets/illustrations/men-on-chair-light-green.png" alt="">
                <h3 class="mb-4 max-w-sm mx-auto text-center text-xl text-white">
                  Best for
                  <span class="font-bold">freelance developers</span>
                  who need to save their time.
                </h3>
                <div class="text-center">
                  <button class="inline-block mr-2 w-2 h-2 bg-red-400 rounded-full"></button>
                  <button class="inline-block mr-2 w-2 h-2 bg-red-400 rounded-full"></button>
                  <button class="inline-block mr-2 w-2 h-2 bg-white rounded-full"></button>
                  <button class="inline-block w-2 h-2 bg-red-400 rounded-full"></button>
                </div>
              </div>
            </div>
          </div>
        </div>
       
      </section>
    
      <section>
        
        <div class="py-20 bg-gray-50 radius-for-skewed">
          <div class="container mx-auto px-4">
            <div class="flex flex-wrap items-center">
              <div class="w-full lg:w-1/2 mb-12 lg:mb-0">
                <div class="max-w-md lg:mx-auto">
                  <span class="text-red-600 font-bold">Dolor sit amet consectutar</span>
                  <h2 class="my-2 text-4xl lg:text-5xl font-bold font-heading">Build &amp; Launch without problems</h2>
                  <p class="mb-6 text-gray-500 leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque efficitur nisl sodales egestas lobortis.</p>
                  <ul class="text-gray-500 font-bold">
                    <li class="flex mb-4">
                      <svg class="mr-2 w-6 h-6 text-red-400" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                      </svg>
                      <span>Vestibulum viverra ante non libero</span>
                    </li>
                    <li class="flex mb-4">
                      <svg class="mr-2 w-6 h-6 text-red-400" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                      </svg>
                      <span>Morbi mollis metus pretium ultrices tincidunt</span>
                    </li>
                    <li class="flex mb-4">
                      <svg class="mr-2 w-6 h-6 text-red-400" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                      </svg>
                      <span>Etiam lectus nunc, commodo et risus in</span>
                    </li>
                  </ul>
                </div>
              </div>
              <div class="w-full lg:w-1/2 flex flex-wrap -mx-4">
                <div class="mb-8 lg:mb-0 w-full md:w-1/2 px-4">
                  <div class="mb-8 py-6 pl-6 pr-4 shadow rounded bg-white">
                    <span class="mb-4 inline-block p-3 rounded-lg bg-red-100">
                      <svg class="w-10 h-10 text-red-600" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 16l4.586-4.586a2 2 0 012.828 0L16 16m-2-2l1.586-1.586a2 2 0 012.828 0L20 14m-6-6h.01M6 20h12a2 2 0 002-2V6a2 2 0 00-2-2H6a2 2 0 00-2 2v12a2 2 0 002 2z"></path>
                      </svg>
                    </span>
                    <h4 class="mb-2 text-2xl font-bold font-heading">Lorem ipsum dolor sit amet</h4>
                    <p class="text-gray-500 leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                  </div>
                  <div class="py-6 pl-6 pr-4 shadow rounded bg-white">
                    <span class="mb-4 inline-block p-3 rounded-lg bg-red-100">
                      <svg class="w-10 h-10 text-red-600" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                        <path d="M3 1a1 1 0 000 2h1.22l.305 1.222a.997.997 0 00.01.042l1.358 5.43-.893.892C3.74 11.846 4.632 14 6.414 14H15a1 1 0 000-2H6.414l1-1H14a1 1 0 00.894-.553l3-6A1 1 0 0017 3H6.28l-.31-1.243A1 1 0 005 1H3zM16 16.5a1.5 1.5 0 11-3 0 1.5 1.5 0 013 0zM6.5 18a1.5 1.5 0 100-3 1.5 1.5 0 000 3z"></path>
                      </svg>
                    </span>
                    <h4 class="mb-2 text-2xl font-bold font-heading">Lorem ipsum dolor sit amet</h4>
                    <p class="text-gray-500 leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                  </div>
                </div>
                <div class="w-full md:w-1/2 lg:mt-20 px-4">
                  <div class="mb-8 py-6 pl-6 pr-4 shadow rounded-lg bg-white">
                    <span class="mb-4 inline-block p-3 rounded bg-red-100">
                      <svg class="w-10 h-10 text-red-600" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 4v12l-4-2-4 2V4M6 20h12a2 2 0 002-2V6a2 2 0 00-2-2H6a2 2 0 00-2 2v12a2 2 0 002 2z"></path>
                      </svg>
                    </span>
                    <h4 class="mb-2 text-2xl font-bold font-heading">Lorem ipsum dolor sit amet</h4>
                    <p class="text-gray-500 leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                  </div>
                  <div class="py-6 pl-6 pr-4 shadow rounded-lg bg-white">
                    <span class="mb-4 inline-block p-3 rounded bg-red-100">
                      <svg class="w-10 h-10 text-red-600" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M6 6V5a3 3 0 013-3h2a3 3 0 013 3v1h2a2 2 0 012 2v3.57A22.952 22.952 0 0110 13a22.95 22.95 0 01-8-1.43V8a2 2 0 012-2h2zm2-1a1 1 0 011-1h2a1 1 0 011 1v1H8V5zm1 5a1 1 0 011-1h.01a1 1 0 110 2H10a1 1 0 01-1-1z" clip-rule="evenodd"></path>
                        <path d="M2 13.692V16a2 2 0 002 2h12a2 2 0 002-2v-2.308A24.974 24.974 0 0110 15c-2.796 0-5.487-.46-8-1.308z"></path>
                      </svg>
                    </span>
                    <h4 class="mb-2 text-2xl font-bold font-heading">Lorem ipsum dolor sit amet</h4>
                    <p class="text-gray-500 leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
       
      </section>
    
      <section>
       
        <div class="py-20 bg-gray-50 radius-for-skewed">
          <div class="container px-4 mx-auto">
            <div class="mb-16 max-w-2xl mx-auto text-center">
              <div class="max-w-lg mx-auto">
                <span class="text-red-600 font-bold">Dolor sit amet consectutar</span>
                <h2 class="mb-2 text-4xl lg:text-5xl font-bold font-heading">All the tools you need in one workspace.</h2>
                <p class="mb-6 text-gray-500">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
              </div>
              <div class="inline-block py-1 px-1 bg-white rounded-lg">
                <button class="mr-1 text-sm py-2 px-4 text-gray-500 hover:text-gray-900 font-bold">Monthly</button>
                <button class="text-sm py-2 px-4 text-gray-900 bg-gray-50 rounded-lg shadow font-bold">Yearly</button>
              </div>
            </div>
            <div class="flex flex-wrap -mx-4">
              <div class="w-full md:w-1/2 lg:w-1/3 px-4 mb-8 lg:mb-0">
                <div class="p-8 bg-white shadow rounded text-center">
                  <h4 class="mb-2 text-2xl font-bold font-heading">Beginner</h4>
                  <span class="text-6xl font-bold">Free</span>
                  <ul class="my-6 text-gray-500">
                    <li class="mb-2">Vestibulum viverra</li>
                    <li class="mb-2">Morbi mollis metus pretium</li>
                    <li class="mb-2">Etiam lectus nunc, commodo</li>
                  </ul>
                  <a class="block text-center py-2 px-4 w-full rounded-l-xl rounded-t-xl bg-red-600 hover:bg-red-700 text-white font-bold leading-loose transition duration-200" href="#">Get Started</a>
                </div>
              </div>
              <div class="w-full md:w-1/2 lg:w-1/3 px-4 mb-8 lg:mb-0">
                <div class="p-8 bg-red-600 shadow rounded text-center">
                  <h4 class="mb-2 text-2xl font-bold text-white">Intermediate</h4>
                  <span class="text-6xl font-bold text-white">$24</span>
                  <span class="text-gray-50 text-xs">/month</span>
                  <ul class="my-6 text-gray-50 text-center">
                    <li class="mb-2">Vestibulum viverra</li>
                    <li class="mb-2">Morbi mollis metus pretium</li>
                    <li class="mb-2">Etiam lectus nunc, commodo</li>
                  </ul>
                  <a class="block text-center py-2 px-4 w-full rounded-l-xl rounded-t-xl bg-white hover:bg-gray-50 font-bold leading-loose transition duration-200" href="#">Get Started</a>
                </div>
              </div>
              <div class="w-full lg:w-1/3 px-4 lg:mb-0">
                <div class="p-8 bg-white shadow rounded text-center">
                  <h4 class="mb-2 text-2xl font-bold font-heading">Professional</h4>
                  <span class="text-6xl font-bold">$48</span>
                  <span class="text-gray-400 text-xs">/month</span>
                  <ul class="my-6 text-gray-500">
                    <li class="mb-2">Vestibulum viverra</li>
                    <li class="mb-2">Morbi mollis metus pretium</li>
                    <li class="mb-2">Etiam lectus nunc, commodo</li>
                  </ul>
                  <a class="block text-center py-2 px-4 w-full rounded-l-xl rounded-t-xl bg-red-600 hover:bg-red-700 text-white font-bold leading-loose transition duration-200" href="#">Get Started</a>
                </div>
              </div>
            </div>
          </div>
        </div>
       
      </section>
    
      <section>
        
        <div class="py-20 bg-gray-50 radius-for-skewed">
          <div class="container mx-auto px-4">
            <div class="max-w-2xl mx-auto text-center mb-16">
              <span class="text-red-600 font-bold">Dolor sit amet consectutar</span>
              <h2 class="mb-2 text-4xl lg:text-5xl font-bold font-heading">Choose your best plan</h2>
              <p class="mb-6 text-gray-500">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
              <div class="inline-block py-1 px-1 bg-white rounded-lg">
                <button class="mr-1 text-sm py-2 px-4 text-gray-500 hover:text-gray-900 font-bold">Monthly</button>
                <button class="text-sm py-2 px-4 text-gray-900 bg-gray-50 rounded-lg shadow font-bold">Yearly</button>
              </div>
            </div>
            <div class="flex flex-wrap -mx-4">
              <div class="w-full md:w-1/2 lg:w-1/3 px-4 mb-8 lg:mb-0">
                <div class="p-8 bg-white shadow rounded">
                  <h4 class="mb-2 text-2xl font-bold font-heading">Beginner</h4>
                  <span class="text-6xl font-bold">Free</span>
                  <p class="mt-3 mb-6 text-gray-500 leading-loose">Nullam diam arcu, sodales quis convallis sit amet, sagittis varius ligula.</p>
                  <ul class="mb-6 text-gray-500">
                    <li class="mb-2 flex">
                      <svg class="mr-2 w-5 h-5 text-red-600" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                      </svg>
                      <span>Vestibulum viverra</span>
                    </li>
                    <li class="mb-2 flex">
                      <svg class="mr-2 w-5 h-5 text-red-600" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                      </svg>
                      <span>Morbi mollis metus pretium</span>
                    </li>
                    <li class="mb-2 flex">
                      <svg class="mr-2 w-5 h-5 text-red-600" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                      </svg>
                      <span>Etiam lectus nunc, commodo</span>
                    </li>
                    <li class="mb-2 flex">
                      <svg class="mr-2 w-5 h-5 text-red-600" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                      </svg>
                      <span>Ut quam nisl mollis id pretium</span>
                    </li>
                    <li class="mb-2 flex">
                      <svg class="mr-2 w-5 h-5 text-red-600" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                      </svg>
                      <span>Suspendisse bibendum</span>
                    </li>
                  </ul>
                  <a class="inline-block text-center py-2 px-4 w-full rounded-l-xl rounded-t-xl bg-red-600 hover:bg-red-700 text-white font-bold leading-loose transition duration-200" href="#">Get Started</a>
                </div>
              </div>
              <div class="w-full md:w-1/2 lg:w-1/3 px-4 mb-8 lg:mb-0">
                <div class="p-8 bg-red-600 shadow rounded">
                  <h4 class="mb-2 text-2xl font-bold text-white">Intermediate</h4>
                  <span class="text-6xl font-bold text-white">$24</span>
                  <span class="text-gray-50 text-xs">/month</span>
                  <p class="mt-3 mb-6 leading-loose text-gray-50">Nullam diam arcu, sodales quis convallis sit amet, sagittis varius ligula.</p>
                  <ul class="mb-6 text-gray-50">
                    <li class="mb-2 flex">
                      <svg class="mr-2 w-5 h-5 text-red-400" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                      </svg>
                      <span>Vestibulum viverra</span>
                    </li>
                    <li class="mb-2 flex">
                      <svg class="mr-2 w-5 h-5 text-red-400" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                      </svg>
                      <span>Morbi mollis metus pretium</span>
                    </li>
                    <li class="mb-2 flex">
                      <svg class="mr-2 w-5 h-5 text-red-400" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                      </svg>
                      <span>Etiam lectus nunc, commodo</span>
                    </li>
                    <li class="mb-2 flex">
                      <svg class="mr-2 w-5 h-5 text-red-400" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                      </svg>
                      <span>Ut quam nisl mollis id pretium</span>
                    </li>
                    <li class="mb-2 flex">
                      <svg class="mr-2 w-5 h-5 text-red-400" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                      </svg>
                      <span>Suspendisse bibendum</span>
                    </li>
                  </ul>
                  <a class="inline-block text-center py-2 px-4 w-full rounded-l-xl rounded-t-xl bg-white hover:bg-gray-50 font-bold leading-loose transition duration-200" href="#">Get Started</a>
                </div>
              </div>
              <div class="w-full lg:w-1/3 px-4">
                <div class="p-8 bg-white shadow rounded">
                  <h4 class="mb-2 text-2xl font-bold font-heading">Professional</h4>
                  <span class="text-6xl font-bold">$48</span>
                  <span class="text-gray-400 text-xs">/month</span>
                  <p class="mt-3 mb-6 text-gray-500 leading-loose">Nullam diam arcu, sodales quis convallis sit amet, sagittis varius ligula.</p>
                  <ul class="mb-6 text-gray-500">
                    <li class="mb-2 flex">
                      <svg class="mr-2 w-5 h-5 text-red-600" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                      </svg>
                      <span>Vestibulum viverra</span>
                    </li>
                    <li class="mb-2 flex">
                      <svg class="mr-2 w-5 h-5 text-red-600" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                      </svg>
                      <span>Morbi mollis metus pretium</span>
                    </li>
                    <li class="mb-2 flex">
                      <svg class="mr-2 w-5 h-5 text-red-600" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                      </svg>
                      <span>Etiam lectus nunc, commodo</span>
                    </li>
                    <li class="mb-2 flex">
                      <svg class="mr-2 w-5 h-5 text-red-600" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                      </svg>
                      <span>Ut quam nisl mollis id pretium</span>
                    </li>
                    <li class="mb-2 flex">
                      <svg class="mr-2 w-5 h-5 text-red-600" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                      </svg>
                      <span>Suspendisse bibendum</span>
                    </li>
                  </ul>
                  <a class="inline-block text-center py-2 px-4 w-full rounded-l-xl rounded-t-xl bg-red-600 hover:bg-red-700 text-white font-bold leading-loose transition duration-200" href="#">Get Started</a>
                </div>
              </div>
            </div>
          </div>
        </div>
        
      </section>
    
      <section class="py-20">
        <div class="container mx-auto px-4">
          <div class="flex flex-wrap items-center">
            <div class="mb-12 lg:mb-0 w-full lg:w-1/2">
              <div class="max-w-md">
                <h2 class="mb-4 text-4xl lg:text-5xl font-bold font-heading">Trusted by brands all over the world</h2>
                <p class="text-gray-500 leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque efficitur nisl sodales egestas lobortis.</p>
              </div>
            </div>
            <div class="w-full lg:w-1/2 flex flex-wrap -mx-2">
              <div class="mb-4 w-full lg:w-1/3 px-2">
                <div class="py-16 bg-gray-50 rounded">
                  <img class="mx-auto h-6" src="@/atis-assets/logo/brands/slack.png" alt="">
                </div>
              </div>
              <div class="mb-4 w-full lg:w-1/3 px-2">
                <div class="py-16 bg-gray-50 rounded">
                  <img class="mx-auto h-6" src="@/atis-assets/logo/brands/dropbox.png" alt="">
                </div>
              </div>
              <div class="mb-4 w-full lg:w-1/3 px-2">
                <div class="py-16 bg-gray-50 rounded">
                  <img class="mx-auto h-6" src="@/atis-assets/logo/brands/spotify.png" alt="">
                </div>
              </div>
              <div class="mb-4 w-full lg:w-1/3 px-2">
                <div class="py-16 bg-gray-50 rounded">
                  <img class="mx-auto h-6" src="@/atis-assets/logo/brands/amazon.png" alt="">
                </div>
              </div>
              <div class="mb-4 w-full lg:w-1/3 px-2">
                <div class="py-16 bg-gray-50 rounded">
                  <img class="mx-auto h-6" src="@/atis-assets/logo/brands/netflix.png" alt="">
                </div>
              </div>
              <div class="w-full lg:w-1/3 px-2">
                <div class="py-16 bg-gray-50 rounded">
                  <img class="mx-auto h-6" src="@/atis-assets/logo/brands/stripe.png" alt="">
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    
      <section>
        
        <div class="py-20 bg-gray-50 radius-for-skewed">
          <div class="container mx-auto px-4">
            <div class="mb-6 flex flex-wrap justify-center">
              <div class="mb-16 w-full text-center">
                <span class="text-red-600 font-bold">Dolor sit amet consectutar</span>
                <h2 class="text-4xl lg:text-5xl font-bold font-heading">Our Blog</h2>
              </div>
              <div class="flex flex-wrap -mx-3 mb-16">
                <div class="mb-6 lg:mb-0 w-full lg:w-1/2 px-3">
                  <div class="h-full flex flex-col rounded shadow">
                    <img class="rounded-t object-cover h-80 lg:h-full w-full" src="https://images.unsplash.com/photo-1559827291-72ee739d0d9a?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=968&amp;q=80" alt="">
                    <div class="mt-auto p-6 rounded-b bg-white">
                      <span class="text-sm text-gray-400">24 Jan, 2021</span>
                      <h2 class="my-2 text-2xl font-bold">Morbi scelerisque nulla et lectus dignissim eleifend nulla eu nulla a metus</h2>
                      <p class="mb-6 text-gray-400 leading-loose">Quisque id sagittis turpis. Nulla sollicitudin rutrum eros eu dictum. Integer sit amet erat sit amet lectus lacinia mattis. Donec est tortor, fermentum at urna a, accumsan suscipit sem.</p>
                      <a class="text-red-600 hover:text-red-700 font-bold" href="#">Learn More</a>
                    </div>
                  </div>
                </div>
                <div class="flex flex-wrap w-full lg:w-1/2">
                  <div class="mb-6 w-full lg:w-1/2 px-3">
                    <div class="rounded overflow-hidden shadow">
                      <img class="lg:h-48 rounded-t" src="https://images.unsplash.com/photo-1413752362258-7af2a667b590?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=1055&amp;q=80" alt="">
                      <div class="p-6 rounded-b bg-white">
                        <span class="text-sm text-gray-400">24 Jan, 2021</span>
                        <h2 class="my-2 text-2xl font-bold">Morbi scelerisque nulla et lectus</h2>
                        <a class="text-red-600 hover:text-red-700 font-bold" href="#">Learn More</a>
                      </div>
                    </div>
                  </div>
                  <div class="mb-6 w-full lg:w-1/2 px-3">
                    <div class="rounded overflow-hidden shadow">
                      <img class="lg:h-48 rounded-t" src="https://images.unsplash.com/photo-1459213599465-03ab6a4d5931?ixlib=rb-1.2.1&amp;ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;auto=format&amp;fit=crop&amp;w=1055&amp;q=80" alt="">
                      <div class="p-6 rounded-b bg-white">
                        <span class="text-sm text-gray-400">24 Jan, 2021</span>
                        <h2 class="my-2 text-2xl font-bold">Morbi scelerisque nulla et lectus</h2>
                        <a class="text-red-600 hover:text-red-700 font-bold" href="#">Learn More</a>
                      </div>
                    </div>
                  </div>
                  <div class="mb-6 w-full lg:w-1/2 px-3">
                    <div class="rounded overflow-hidden shadow">
                      <img class="lg:h-48 rounded-t" src="https://images.unsplash.com/photo-1459213599465-03ab6a4d5931?ixlib=rb-1.2.1&amp;ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;auto=format&amp;fit=crop&amp;w=1055&amp;q=80" alt="">
                      <div class="p-6 rounded-b bg-white">
                        <span class="text-sm text-gray-400">24 Jan, 2021</span>
                        <h2 class="my-2 text-2xl font-bold">Morbi scelerisque nulla et lectus</h2>
                        <a class="text-red-600 hover:text-red-700 font-bold" href="#">Learn More</a>
                      </div>
                    </div>
                  </div>
                  <div class="mb-6 w-full lg:w-1/2 px-3">
                    <div class="rounded overflow-hidden shadow">
                      <img class="lg:h-48 rounded-t" src="https://images.unsplash.com/photo-1413752362258-7af2a667b590?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=1055&amp;q=80" alt="">
                      <div class="p-6 rounded-b bg-white">
                        <span class="text-sm text-gray-400">24 Jan, 2021</span>
                        <h2 class="my-2 text-2xl font-bold">Morbi scelerisque nulla et lectus</h2>
                        <a class="text-red-600 hover:text-red-700 font-bold" href="#">Learn More</a>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div><a class="inline-block py-2 px-6 rounded-l-xl rounded-t-xl bg-red-600 hover:bg-red-700 text-gray-50 font-bold leading-loose outline-none transition duration-200" href="#">View More Articles</a></div>
            </div>
          </div>
        </div>
       
      </section>
    
      <section class="py-10 lg:py-20">
        <div class="container mx-auto px-4">
          <div class="max-w-2xl mx-auto">
            <div class="flex flex-wrap -mx-6">
              <div class="mb-6 w-full lg:w-1/2 px-6">
                <h2 class="mb-6 text-2xl font-bold">Lorem ipsum dolor sit amet consectutar</h2>
                <p class="text-gray-500 leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent commodo est eget consequat imperdiet. Suspendisse laoreet scelerisque lobortis. Mauris facilisis hendrerit nulla at vehicula. Suspendisse potenti. Ut in nulla a purus bibendum convallis.</p>
              </div>
              <div class="w-full lg:w-1/2 px-6 h-80">
                <img class="h-full mx-auto object-cover rounded-lg" src="https://images.unsplash.com/photo-1473773508845-188df298d2d1?ixlib=rb-1.2.1&amp;ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;auto=format&amp;fit=crop&amp;w=967&amp;q=80" alt="">
              </div>
            </div>
          </div>
        </div>
      </section>
    
      <section class="py-20">
        <div class="container mx-auto px-4">
          <div class="max-w-2xl mx-auto">
            <h2 class="mb-16 text-3xl lg:text-4xl font-bold font-heading">Pellentesque finibus commodo nisl, id interdum leo. Maecenas aliquam felis justo, ut sagittis nunc maximus ut.</h2>
            <div class="mb-8 flex justify-center items-start">
              <div class="mb-4 mr-6 py-4 px-6 rounded text-red-500 bg-red-50 font-bold">1</div>
              <div>
                <h3 class="mb-4 text-xl lg:text-2xl font-bold">Lorem ipsum dolor sit amet consectutar</h3>
                <p class="text-gray-500 leading-loose">Nam mattis, sapien a commodo ultrices, nunc orci tincidunt ante, tempus tempus turpis metus laoreet lacus. Praesent condimentum, arcu ut fringilla tincidunt, augue diam pretium augue, sit amet vestibulum nunc felis vel metus.</p>
              </div>
            </div>
            <div class="mb-8 flex justify-center items-start">
              <div class="mb-4 mr-6 py-4 px-6 rounded text-red-500 bg-red-50 font-bold">2</div>
              <div>
                <h3 class="mb-4 text-xl lg:text-2xl font-bold">Lorem ipsum dolor sit amet consectutar</h3>
                <p class="text-gray-500 leading-loose">Nam mattis, sapien a commodo ultrices, nunc orci tincidunt ante, tempus tempus turpis metus laoreet lacus. Praesent condimentum, arcu ut fringilla tincidunt, augue diam pretium augue, sit amet vestibulum nunc felis vel metus.</p>
              </div>
            </div>
            <div class="flex justify-center items-start">
              <div class="mb-4 mr-6 py-4 px-6 rounded text-red-500 bg-red-50 font-bold">3</div>
              <div>
                <h3 class="mb-4 text-xl lg:text-2xl font-bold">Lorem ipsum dolor sit amet consectutar</h3>
                <p class="text-gray-500 leading-loose">Nam mattis, sapien a commodo ultrices, nunc orci tincidunt ante, tempus tempus turpis metus laoreet lacus. Praesent condimentum, arcu ut fringilla tincidunt, augue diam pretium augue, sit amet vestibulum nunc felis vel metus.</p>
              </div>
            </div>
          </div>
        </div>
      </section>
    
      <section class="py-20">
        <div class="container mx-auto px-4">
          <div class="max-w-2xl mx-auto">
            <img class="mb-12 rounded object-cover mx-auto" src="https://images.unsplash.com/photo-1473773508845-188df298d2d1?ixlib=rb-1.2.1&amp;ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;auto=format&amp;fit=crop&amp;w=967&amp;q=80" alt="">
            <h2 class="mb-12 text-3xl lg:text-4xl font-bold font-heading">Pellentesque finibus commodo nisl, id interdum leo. Maecenas aliquam felis justo, ut sagittis nunc maximus ut.</h2>
            <div class="mb-12">
              <h3 class="mb-4 text-2xl font-bold font-heading">Maecenas aliquam felis dolor sit amet</h3>
              <p class="text-gray-500 leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent commodo est eget consequat imperdiet. Suspendisse laoreet scelerisque lobortis. Mauris facilisis hendrerit nulla at vehicula. Suspendisse potenti. Ut in nulla a purus bibendum convallis. Suspendisse id nunc maximus, suscipit ante ac, vulputate massa. Sed ut nunc suscipit, bibendum arcu a, interdum elit. Nullam laoreet mollis dictum. Ut suscipit, magna at elementum iaculis, erat erat fermentum justo, sit amet ultrices enim leo sit amet purus. Nulla sed erat molestie, auctor mauris lobortis, iaculis justo.</p>
            </div>
            <div>
              <h3 class="mb-4 text-2xl font-bold font-heading">Maecenas aliquam felis dolor sit amet</h3>
              <p class="text-gray-500 leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent commodo est eget consequat imperdiet. Suspendisse laoreet scelerisque lobortis. Mauris facilisis hendrerit nulla at vehicula. Suspendisse potenti. Ut in nulla a purus bibendum convallis. Suspendisse id nunc maximus, suscipit ante ac, vulputate massa. Sed ut nunc suscipit, bibendum arcu a, interdum elit. Nullam laoreet mollis dictum. Ut suscipit, magna at elementum iaculis, erat erat fermentum justo, sit amet ultrices enim leo sit amet purus. Nulla sed erat molestie, auctor mauris lobortis, iaculis justo.</p>
            </div>
          </div>
        </div>
      </section>
    
      <section>
        
        <div class="py-20 bg-gray-50 radius-for-skewed">
          <div class="container mx-auto px-4">
            <div class="mb-16 flex flex-wrap items-center">
              <div class="w-full lg:w-1/2">
                <span class="text-red-600 font-bold">Dolor sit amet consectutar</span>
                <h2 class="text-4xl lg:text-5xl font-bold font-heading">Featured Posts</h2>
              </div>
              <div class="hidden lg:block text-right w-1/2"><a class="inline-block py-2 px-6 rounded-l-xl rounded-t-xl bg-red-600 hover:bg-red-700 text-gray-50 font-bold leading-loose transition duration-200" href="#">View More Articles</a></div>
            </div>
            <div class="flex flex-wrap -mx-3">
              <div class="mb-8 lg:mb-0 w-full lg:w-1/4 px-3">
                <div class="py-4 px-6 bg-white shadow rounded">
                  <h4 class="mb-4 text-gray-500 font-bold uppercase">Topics</h4>
                  <ul>
                    <li><a class="block py-2 px-3 mb-4 rounded text-red-600 font-bold bg-gray-50" href="#">All</a></li>
                    <li><a class="block py-2 px-3 mb-4 rounded hover:text-red-600 hover:bg-gray-50" href="#">Community</a></li>
                    <li><a class="block py-2 px-3 mb-4 rounded hover:text-red-600 hover:bg-gray-50" href="#">Design</a></li>
                    <li><a class="block py-2 px-3 mb-4 rounded hover:text-red-600 hover:bg-gray-50" href="#">Engineering</a></li>
                    <li><a class="block py-2 px-3 mb-4 rounded hover:text-red-600 hover:bg-gray-50" href="#">Marketplace</a></li>
                    <li><a class="block py-2 px-3 mb-4 rounded hover:text-red-600 hover:bg-gray-50" href="#">News</a></li>
                    <li><a class="block py-2 px-3 mb-4 rounded hover:text-red-600 hover:bg-gray-50" href="#">Culture</a></li>
                    <li><a class="block py-2 px-3 mb-4 rounded hover:text-red-600 hover:bg-gray-50" href="#">Product Updates</a></li>
                    <li><a class="block py-2 px-3 mb-4 rounded hover:text-red-600 hover:bg-gray-50" href="#">Trust &amp; Security</a></li>
                  </ul>
                </div>
              </div>
              <div class="w-full lg:w-3/4 px-3">
                <div class="flex flex-wrap -mx-3 mb-8 lg:mb-6">
                  <div class="mb-4 lg:mb-0 w-full lg:w-1/4 px-3">
                    <img class="w-full h-full object-cover rounded" src="https://images.unsplash.com/photo-1552338804-c42590cb7b88?ixlib=rb-1.2.1&amp;ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;auto=format&amp;fit=crop&amp;w=1189&amp;q=80" alt="">
                  </div>
                  <div class="w-full lg:w-3/4 px-3">
                    <a class="hover:underline" href="#">
                      <h3 class="mb-1 text-2xl font-bold font-heading">Morbi scelerisque nulla et lectus dignissim eleifend nulla eu nulla a metus</h3>
                    </a>
                    <div class="mb-2 flex items-center text-sm">
                      <a class="text-red-600 hover:underline hover:text-red-700" href="#">John Doe</a>
                      <span class="text-gray-400 mx-2">&bull;</span>
                      <span class="text-gray-400">24 Jan, 2021</span>
                    </div>
                    <p class="text-gray-500">Quisque id sagittis turpis. Nulla sollicitudin rutrum eros eu dictum...</p>
                  </div>
                </div>
                <div class="flex flex-wrap -mx-3 mb-8 lg:mb-6">
                  <div class="mb-4 lg:mb-0 w-full lg:w-1/4 px-3">
                    <img class="w-full h-full object-cover rounded" src="https://images.unsplash.com/photo-1578509395623-a34c97f15379?ixlib=rb-1.2.1&amp;ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;auto=format&amp;fit=crop&amp;w=968&amp;q=80" alt="">
                  </div>
                  <div class="w-full lg:w-3/4 px-3">
                    <a class="hover:underline" href="#">
                      <h3 class="mb-1 text-2xl font-bold font-heading">Morbi scelerisque nulla et lectus dignissim eleifend nulla eu nulla a metus</h3>
                    </a>
                    <div class="mb-2 flex items-center text-sm">
                      <a class="text-red-600 hover:underline hover:text-red-700" href="#">John Doe</a>
                      <span class="text-gray-400 mx-2">&bull;</span>
                      <span class="text-gray-400">24 Jan, 2021</span>
                    </div>
                    <p class="text-gray-500">Quisque id sagittis turpis. Nulla sollicitudin rutrum eros eu dictum...</p>
                  </div>
                </div>
                <div class="flex flex-wrap -mx-3 mb-8 lg:mb-6">
                  <div class="mb-4 lg:mb-0 w-full lg:w-1/4 px-3">
                    <img class="w-full h-full object-cover rounded" src="https://images.unsplash.com/photo-1551008475-4533d141425b?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=968&amp;q=80" alt="">
                  </div>
                  <div class="w-full lg:w-3/4 px-3">
                    <a class="hover:underline" href="#">
                      <h3 class="mb-1 text-2xl font-bold font-heading">Morbi scelerisque nulla et lectus dignissim eleifend nulla eu nulla a metus</h3>
                    </a>
                    <div class="mb-2 flex items-center text-sm">
                      <a class="text-red-600 hover:underline hover:text-red-700" href="#">John Doe</a>
                      <span class="text-gray-400 mx-2">&bull;</span>
                      <span class="text-gray-400">24 Jan, 2021</span>
                    </div>
                    <p class="text-gray-500">Quisque id sagittis turpis. Nulla sollicitudin rutrum eros eu dictum...</p>
                  </div>
                </div>
                <div class="flex flex-wrap -mx-3 mb-8 lg:mb-6">
                  <div class="mb-4 lg:mb-0 w-full lg:w-1/4 px-3">
                    <img class="w-full h-full object-cover rounded" src="https://images.unsplash.com/37/IHLjdHdzSvi0rgUMMlSK_TE3_0286.jpg?ixlib=rb-1.2.1&amp;ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;auto=format&amp;fit=crop&amp;w=1191&amp;q=80" alt="">
                  </div>
                  <div class="w-full lg:w-3/4 px-3">
                    <a class="hover:underline" href="#">
                      <h3 class="mb-1 text-2xl font-bold font-heading">Morbi scelerisque nulla et lectus dignissim eleifend nulla eu nulla a metus</h3>
                    </a>
                    <div class="mb-2 flex items-center text-sm">
                      <a class="text-red-600 hover:underline hover:text-red-700" href="#">John Doe</a>
                      <span class="text-gray-400 mx-2">&bull;</span>
                      <span class="text-gray-400">24 Jan, 2021</span>
                    </div>
                    <p class="text-gray-500">Quisque id sagittis turpis. Nulla sollicitudin rutrum eros eu dictum...</p>
                  </div>
                </div>
                <div class="flex flex-wrap -mx-3 mb-8 lg:mb-6">
                  <div class="mb-4 lg:mb-0 w-full lg:w-1/4 px-3">
                    <img class="w-full h-full object-cover rounded" src="https://images.unsplash.com/photo-1552338804-c42590cb7b88?ixlib=rb-1.2.1&amp;ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;auto=format&amp;fit=crop&amp;w=1189&amp;q=80" alt="">
                  </div>
                  <div class="w-full lg:w-3/4 px-3">
                    <a class="hover:underline" href="#">
                      <h3 class="mb-1 text-2xl font-bold font-heading">Morbi scelerisque nulla et lectus dignissim eleifend nulla eu nulla a metus</h3>
                    </a>
                    <div class="mb-2 flex items-center text-sm">
                      <a class="text-red-600 hover:underline hover:text-red-700" href="#">John Doe</a>
                      <span class="text-gray-400 mx-2">&bull;</span>
                      <span class="text-gray-400">24 Jan, 2021</span>
                    </div>
                    <p class="text-gray-500">Quisque id sagittis turpis. Nulla sollicitudin rutrum eros eu dictum...</p>
                  </div>
                </div>
                <div class="flex flex-wrap -mx-3">
                  <div class="mb-4 lg:mb-0 w-full lg:w-1/4 px-3">
                    <img class="w-full h-full object-cover rounded" src="https://images.unsplash.com/photo-1578509395623-a34c97f15379?ixlib=rb-1.2.1&amp;ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;auto=format&amp;fit=crop&amp;w=968&amp;q=80" alt="">
                  </div>
                  <div class="w-full lg:w-3/4 px-3">
                    <a class="hover:underline" href="#">
                      <h3 class="mb-1 text-2xl font-bold font-heading">Morbi scelerisque nulla et lectus dignissim eleifend nulla eu nulla a metus</h3>
                    </a>
                    <div class="mb-2 flex items-center text-sm">
                      <a class="text-red-600 hover:underline hover:text-red-700" href="#">John Doe</a>
                      <span class="text-gray-400 mx-2">&bull;</span>
                      <span class="text-gray-400">24 Jan, 2021</span>
                    </div>
                    <p class="text-gray-500">Quisque id sagittis turpis. Nulla sollicitudin rutrum eros eu dictum...</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        
      </section>
    
      <section>
        
        <div class="py-20 bg-gray-50 radius-for-skewed">
          <div class="container mx-auto px-4">
            <div class="mb-16 max-w-xl mx-auto text-center">
              <span class="text-red-600 font-bold">Dolor sit amet consectutar</span>
              <h2 class="text-5xl font-bold">Frequently Asked Questions</h2>
            </div>
            <div class="flex flex-wrap -mx-4 -mb-8">
              <div class="w-full lg:w-1/2 px-4 mb-8">
                <div class="h-full p-8 bg-white rounded shadow">
                  <div class="mb-6 flex items-start">
                    <span class="mr-4 inline-block p-3 rounded-full bg-red-600">
                      <svg class="w-6 h-6 text-white" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 8h10M7 12h4m1 8l-4-4H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-3l-4 4z"></path>
                      </svg>
                    </span>
                    <h3 class="text-xl font-bold">Fusce eget nunc et libero accumsan rutrum quis nec lectus?</h3>
                  </div>
                  <p class="text-gray-400 leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam euismod orci sed tristique placerat. Fusce in ligula urna. Fusce eget nunc et libero accumsan rutrum quis nec lectus. Quisque luctus sem nibh, quis ornare neque consectetur varius.</p>
                </div>
              </div>
              <div class="w-full lg:w-1/2 px-4 mb-8">
                <div class="h-full p-8 bg-white rounded shadow">
                  <div class="mb-6 flex items-start">
                    <span class="mr-4 inline-block p-3 rounded-full bg-red-600">
                      <svg class="w-6 h-6 text-white" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 8h10M7 12h4m1 8l-4-4H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-3l-4 4z"></path>
                      </svg>
                    </span>
                    <h3 class="text-xl font-bold">Nunc maximus odio sit amet eros faucibus?</h3>
                  </div>
                  <p class="text-gray-400 leading-loose">Phasellus in molestie lorem. In egestas placerat justo, eget congue tellus egestas vitae. Mauris placerat blandit congue. Nullam sit amet nulla sed velit sagittis accumsan. Ut a lacus in tellus molestie semper.</p>
                </div>
              </div>
              <div class="w-full lg:w-1/2 px-4 mb-8">
                <div class="h-full p-8 bg-white rounded shadow">
                  <div class="mb-6 flex items-start">
                    <span class="mr-4 inline-block p-3 rounded-full bg-red-600">
                      <svg class="w-6 h-6 text-white" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 8h10M7 12h4m1 8l-4-4H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-3l-4 4z"></path>
                      </svg>
                    </span>
                    <h3 class="text-xl font-bold">Nam feugiat ex eget sapien lobortis?</h3>
                  </div>
                  <p class="text-gray-400 leading-loose">Nam pretium dolor vel odio bibendum vehicula. Ut in dignissim eros. In ultrices laoreet porttitor. Sed gravida porttitor posuere. Nam vulputate metus vel massa luctus mollis. Sed malesuada nibh egestas ultricies volutpat. Nunc maximus odio sit amet eros faucibus, nec convallis arcu pellentesque.</p>
                </div>
              </div>
              <div class="w-full lg:w-1/2 px-4 mb-8">
                <div class="h-full p-8 bg-white rounded shadow">
                  <div class="mb-6 flex items-start">
                    <span class="mr-4 inline-block p-3 rounded-full bg-red-600">
                      <svg class="w-6 h-6 text-white" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 8h10M7 12h4m1 8l-4-4H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-3l-4 4z"></path>
                      </svg>
                    </span>
                    <h3 class="text-xl font-bold">In hac habitasse platea dictumst?</h3>
                  </div>
                  <p class="text-gray-400 leading-loose">Nullam ante dui, porta eget sagittis sed, iaculis vitae lorem. Vestibulum vel neque id lectus fringilla sollicitudin. Nunc sed dapibus velit. Integer ut felis nisl.</p>
                </div>
              </div>
              <div class="w-full lg:w-1/2 px-4 mb-8">
                <div class="h-full p-8 bg-white rounded shadow">
                  <div class="mb-6 flex items-start">
                    <span class="mr-4 inline-block p-3 rounded-full bg-red-600">
                      <svg class="w-6 h-6 text-white" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 8h10M7 12h4m1 8l-4-4H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-3l-4 4z"></path>
                      </svg>
                    </span>
                    <h3 class="text-xl font-bold">Nullam congue lacinia nibh quis scelerisque?</h3>
                  </div>
                  <p class="text-gray-400 leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam euismod orci sed tristique placerat. Fusce in ligula urna. Fusce eget nunc et libero accumsan rutrum quis nec lectus.</p>
                </div>
              </div>
              <div class="w-full lg:w-1/2 px-4 mb-8">
                <div class="h-full p-8 bg-white rounded shadow">
                  <div class="mb-6 flex items-start">
                    <span class="mr-4 inline-block p-3 rounded-full bg-red-600">
                      <svg class="w-6 h-6 text-white" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 8h10M7 12h4m1 8l-4-4H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-3l-4 4z"></path>
                      </svg>
                    </span>
                    <h3 class="text-xl font-bold">Nam feugiat ex eget sapien lobortis?</h3>
                  </div>
                  <p class="text-gray-400 leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam euismod orci sed tristique placerat. Fusce in ligula urna. Fusce eget nunc et libero accumsan rutrum quis nec lectus. Quisque luctus sem nibh, quis ornare neque consectetur varius.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
       
      </section>
    
      <section>
       
        <div class="py-20 bg-gray-50 radius-for-skewed">
          <div class="container mx-auto px-4">
            <div class="mb-8 md:mb-16 max-w-lg mx-auto text-center">
              <span class="text-red-600 font-bold">Dolor sit amet consectutar</span>
              <h2 class="mb-6 text-4xl lg:text-5xl font-bold font-heading">Lates Projects</h2>
              <div class="inline-flex flex-wrap py-1 sm:px-1 sm:space-x-1 bg-white rounded text-sm">
                <button class="w-full sm:w-auto mb-1 sm:mb-0 mx-1 sm:mx-0 py-2 px-4 hover:bg-gray-50 text-gray-500 hover:text-gray-900 rounded hover:shadow font-bold focus:outline-none transition duration-200">Category 1</button>
                <button class="w-full sm:w-auto mb-1 sm:mb-0 mx-1 sm:mx-0 py-2 px-4 bg-gray-50 text-gray-900 shadow rounded font-bold focus:outline-none transition duration-200">Category 2</button>
                <button class="w-full sm:w-auto mb-1 sm:mb-0 mx-1 sm:mx-0 py-2 px-4 hover:bg-gray-50 text-gray-500 hover:text-gray-900 rounded hover:shadow font-bold focus:outline-none transition duration-200">Category 3</button>
                <button class="w-full sm:w-auto mb-1 sm:mb-0 mx-1 sm:mx-0 py-2 px-4 hover:bg-gray-50 text-gray-500 hover:text-gray-900 rounded hover:shadow font-bold focus:outline-none transition duration-200">Category 4</button>
              </div>
            </div>
            <div class="flex flex-wrap -mx-4 mb-12">
              <div class="flex flex-wrap w-full lg:w-1/2 mb-8 lg:mb-0">
                <div class="w-full lg:w-1/2 px-4 mb-8">
                  <img class="h-64 w-full rounded-lg object-cover" src="https://images.unsplash.com/photo-1464822759023-fed622ff2c3b?ixlib=rb-1.2.1&amp;ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;auto=format&amp;fit=crop&amp;w=1050&amp;q=80" alt="">
                </div>
                <div class="w-full lg:w-1/2 px-4 mb-8">
                  <img class="h-64 w-full rounded-lg object-cover" src="https://images.unsplash.com/photo-1454496522488-7a8e488e8606?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=1055&amp;q=80" alt="">
                </div>
                <div class="w-full px-4">
                  <img class="h-64 lg:h-128 w-full rounded-lg object-cover" src="https://images.unsplash.com/photo-1476610182048-b716b8518aae?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=1127&amp;q=80" alt="">
                </div>
              </div>
              <div class="flex flex-wrap w-full lg:w-1/2">
                <div class="w-full px-4 mb-8">
                  <div class="relative">
                    <img class="h-128 w-full rounded-lg object-cover" src="https://images.unsplash.com/photo-1464822759023-fed622ff2c3b?ixlib=rb-1.2.1&amp;ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;auto=format&amp;fit=crop&amp;w=1050&amp;q=80" alt="">
                    <div class="absolute inset-0 bg-gray-900 opacity-80 rounded-lg"></div>
                    <div class="absolute inset-0 p-6 flex justify-center">
                      <div class="max-w-md my-auto">
                        <span class="text-red-600 font-bold">Dolor sit amet consectutar</span>
                        <h2 class="text-4xl lg:text-5xl text-white font-bold">Build &amp; Launch without problems</h2>
                        <div class="max-w-xs">
                          <p class="mb-6 text-gray-400">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque efficitur nisl sodales egestas lobortis.</p>
                          <a class="inline-block py-2 px-6 rounded-l-xl rounded-t-xl bg-red-600 hover:bg-red-700 text-gray-50 font-bold leading-loose" href="#">See More</a>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="w-full lg:w-1/2 px-4 mb-8 lg:mb-0">
                  <img class="h-64 w-full rounded-lg object-cover" src="https://images.unsplash.com/photo-1464822759023-fed622ff2c3b?ixlib=rb-1.2.1&amp;ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;auto=format&amp;fit=crop&amp;w=1050&amp;q=80" alt="">
                </div>
                <div class="w-full lg:w-1/2 px-4">
                  <img class="h-64 w-full rounded-lg object-cover" src="https://images.unsplash.com/photo-1454496522488-7a8e488e8606?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=1055&amp;q=80" alt="">
                </div>
              </div>
            </div>
            <div class="text-center"><a class="inline-block py-2 px-6 rounded-l-xl rounded-t-xl bg-red-600 hover:bg-red-700 text-gray-50 font-bold leading-loose transition duration-200" href="#">View More Projects</a></div>
          </div>
        </div>
       
      </section>
    
      <section>
        
        <div class="py-20 bg-gray-50 radius-for-skewed">
          <div class="container mx-auto px-4">
            <div class="flex flex-wrap -mx-4">
              <div class="w-full lg:w-1/2 px-4">
                <div class="max-w-md">
                  <span class="text-red-600 font-bold">Dolor sit amet consectutar</span>
                  <h2 class="text-4xl lg:text-5xl font-bold font-heading">Build &amp; Launch without problems</h2>
                  <p class="mb-16 text-gray-500 leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque efficitur nisl sodales egestas lobortis.</p>
                  <div class="flex flex-wrap">
                    <div class="mb-8 w-full lg:w-1/2">
                      <h4 class="text-gray-500">Total Revenue</h4>
                      <span class="text-3xl lg:text-4xl font-bold">$33,261</span>
                    </div>
                    <div class="mb-8 w-full lg:w-1/2">
                      <h4 class="text-gray-500">Subscribers</h4>
                      <span class="text-3xl lg:text-4xl font-bold">481,095</span>
                    </div>
                    <div class="mb-8 w-full lg:w-1/2">
                      <h4 class="text-gray-500">Modal Sale Rate</h4>
                      <span class="text-3xl lg:text-4xl font-bold">25%</span>
                    </div>
                    <div class="mb-8 w-full lg:w-1/2">
                      <h4 class="text-gray-500">Conversations</h4>
                      <span class="text-3xl lg:text-4xl font-bold">643,533</span>
                    </div>
                  </div>
                </div>
              </div>
              <div class="flex flex-wrap items-center justify-center w-full lg:w-1/2 px-4">
                <button class="order-1 xl:order-0 mr-12 inline-block p-6 bg-white rounded-full shadow text-red-600 hover:text-red-400 focus:outline-none">
                  <svg class="w-6 h-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 19l-7-7m0 0l7-7m-7 7h18"></path>
                  </svg>
                </button>
                <div class="w-full xl:w-auto order-0 xl:order-1">
                  <img class="mx-auto mb-8 xl:mb-0" src="@/atis-assets/illustrations/book-detail-full.png" alt="">
                </div>
                <button class="order-2 xl:order-2 ml-12 inline-block p-6 bg-white rounded-full shadow text-red-600 hover:text-red-400 focus:outline-none">
                  <svg class="w-6 h-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path>
                  </svg>
                </button>
              </div>
            </div>
          </div>
        </div>
        
      </section>
    
      <section>
        
        <div class="py-20 bg-gray-50 radius-for-skewed">
          <div class="container mx-auto px-4">
            <div class="flex flex-wrap items-center -mx-4">
              <div class="mb-12 lg:mb-0 w-full lg:w-1/2 px-4">
                <div class="max-w-md">
                  <span class="text-red-600 font-bold">Dolor sit amet consectutar</span>
                  <h2 class="text-4xl lg:text-5xl font-bold font-heading">Build &amp; Launch without problems</h2>
                  <p class="mb-6 text-gray-500 leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque efficitur nisl sodales egestas lobortis.</p>
                  <ul class="mb-8 text-gray-500 font-bold">
                    <li class="mb-3 flex items-center">
                      <svg class="w-5 h-5 mr-2 text-red-500" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                      </svg>
                      <span>Vestibulum viverra ante non libero</span>
                    </li>
                    <li class="mb-3 flex items-center">
                      <svg class="w-5 h-5 mr-2 text-red-500" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                      </svg>
                      <span>Morbi mollis metus pretium ultrices tincidunt</span>
                    </li>
                    <li class="mb-3 flex items-center">
                      <svg class="w-5 h-5 mr-2 text-red-500" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                      </svg>
                      <span>Etiam lectus nunc, commodo et risus in</span>
                    </li>
                  </ul>
                  <div>
                    <a href="#">
                      <img class="mb-2 mr-6 inline-block" src="@/atis-assets/logo/brands/google-play-store.png" alt="">
                    </a>
                    <a href="#">
                      <img class="mb-2 inline-block" src="@/atis-assets/logo/brands/app-store-download.png" alt="">
                    </a>
                  </div>
                </div>
              </div>
              <div class="transform -rotate-12 flex items-center w-full lg:w-1/2 px-4">
                <div class="w-1/3">
                  <img src="@/atis-assets/illustrations/book-detail-full.png" alt="">
                </div>
                <div class="w-1/3">
                  <img src="@/atis-assets/illustrations/login-full.png" alt="">
                  <img src="@/atis-assets/illustrations/details-full.png" alt="">
                </div>
                <div class="w-1/3">
                  <img src="@/atis-assets/illustrations/home.png" alt="">
                </div>
              </div>
            </div>
          </div>
        </div>
        
      </section>
    
      <section>
        
        <div class="py-20 bg-gray-50 radius-for-skewed">
          <div class="container mx-auto px-4">
            <div class="mb-20 lg:mb-40 max-w-2xl mx-auto text-center">
              <a class="inline-block mb-6 mx-auto text-3xl font-bold leading-none" href="#">
                <img class="h-12" src="@/atis-assets/logo/atis/atis-mono-sign.svg" alt="" width="auto">
              </a>
              <h2 class="mb-4 text-4xl lg:text-5xl font-bold">So much more than a business analytics tool</h2>
              <p class="mb-6 max-w-md mx-auto text-gray-500 leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque efficitur nisl sodales egestas lobortis.</p>
              <a class="inline-block py-2 px-6 bg-red-600 hover:bg-red-700 text-white font-bold rounded-l-xl rounded-t-xl" href="#">Get Started</a>
            </div>
            <div class="relative flex flex-wrap justify-between">
              <div class="w-full lg:w-1/3 mb-6">
                <ul class="flex flex-wrap justify-center">
                  <li class="mr-6"><a class="hover:text-gray-600" href="#">Start</a></li>
                  <li class="mr-6"><a class="hover:text-gray-600" href="#">About Us</a></li>
                  <li class="mr-6"><a class="hover:text-gray-600" href="#">Services</a></li>
                  <li><a class="hover:text-gray-600" href="#">Platform</a></li>
                </ul>
              </div>
              <div class="mb-6 w-full lg:w-auto lg:absolute lg:left-1/2 lg:transform lg:-translate-x-1/2 flex justify-center lg:space-x-4">
                <a href="#">
                  <img src="@/atis-assets/social/facebook.svg" alt="">
                </a>
                <a href="#">
                  <img src="@/atis-assets/social/twitter.svg" alt="">
                </a>
                <a href="#">
                  <img src="@/atis-assets/social/instagram.svg" alt="">
                </a>
              </div>
              <div class="w-full lg:w-1/3 flex justify-center lg:justify-end">
                <span>Atis, Inc.</span>
              </div>
            </div>
          </div>
        </div>
        
      </section>
    
      <section>
       
        <div class="py-20 bg-gray-50 radius-for-skewed">
          <div class="container mx-auto px-4">
            <img class="mx-auto" src="@/atis-assets/illustrations/pablo.png" alt="">
            <div class="text-center">
              <span class="mb-6 text-4xl text-red-600 font-bold">Whoops!</span>
              <h3 class="mb-2 text-4xl font-bold">Something went wrong!</h3>
              <p class="mb-8 text-gray-400">Sorry, but we are unable to open this page</p>
              <div><a class="w-full lg:w-auto mb-2 lg:mb-0 lg:mr-4 inline-block py-2 px-6 rounded-l-xl rounded-t-xl font-bold leading-loose text-gray-50 bg-red-600 hover:bg-red-700" href="#">Go back to Homepage</a><a class="w-full lg:w-auto inline-block py-2 px-6 rounded-l-xl rounded-t-xl font-bold leading-loose bg-white hover:bg-gray-50" href="#">Try Again</a></div>
            </div>
          </div>
        </div>
       
      </section>
    
      <!-- <div class="fixed bottom-0 z-50">
        <div class="container mx-auto px-4">
          <div class="flex flex-wrap items-center mb-6 p-6 bg-gray-800 text-white rounded-lg">
            <div class="w-full lg:w-3/4 px-4">
              <p class="font-bold font-heading">Cookie Policy</p>
              <p class="mt-3 mb-6 text-gray-400 text-sm">We use cookies to personalise content, to provide social media features and to analyse our traffic. We also share information about your use of our site with our social media, advertising and analytics partners. If you want to change your cookie setting, please see the &lsquo;how to reject cookies&apos; section of our . Otherwise, if you agree to our use of cookies, please continue to use our website.</p>
            </div>
            <div class="w-full lg:w-1/4 px-4 lg:text-right"><a class="inline-block mr-4 py-2 px-4 rounded-l-xl rounded-t-xl border-2 border-red-600 hover:border-red-700 bg-red-600 hover:bg-red-700 transition duration-200" href="#">Allow</a><a class="inline-block py-2 px-4 rounded-r-xl rounded-t-xl border-2 border-gray-400 hover:bg-gray-700 transition duration-200" href="#">Decline</a></div>
          </div>
        </div>
      </div> -->
    
      <section>
        
        <div class="py-20 bg-gray-50 radius-for-skewed">
          <div class="container mx-auto px-4">
            <div class="mb-8 md:mb-16 max-w-lg mx-auto text-center">
              <span class="text-red-600 font-bold">Dolor sit amet consectutar</span>
              <h2 class="mb-6 text-4xl lg:text-5xl font-bold font-heading">Lates Projects</h2>
              <div class="inline-flex flex-wrap py-1 sm:px-1 sm:space-x-1 bg-white rounded text-sm">
                <button class="w-full sm:w-auto mb-1 sm:mb-0 mx-1 sm:mx-0 py-2 px-4 hover:bg-gray-50 text-gray-500 hover:text-gray-900 rounded hover:shadow font-bold focus:outline-none transition duration-200">Category 1</button>
                <button class="w-full sm:w-auto mb-1 sm:mb-0 mx-1 sm:mx-0 py-2 px-4 bg-gray-50 text-gray-900 shadow rounded font-bold focus:outline-none transition duration-200">Category 2</button>
                <button class="w-full sm:w-auto mb-1 sm:mb-0 mx-1 sm:mx-0 py-2 px-4 hover:bg-gray-50 text-gray-500 hover:text-gray-900 rounded hover:shadow font-bold focus:outline-none transition duration-200">Category 3</button>
                <button class="w-full sm:w-auto mb-1 sm:mb-0 mx-1 sm:mx-0 py-2 px-4 hover:bg-gray-50 text-gray-500 hover:text-gray-900 rounded hover:shadow font-bold focus:outline-none transition duration-200">Category 4</button>
              </div>
            </div>
            <div class="flex flex-wrap mb-8 -mx-4">
              <div class="w-full md:w-1/2 lg:w-1/4 mb-8 px-4">
                <a href="#">
                  <img class="mx-auto h-64 w-full rounded object-cover" src="https://images.unsplash.com/photo-1464822759023-fed622ff2c3b?ixlib=rb-1.2.1&amp;ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;auto=format&amp;fit=crop&amp;w=1050&amp;q=80" alt="">
                </a>
              </div>
              <div class="w-full md:w-1/2 lg:w-1/4 mb-8 px-4">
                <a href="#">
                  <img class="mx-auto h-64 w-full rounded object-cover" src="https://images.unsplash.com/photo-1454496522488-7a8e488e8606?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=1055&amp;q=80" alt="">
                </a>
              </div>
              <div class="w-full md:w-1/2 lg:w-1/4 mb-8 px-4">
                <div class="relative mx-auto h-64 w-full rounded-lg">
                  <img class="relative h-full w-full rounded-lg object-cover" src="https://images.unsplash.com/photo-1464822759023-fed622ff2c3b?ixlib=rb-1.2.1&amp;ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;auto=format&amp;fit=crop&amp;w=1050&amp;q=80" alt="">
                  <div class="absolute inset-0 bg-gray-900 opacity-50 rounded-lg"></div>
                  <div class="absolute inset-0 flex items-center justify-center"><a class="inline-block py-2 px-4 border-2 border-gray-400 hover:border-white bg-transparent text-gray-50 hover:bg-white hover:text-gray-900 transition duration-200 rounded-l-xl rounded-t-xl font-bold leading-loose" href="#">View Project</a></div>
                </div>
              </div>
              <div class="w-full md:w-1/2 lg:w-1/4 mb-8 px-4">
                <a href="#">
                  <img class="mx-auto h-64 w-full rounded object-cover" src="https://images.unsplash.com/photo-1518098268026-4e89f1a2cd8e?ixlib=rb-1.2.1&amp;ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;auto=format&amp;fit=crop&amp;w=968&amp;q=80" alt="">
                </a>
              </div>
              <div class="w-full md:w-1/2 lg:w-1/4 mb-8 px-4">
                <a href="#">
                  <img class="mx-auto h-64 w-full rounded object-cover" src="https://images.unsplash.com/photo-1472214103451-9374bd1c798e?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=1050&amp;q=80" alt="">
                </a>
              </div>
              <div class="w-full md:w-1/2 lg:w-1/4 mb-8 px-4">
                <a href="#">
                  <img class="mx-auto h-64 w-full rounded object-cover" src="https://images.unsplash.com/photo-1459213599465-03ab6a4d5931?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=1055&amp;q=80" alt="">
                </a>
              </div>
              <div class="w-full md:w-1/2 lg:w-1/4 mb-8 px-4">
                <a href="#">
                  <img class="mx-auto h-64 w-full rounded object-cover" src="https://images.unsplash.com/photo-1476610182048-b716b8518aae?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=1127&amp;q=80" alt="">
                </a>
              </div>
              <div class="w-full md:w-1/2 lg:w-1/4 mb-8 px-4">
                <a href="#">
                  <img class="mx-auto h-64 w-full rounded object-cover" src="https://images.unsplash.com/photo-1413752362258-7af2a667b590?ixlib=rb-1.2.1&amp;ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;auto=format&amp;fit=crop&amp;w=1055&amp;q=80" alt="">
                </a>
              </div>
            </div>
            <div class="text-center"><a class="inline-block py-2 px-6 leading-loose rounded-l-xl rounded-t-xl bg-red-600 hover:bg-red-700 text-gray-50 font-bold" href="#">View More Projects</a></div>
          </div>
        </div>
        
      </section>
    
      <section>
        
        <div class="py-20 bg-gray-50 radius-for-skewed">
          <div class="container mx-auto px-4">
            <div class="mb-12">
              <h2 class="text-4xl lg:text-5xl font-bold font-heading">Contact</h2>
              <p class="text-gray-500 leading-loose">Got any question? Let&rsquo;s talk about it.</p>
            </div>
            <div class="flex flex-wrap">
              <div class="w-full lg:w-1/2 mb-16 lg:mb-0">
                <div class="flex flex-wrap">
                  <div class="mb-12 w-full md:w-1/2 lg:w-1/2">
                    <h3 class="mb-2 text-3xl lg:text-4xl font-bold">Office</h3>
                    <p class="text-gray-400">359 Hidden Valley</p>
                    <p class="text-gray-400">Road, NY</p>
                  </div>
                  <div class="mb-12 w-full md:w-1/2">
                    <h3 class="mb-2 text-3xl lg:text-4xl font-bold">Contacts</h3>
                    <p class="text-gray-400">hallo@gamil.com</p>
                  </div>
                  <div class="w-full md:w-1/3 lg:w-full">
                    <h3 class="mb-2 text-3xl lg:text-4xl font-bold">Socials</h3>
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
                  </div>
                </div>
              </div>
              <div class="w-full lg:w-1/2">
                <div class="max-w-md lg:mx-auto">
                  <form action="">
                    <div class="mb-4 text-sm">
                      <span class="mr-4 font-semibold">Department:</span>
                      <label class="mr-4">
                        <input class="mr-1" type="radio" name="department" value="1" checked="">
                        <span>Support</span>
                      </label>
                      <label>
                        <input class="mr-1" type="radio" name="department" value="2">
                        <span>Sales</span>
                      </label>
                    </div>
                    <div class="mb-4">
                      <input class="w-full p-4 text-xs font-semibold leading-none bg-white rounded outline-none" type="text" placeholder="Subject">
                    </div>
                    <div class="mb-4">
                      <input class="w-full p-4 text-xs font-semibold leading-none bg-white rounded outline-none" type="text" placeholder="Name">
                    </div>
                    <div class="mb-4">
                      <input class="w-full p-4 text-xs font-semibold leading-none bg-white rounded outline-none" type="email" placeholder="name@example.com">
                    </div>
                    <div class="mb-4"><textarea class="w-full h-24 p-4 text-xs font-semibold leading-none resize-none bg-white rounded outline-none" type="text" placeholder="Message..."></textarea></div>
                    <div class="mb-4">
                      <label class="flex px-2 bg-white rounded">
                        <input class="hidden" type="file" placeholder="Choose file.." name="Choose file">
                        <div class="my-1 ml-auto px-4 py-3 text-xs text-white font-semibold leading-none bg-gray-500 hover:bg-gray-600 rounded cursor-pointer transition duration-200">Browse</div>
                      </label>
                    </div>
                    <div class="flex justify-between items-center">
                      <label>
                        <input class="mr-1" type="checkbox" name="terms" value="1">
                        <span class="text-sm font-semibold">I agree to terms and conditions.</span>
                      </label>
                      <button class="inline-block py-2 px-6 rounded-l-xl rounded-t-xl bg-red-600 hover:bg-red-700 text-gray-50 font-bold leading-loose transition duration-200">Get Started</button>
                    </div>
                  </form>
                </div>
              </div>
            </div>
          </div>
        </div>
        
      </section>
    
      <section class="py-20 bg-gray-50">
        <div class="container mx-auto px-4">
          <div class="flex flex-wrap items-center justify-center -mx-4">
            <div class="mb-16 lg:mb-0 max-w-2xl lg:w-1/2 px-4">
              <a class="mb-6 inline-block text-3xl font-bold leading-none" href="#">
                <img class="h-12" src="@/atis-assets/logo/atis/atis-mono-sign.svg" alt="" width="auto">
              </a>
              <h2 class="mb-4 text-4xl md:text-5xl font-bold font-heading">So much more than a business analytics tool</h2>
              <p class="mb-8 text-gray-500 leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque efficitur nisl sodales egestas lobortis.</p>
              <a class="inline-block py-2 px-6 bg-red-600 hover:bg-red-700 text-white font-bold leading-loose transition duration-250 rounded-l-xl rounded-t-xl" href="#">Get Started</a>
            </div>
            <div class="w-full lg:w-1/2 px-4">
              <div class="max-w-sm mx-auto lg:mr-0 lg:ml-auto">
                <div class="mb-6 py-8 px-6 bg-white shadow rounded-t-3xl rounded-bl-3xl text-center">
                  <form action="">
                    <div class="mb-6">
                      <span class="text-sm text-gray-400">Sign Up</span>
                      <h4 class="text-2xl">Create an account</h4>
                    </div>
                    <div class="mb-4 flex flex-wrap -mx-2">
                      <div class="mb-4 lg:mb-0 w-full lg:w-1/2 px-2">
                        <input class="py-2 px-3 w-full bg-gray-50 rounded leading-loose" type="text" placeholder="First Name">
                      </div>
                      <div class="w-full lg:w-1/2 px-2">
                        <input class="py-2 px-3 w-full bg-gray-50 rounded leading-loose" type="text" placeholder="Last Name">
                      </div>
                    </div>
                    <input class="mb-4 py-2 px-3 w-full bg-gray-50 rounded leading-loose" type="email" placeholder="hello@example.com">
                    <input class="mb-6 py-2 px-3 w-full bg-gray-50 rounded leading-loose" type="password" placeholder="Enter your password">
                    <button class="mb-4 py-4 w-full rounded text-sm bg-red-600 hover:bg-red-700 text-white font-bold leading-normal transition duration-200">Sign Up</button>
                  </form>
                  <p class="text-xs text-gray-400">
                    <span>Already have an account?</span>
                    <a class="text-red-500" href="#">Sign In</a>
                  </p>
                </div>
                <p class="text-center text-gray-400">
                  <a class="text-red-600 hover:text-red-700" href="#">Police privacy</a>
                  <span>and</span>
                  <a class="text-red-600 hover:text-red-700" href="#">Terms of Use</a>
                </p>
              </div>
            </div>
          </div>
        </div>
      </section>
    
      <section>
       
        <div class="py-20 bg-gray-50 radius-for-skewed">
          <div class="container mx-auto px-4">
            <div class="max-w-6xl p-4 flex flex-wrap justify-center items-center">
              <div class="mb-6 w-full lg:w-1/3 text-center">
                <img class="mb-6 mx-auto w-32 h-32 rounded-full object-cover" src="https://images.unsplash.com/photo-1564564321837-a57b7070ac4f?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=1055&amp;q=80" alt="">
                <h4 class="text-xl">Ian Brown</h4>
                <p class="text-red-600">Head of Development</p>
              </div>
              <div class="w-full lg:w-2/3">
                <svg class="mb-4 text-red-600 h-10" viewbox="0 0 32 28" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M10.2418 12.749C9.45369 12.522 8.66554 12.4069 7.89887 12.4069C6.71496 12.4069 5.72709 12.6775 4.96109 13.0088C5.69957 10.3053 7.47358 5.6405 11.0075 5.11517C11.3348 5.0665 11.603 4.82986 11.6923 4.51131L12.4646 1.74875C12.5298 1.51512 12.4912 1.26505 12.3579 1.06231C12.2246 0.859563 12.0105 0.724288 11.7705 0.691393C11.5097 0.655812 11.2438 0.637686 10.9803 0.637686C6.73846 0.637686 2.53756 5.06516 0.764895 11.4046C-0.275679 15.1238 -0.580802 20.7154 1.98237 24.2349C3.41668 26.2043 5.50924 27.2559 8.20198 27.361C8.21305 27.3613 8.2238 27.3616 8.23487 27.3616C11.5573 27.3616 14.5035 25.1241 15.3997 21.9208C15.9351 20.0058 15.6931 17.9975 14.7176 16.2644C13.7526 14.5508 12.1632 13.3018 10.2418 12.749Z" fill="currentColor"></path>
                  <path d="M31.0396 16.2648C30.0746 14.5508 28.4852 13.3018 26.5638 12.749C25.7757 12.522 24.9875 12.4069 24.2212 12.4069C23.0373 12.4069 22.0491 12.6775 21.2831 13.0088C22.0215 10.3053 23.7955 5.6405 27.3298 5.11517C27.6571 5.0665 27.9249 4.82986 28.0146 4.51131L28.7869 1.74875C28.8521 1.51512 28.8135 1.26505 28.6802 1.06231C28.5473 0.859563 28.3331 0.724288 28.0928 0.691393C27.8323 0.655812 27.5664 0.637686 27.3026 0.637686C23.0608 0.637686 18.8599 5.06516 17.0869 11.4046C16.0466 15.1238 15.7415 20.7154 18.305 24.2356C19.739 26.2046 21.8319 27.2566 24.5243 27.3613C24.5354 27.3616 24.5461 27.362 24.5575 27.362C27.8796 27.362 30.8261 25.1244 31.7224 21.9211C32.2571 20.0061 32.0147 17.9975 31.0396 16.2648Z" fill="currentColor"></path>
                </svg>
                <h3 class="mb-6 text-3xl lg:text-4xl font-bold font-heading">Maecenas nibh purus, pharetra ac felis sed, elementum molestie urna. Nunc at arcu non ipsum.</h3>
                <div>
                  <button class="mr-1 bg-gray-200 rounded-full p-1"></button>
                  <button class="mr-1 bg-gray-200 rounded-full p-1"></button>
                  <button class="mr-1 bg-red-600 rounded-full p-1"></button>
                  <button class="bg-gray-200 rounded-full p-1"></button>
                </div>
              </div>
            </div>
          </div>
        </div>
       
      </section>
    
      <section class="py-20 bg-gray-50">
        <div class="container mx-auto px-4">
          <div class="flex flex-wrap items-center justify-center -mx-4">
            <div class="w-full lg:w-1/2 px-4 order-1 lg:order-0">
              <h2 class="mb-4 text-4xl md:text-5xl font-bold font-heading">So much more than a business analytics tool</h2>
              <p class="mb-8 text-gray-500 leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque efficitur nisl sodales egestas lobortis.</p>
              <a class="inline-block py-2 px-6 bg-red-600 hover:bg-red-700 text-white font-bold leading-loose rounded-l-xl rounded-t-xl transition duration-200" href="#">Get Started</a>
            </div>
            <div class="w-full lg:w-1/2 px-4 order-0 lg:order-1 mb-8 lg:mb-0">
              <img src="@/atis-assets/illustrations/pablo-coming-soon-mono.png" alt="">
            </div>
          </div>
        </div>
      </section>
    
      <section>
       
        <div class="py-20 bg-gray-50 radius-for-skewed">
          <div class="container mx-auto px-4">
            <div class="max-w-xl mx-auto text-center">
              <a class="mb-6 inline-block text-3xl font-bold leading-none" href="#">
                <img class="h-12" src="@/atis-assets/logo/atis/atis-mono-sign.svg" alt="" width="auto">
              </a>
              <h2 class="mb-2 text-4xl lg:text-5xl font-bold font-heading">So much more than a business analytics tool</h2>
              <p class="mb-8 text-gray-400 leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque efficitur nisl sodales egestas lobortis.</p>
              <form class="mx-auto" action="">
                <div class="max-w-md mx-auto flex flex-wrap items-center">
                  <input class="flex-grow py-3 px-4 mr-4 text-xs rounded leading-loose" type="email" placeholder="example@shuffle.dev">
                  <button class="w-auto py-2 px-6 rounded-t-xl rounded-l-xl bg-red-600 hover:bg-red-700 text-gray-50 font-bold leading-loose transition duration-200">Sign Up</button>
                </div>
              </form>
            </div>
          </div>
        </div>
       
      </section>
    
      <section>
        
        <div class="py-20 bg-gray-50 radius-for-skewed">
          <div class="container mx-auto px-4">
            <div class="mb-16 max-w-xl mx-auto text-center">
              <span class="text-red-600 font-bold font-heading">Dolor sit amet consectutar</span>
              <h2 class="mb-6 text-5xl font-bold font-heading">Frequently Asked Questions</h2>
              <form class="flex justify-center">
                <input class="w-2/3 p-4 text-xs font-heading bg-white focus:border-gray-500 focus:outline-none rounded-l" placeholder="Search, find any question you want to ask...">
                <button class="pr-4 rounded-r-lg bg-white text-red-600">
                  <svg class="w-6 h-6" fill="none" stroke="currentColor" viewbox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path>
                  </svg>
                </button>
              </form>
            </div>
            <div class="mb-16 flex justify-center space-x-4">
              <button class="inline-block h-2 w-2 bg-red-600 rounded-full"></button>
              <button class="inline-block h-2 w-2 bg-red-600 rounded-full"></button>
              <button class="inline-block h-2 w-2 bg-red-600 rounded-full"></button>
              <button class="inline-block h-2 w-2 bg-red-600 rounded-full"></button>
              <button class="inline-block h-2 w-2 bg-red-600 rounded-full"></button>
            </div>
            <div class="max-w-3xl mx-auto">
              <ul class="space-y-4 lg:space-y-6">
                <li class="p-6 bg-gray-50 rounded shadow">
                  <button class="w-full flex justify-between items-center text-left font-bold font-heading hover:text-gray-600">
                    <span class="text-xl">Lorem ipsum dolor sit amet, consectetur adipiscing elit?</span>
                    <svg class="w-4 h-4 text-red-600" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 10l7-7m0 0l7 7m-7-7v18"></path>
                    </svg>
                  </button>
                  <p class="mt-4 text-gray-400 font-normal leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam euismod orci sed tristique placerat. Fusce in ligula urna. Fusce eget nunc et libero accumsan rutrum quis nec lectus. Quisque luctus sem nibh, quis ornare neque consectetur varius. Maecenas rhoncus consectetur rutrum.</p>
                </li>
                <li class="p-6 bg-gray-50 rounded shadow">
                  <button class="w-full flex justify-between items-center text-left font-bold font-heading hover:text-gray-600">
                    <span class="text-xl">Nunc maximus odio sit amet eros faucibus?</span>
                    <svg class="w-4 h-4 text-red-600" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 14l-7 7m0 0l-7-7m7 7V3"></path>
                    </svg>
                  </button>
                  <p class="hidden mt-4 text-gray-400 font-normal leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus quis ultricies est. Duis nec hendrerit magna. Ut vel orci gravida, hendrerit enim non, gravida turpis. Praesent non lectus porttitor, scelerisque nulla nec, ornare neque. Integer massa libero, ornare ut leo nec, scelerisque rutrum elit. Morbi et massa id ipsum lobortis rhoncus. Aenean sit amet porta nulla, quis varius risus. Suspendisse ultrices ut lectus non laoreet. Etiam ornare laoreet tortor quis porttitor. Suspendisse tempus erat non dui volutpat eleifend.</p>
                </li>
                <li class="p-6 bg-gray-50 rounded shadow">
                  <button class="w-full flex justify-between items-center text-left font-bold font-heading hover:text-gray-600">
                    <span class="text-xl">Nam feugiat ex eget sapien lobortis?</span>
                    <svg class="w-4 h-4 text-red-600" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 14l-7 7m0 0l-7-7m7 7V3"></path>
                    </svg>
                  </button>
                  <p class="hidden mt-4 text-gray-400 font-normal leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus quis ultricies est. Duis nec hendrerit magna. Ut vel orci gravida, hendrerit enim non, gravida turpis. Praesent non lectus porttitor, scelerisque nulla nec, ornare neque. Integer massa libero, ornare ut leo nec, scelerisque rutrum elit. Morbi et massa id ipsum lobortis rhoncus. Aenean sit amet porta nulla, quis varius risus. Suspendisse ultrices ut lectus non laoreet. Etiam ornare laoreet tortor quis porttitor. Suspendisse tempus erat non dui volutpat eleifend.</p>
                </li>
                <li class="p-6 bg-gray-50 rounded shadow">
                  <button class="w-full flex justify-between items-center text-left font-bold font-heading hover:text-gray-600">
                    <span class="text-xl">In hac habitasse platea dictumst?</span>
                    <svg class="w-4 h-4 text-red-600" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 14l-7 7m0 0l-7-7m7 7V3"></path>
                    </svg>
                  </button>
                  <p class="hidden mt-4 text-gray-400 font-normal leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus quis ultricies est. Duis nec hendrerit magna. Ut vel orci gravida, hendrerit enim non, gravida turpis. Praesent non lectus porttitor, scelerisque nulla nec, ornare neque. Integer massa libero, ornare ut leo nec, scelerisque rutrum elit. Morbi et massa id ipsum lobortis rhoncus. Aenean sit amet porta nulla, quis varius risus. Suspendisse ultrices ut lectus non laoreet. Etiam ornare laoreet tortor quis porttitor. Suspendisse tempus erat non dui volutpat eleifend.</p>
                </li>
                <li class="p-6 bg-gray-50 rounded shadow">
                  <button class="w-full flex justify-between items-center text-left font-bold font-heading hover:text-gray-600">
                    <span class="text-xl">Nullam congue lacinia nibh quis scelerisque?</span>
                    <svg class="w-4 h-4 text-red-600" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 14l-7 7m0 0l-7-7m7 7V3"></path>
                    </svg>
                  </button>
                  <p class="hidden mt-4 text-gray-400 font-normal leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus quis ultricies est. Duis nec hendrerit magna. Ut vel orci gravida, hendrerit enim non, gravida turpis. Praesent non lectus porttitor, scelerisque nulla nec, ornare neque. Integer massa libero, ornare ut leo nec, scelerisque rutrum elit. Morbi et massa id ipsum lobortis rhoncus. Aenean sit amet porta nulla, quis varius risus. Suspendisse ultrices ut lectus non laoreet. Etiam ornare laoreet tortor quis porttitor. Suspendisse tempus erat non dui volutpat eleifend.</p>
                </li>
                <li class="p-6 bg-gray-50 rounded shadow">
                  <button class="w-full flex justify-between items-center text-left font-bold font-heading hover:text-gray-600">
                    <span class="text-xl">Nam feugiat ex eget sapien lobortis?</span>
                    <svg class="w-4 h-4 text-red-600" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 14l-7 7m0 0l-7-7m7 7V3"></path>
                    </svg>
                  </button>
                  <p class="hidden mt-4 text-gray-400 font-normal leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus quis ultricies est. Duis nec hendrerit magna. Ut vel orci gravida, hendrerit enim non, gravida turpis. Praesent non lectus porttitor, scelerisque nulla nec, ornare neque. Integer massa libero, ornare ut leo nec, scelerisque rutrum elit. Morbi et massa id ipsum lobortis rhoncus. Aenean sit amet porta nulla, quis varius risus. Suspendisse ultrices ut lectus non laoreet. Etiam ornare laoreet tortor quis porttitor. Suspendisse tempus erat non dui volutpat eleifend.</p>
                </li>
              </ul>
            </div>
          </div>
        </div>
        
      </section>
    
      <section>
        
        <div class="py-20 bg-gray-50 radius-for-skewed">
          <div class="container px-4 mx-auto">
            <div class="lg:flex items-center justify-center md:space-x-8">
              <div class="mb-10 text-center lg:hidden">
                <button class="mr-6 lg:mr-0 bg-white p-4 rounded-full shadow-md text-red-600 hover:text-red-400 transition duration-200">
                  <svg class="w-6 h-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 19l-7-7m0 0l7-7m-7 7h18"></path>
                  </svg>
                </button>
                <button class="bg-white p-4 rounded-full shadow-md text-red-600 hover:text-red-400 transition duration-200">
                  <svg class="w-6 h-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path>
                  </svg>
                </button>
              </div>
              <button class="hidden lg:block lg:mr-0 bg-white p-5 rounded-full shadow-md text-red-600 hover:text-red-400 transition duration-200">
                <svg class="w-6 h-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 19l-7-7m0 0l7-7m-7 7h18"></path>
                </svg>
              </button>
              <div class="flex w-full flex-wrap bg-white shadow rounded">
                <div class="py-10 text-center w-full lg:w-1/3 border-r">
                  <span class="text-5xl lg:text-6xl font-bold">5.0</span>
                  <div class="mb-6 lg:mb-12 flex text-red-600 justify-center">
                    <svg class="w-6 h-6" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                      <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path>
                    </svg>
                    <svg class="w-6 h-6" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                      <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path>
                    </svg>
                    <svg class="w-6 h-6" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                      <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path>
                    </svg>
                    <svg class="w-6 h-6" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                      <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path>
                    </svg>
                    <svg class="w-6 h-6" xmlns="http://www.w3.org/2000/svg" viewbox="0 0 20 20" fill="currentColor">
                      <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path>
                    </svg>
                  </div>
                  <div>
                    <img class="block mx-auto" src="@/atis-assets/social/clutch-logo.png" alt="">
                  </div>
                </div>
                <div class="py-10 px-6 w-full lg:w-2/3">
                  <img class="mb-10 w-10 h-10" src="@/atis-assets/elements/left-quote.png" alt="">
                  <p class="mb-10 text-xl lg:text-2xl leading-loose text-gray-500">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque et placerat metus. Morbi aliquet felis sit amet erat finibus, ac condimentum ligula ornare.</p>
                  <h4 class="text-2xl font-bold font-heading">Alice Bradley</h4>
                  <p class="text-gray-500">Backend Developer</p>
                </div>
              </div>
              <button class="hidden lg:block bg-white p-5 rounded-full shadow-md text-red-600 hover:text-red-400 transition duration-200">
                <svg class="w-6 h-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewbox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path>
                </svg>
              </button>
            </div>
          </div>
        </div>
       
      </section>
    
      <!-- <div class="fixed bottom-0 inset-x-0 z-50">
        <div class="max-w-md mx-4 md:mx-0 md:ml-10 mb-6 p-8 bg-gray-800 text-white rounded-lg">
          <div class="text-center">
            <p class="font-bold font-heading">Cookie Policy</p>
            <p class="mb-5 mt-3 mb-6 text-gray-400 text-sm">We use <a class="text-red-600 hover:text-red-700 underline" href="#">cookies</a> to personalise content, to provide social media features and to analyse our traffic.</p>
            <a class="inline-block mr-3 py-2 px-4 rounded-l-xl rounded-t-xl border-2 border-red-600 hover:border-red-700 bg-red-600 hover:bg-red-700 transition duration-200" href="#">Allow</a><a class="inline-block py-2 px-4 rounded-r-xl rounded-t-xl border-2 border-gray-400 hover:bg-gray-700 transition duration-200" href="#">Decline</a>
          </div>
        </div>
      </div> -->
    
      <section>
       
        <div class="py-20 bg-gray-50 radius-for-skewed">
          <div class="container px-4 mx-auto">
            <div class="max-w-xl mx-auto mb-12 text-center">
              <span class="text-red-600 font-bold">Dolor sit amet consectutar</span>
              <h2 class="text-4xl lg:text-5xl font-bold font-heading">Check our awesome team members</h2>
            </div>
            <div class="flex flex-wrap">
              <div class="mb-6 w-full md:w-1/2 lg:w-1/3 px-3">
                <div class="pb-8 bg-white rounded shadow text-center overflow-hidden">
                  <img class="mb-8 w-full h-64 object-cover" src="https://images.unsplash.com/photo-1580852300654-03c803a14e24?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=600&amp;q=80" alt="">
                  <h4 class="mb-2 text-2xl font-bold font-heading">Danny Bailey</h4>
                  <p class="text-gray-500">CEO</p>
                </div>
              </div>
              <div class="mb-6 w-full md:w-1/2 lg:w-1/3 px-3">
                <div class="pb-8 bg-white rounded shadow text-center overflow-hidden">
                  <img class="mb-8 w-full h-64 object-cover" src="https://images.unsplash.com/photo-1559548331-f9cb98001426?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=600&amp;q=80" alt="">
                  <h4 class="mb-2 text-2xl font-bold font-heading">Ian Brown</h4>
                  <p class="text-gray-500">Head of Development</p>
                </div>
              </div>
              <div class="mb-6 w-full md:w-1/2 lg:w-1/3 px-3">
                <div class="pb-8 bg-white rounded shadow text-center overflow-hidden">
                  <img class="mb-8 w-full h-64 object-cover" src="https://images.unsplash.com/photo-1488426862026-3ee34a7d66df?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=600&amp;q=80" alt="">
                  <h4 class="mb-2 text-2xl font-bold font-heading">Daisy Carter</h4>
                  <p class="text-gray-500">Product Development</p>
                </div>
              </div>
              <div class="mb-6 w-full md:w-1/2 lg:w-1/3 px-3">
                <div class="pb-8 bg-white rounded shadow text-center overflow-hidden">
                  <img class="mb-8 w-full h-64 object-cover" src="https://images.unsplash.com/photo-1600486913747-55e5470d6f40?ixlib=rb-1.2.1&amp;ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;auto=format&amp;fit=crop&amp;w=600&amp;q=80" alt="">
                  <h4 class="mb-2 text-2xl font-bold font-heading">Dennis Robertson</h4>
                  <p class="text-gray-500">Frontend Developer</p>
                </div>
              </div>
              <div class="mb-6 w-full md:w-1/2 lg:w-1/3 px-3">
                <div class="pb-8 bg-white rounded shadow text-center overflow-hidden">
                  <img class="mb-8 w-full h-64 object-cover" src="https://images.unsplash.com/photo-1484588168347-9d835bb09939?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=600&amp;q=80" alt="">
                  <h4 class="mb-2 text-2xl font-bold font-heading">Alice Bradley</h4>
                  <p class="text-gray-500">Backend Developer</p>
                </div>
              </div>
              <div class="mb-6 w-full md:w-1/2 lg:w-1/3 px-3">
                <div class="pb-8 bg-white rounded shadow text-center overflow-hidden">
                  <img class="mb-8 w-full h-64 object-cover" src="https://images.unsplash.com/photo-1604072366595-e75dc92d6bdc?ixid=MXwxMjA3fDB8MHxwcm9maWxlLXBhZ2V8MTB8fHxlbnwwfHx8&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=600&amp;q=600" alt="">
                  <h4 class="mb-2 text-2xl font-bold font-heading">Sahra Ortiz</h4>
                  <p class="text-gray-500">Product Designer</p>
                </div>
              </div>
            </div>
          </div>
        </div>
       
      </section>
    
      <section>
        
        <div class="py-20 bg-gray-900 radius-for-skewed">
          <div class="container mx-auto px-4">
            <div class="flex flex-wrap">
              <div class="w-full lg:w-1/3 mb-16 lg:mb-0">
                <a class="inline-block mb-3 text-white text-3xl font-bold leading-none" href="#">
                  <img class="mb-3 h-12" src="@/atis-assets/logo/atis/atis-mono-white.svg" alt="" width="auto">
                </a>
                <p class="mb-4 max-w-sm text-gray-400 leading-loose">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus tincidunt felis eu est.</p>
                <div>
                  <a class="inline-block w-10 mr-2 p-2 bg-gray-800 hover:bg-gray-700 rounded" href="#">
                    <img class="mx-auto" src="@/atis-assets/social/facebook.svg">
                  </a>
                  <a class="inline-block w-10 mr-2 p-2 bg-gray-800 hover:bg-gray-700 rounded" href="#">
                    <img class="mx-auto" src="@/atis-assets/social/twitter.svg">
                  </a>
                  <a class="inline-block w-10 p-2 bg-gray-800 hover:bg-gray-700 rounded" href="#">
                    <img class="mx-auto" src="@/atis-assets/social/instagram.svg">
                  </a>
                </div>
              </div>
              <div class="w-full lg:w-2/3 lg:pl-16 flex flex-wrap justify-between">
                <div class="w-full md:w-1/3 lg:w-auto mb-16 md:mb-0">
                  <h3 class="mb-6 text-2xl font-bold text-white">Products</h3>
                  <ul>
                    <li class="mb-4"><a class="text-gray-400 hover:text-gray-300" href="#">Services</a></li>
                    <li class="mb-4"><a class="text-gray-400 hover:text-gray-300" href="#">About Us</a></li>
                    <li class="mb-4"><a class="text-gray-400 hover:text-gray-300" href="#">News and Stories</a></li>
                    <li><a class="text-gray-400 hover:text-gray-300" href="#">Roadmap</a></li>
                  </ul>
                </div>
                <div class="w-full md:w-1/3 lg:w-auto mb-16 md:mb-0">
                  <h3 class="mb-6 text-2xl font-bold text-white">Important Links</h3>
                  <ul>
                    <li class="mb-4"><a class="text-gray-400 hover:text-gray-300" href="#">Organization Team</a></li>
                    <li class="mb-4"><a class="text-gray-400 hover:text-gray-300" href="#">Our Journeys</a></li>
                    <li class="mb-4"><a class="text-gray-400 hover:text-gray-300" href="#">Pricing Plans</a></li>
                    <li class="mb-4"><a class="text-gray-400 hover:text-gray-300" href="#">Roadmap</a></li>
                    <li class="mb-4"><a class="text-gray-400 hover:text-gray-300" href="#">Terms &amp; Conditions</a></li>
                    <li><a class="text-gray-400 hover:text-gray-300" href="#">Privacy Policy</a></li>
                  </ul>
                </div>
                <div class="w-full md:w-1/3 lg:w-auto">
                  <h3 class="mb-6 text-2xl font-bold text-white">Company</h3>
                  <ul>
                    <li class="mb-4"><a class="text-gray-400 hover:text-gray-300" href="#">About Us</a></li>
                    <li class="mb-4"><a class="text-gray-400 hover:text-gray-300" href="#">Jobs</a></li>
                    <li class="mb-4"><a class="text-gray-400 hover:text-gray-300" href="#">Press</a></li>
                    <li><a class="text-gray-400 hover:text-gray-300" href="#">Contact Us</a></li>
                  </ul>
                </div>
              </div>
            </div>
            <p class="lg:text-center text-sm text-gray-400 border-t border-gray-800 pt-12 mt-16">&copy; 2021. All rights reserved.</p>
          </div>
        </div>
        
      </section>
    </div>
</template>

<script>
export default {}
</script>
