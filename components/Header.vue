<template>
  <div >
    <header class="text-gray-600 body-font bg-red-700">
  <div class="container px-5 py-2 mx-auto flex items-center sm:flex-row flex-col">
    <span class="inline-flex sm:ml-auto sm:mt-0 mt-4 justify-center sm:justify-start cursor-pointer ">
      <nuxt-link to="" class="text-white">
        <svg fill="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
          <path d="M18 2h-3a5 5 0 00-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 011-1h3z"></path>
        </svg>
      </nuxt-link>
      <nuxt-link to="" class="ml-3 text-white">
        <svg fill="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
          <path d="M23 3a10.9 10.9 0 01-3.14 1.53 4.48 4.48 0 00-7.86 3v1A10.66 10.66 0 013 4s-4 9 5 13a11.64 11.64 0 01-7 2c9 5 20 0 20-11.5a4.5 4.5 0 00-.08-.83A7.72 7.72 0 0023 3z"></path>
        </svg>
      </nuxt-link>
      <nuxt-link to="" class="ml-3 text-white">
        <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
          <rect width="20" height="20" x="2" y="2" rx="5" ry="5"></rect>
          <path d="M16 11.37A4 4 0 1112.63 8 4 4 0 0116 11.37zm1.5-4.87h.01"></path>
        </svg>
      </nuxt-link>
      <nuxt-link to="" class="ml-3 text-white">
        <svg fill="currentColor" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="0" class="w-5 h-5" viewBox="0 0 24 24">
          <path stroke="none" d="M16 8a6 6 0 016 6v7h-4v-7a2 2 0 00-2-2 2 2 0 00-2 2v7h-4v-7a6 6 0 016-6zM2 9h4v12H2z"></path>
          <circle cx="4" cy="4" r="2" stroke="none"></circle>
        </svg>
      </nuxt-link>
    </span>
    <div class="inline-flex sm:ml-auto sm:mt-0 mt-4 justify-center sm:justify-start cursor-pointer flex-1">
      <span class="ml-3 text-white">hallo@gamil.com</span>
    <span class="ml-3 text-white">8960972920, 7007519673</span>

    </div>
    
    <span class="inline-flex sm:ml-auto sm:mt-0 mt-4 justify-center sm:justify-start cursor-pointer">
      <nuxt-link to="/admin" class="text-white font-bold">ADMIN</nuxt-link>
    </span>
  </div>
</header>
    <!-- <section class="overflow-hidden"> -->
    <nav class="relative px-6 py-4 flex justify-between items-center bg-white z-50">
      <a class="text-3xl font-bold leading-none" href="#">
        <img
          class="h-10 "
          src="@/atis-assets/logo/apexlogo.svg"
          alt=""
          width="auto"
        />
      </a>
      <div class="lg:hidden">
        <button class="navbar-burger flex items-center text-gray-400 p-3">
          <svg
            class="block h-4 w-4 fill-current"
            viewbox="0 0 20 20"
            xmlns="http://www.w3.org/2000/svg"
          >
            <title>Mobile menu</title>
            <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path>
          </svg>
        </button>
      </div>
      <ul
        class="
          hidden
          absolute
          top-1/2
          left-1/2
          transform
          -translate-y-1/2 -translate-x-1/2
          lg:flex lg:mx-auto lg:flex lg:items-center lg:w-auto lg:space-x-6
        "
      >
        <li>
          <nuxt-link to="/" class="text-base font-semibold text-gray-800  hover:text-red-500"
            >Home</nuxt-link
          >
        </li>
        <li class="text-gray-800">
          <svg
            class="w-3 h-4 current-fill"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewbox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M12 5v.01M12 12v.01M12 19v.01M12 6a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2z"
            ></path>
          </svg>
        </li>
        <li>
          <nuxt-link
            to=""
            class="text-base font-semibold text-gray-800  hover:text-red-500"
            >About</nuxt-link
          >
          <ul class="sub-menu z-40">
            <li><nuxt-link to="/aboutus">About Us</nuxt-link></li>
            <li><nuxt-link to="/director">Director's Message</nuxt-link></li>
            <li><nuxt-link to="/mission">Mission & Vision</nuxt-link></li>
            <li><nuxt-link to="/methology">Teaching Methology</nuxt-link></li>
            <li><nuxt-link to="/privacypolicy">Achievement</nuxt-link></li>
            
          </ul>
        </li>
        <li class="text-gray-800 font-bold">
          <svg
            class="w-3 h-4 current-fill"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewbox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M12 5v.01M12 12v.01M12 19v.01M12 6a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2z"
            ></path>
          </svg>
        </li>
        <li>
          <nuxt-link to="/courses" class="text-base font-semibold text-gray-800  hover:text-red-500"
            >Courses </nuxt-link
          >
            <ul class="sub-menu">
             <li><nuxt-link to="/oneyeartarget">One Year Target Courses</nuxt-link></li>
             <li><nuxt-link to="/oneyear">One Year Courses</nuxt-link></li>
             <li><nuxt-link to="/twoyear">Two Year Courses</nuxt-link></li>
            <!-- <li><nuxt-link to="/jeeadvance">JEE Advance</nuxt-link></li>
            <li><nuxt-link to="/jeemain">JEE Main</nuxt-link></li> -->
            <li><nuxt-link to="#">Pre-Medical</nuxt-link></li>
            <li><nuxt-link to="/foundation">Foundation</nuxt-link></li>
            <li><nuxt-link to="/onlinecourse">Online Course/LIVE</nuxt-link></li>
            <li><nuxt-link to="/dlp">Distance Learning Program (DLP)</nuxt-link></li>
          </ul>
        </li>
        <li class="text-gray-800 font-bold">
          <svg
            class="w-3 h-4 current-fill"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewbox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M12 5v.01M12 12v.01M12 19v.01M12 6a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2z"
            ></path>
          </svg>
        </li>
        <li>
          <nuxt-link to="" class="text-base font-semibold text-gray-800  hover:text-red-500"
            >Admission <span class="caret"></span></nuxt-link
          >
          <ul class="sub-menu">
            <li><nuxt-link to="/admissionform">Apply Online</nuxt-link></li>
            <li><nuxt-link to="#">Admission Procedure</nuxt-link></li>
            <li><nuxt-link to="#">Term & Condition policy</nuxt-link></li>
            <li><nuxt-link to="#">Time Table</nuxt-link></li>
          </ul>
        </li>
        <li class="text-gray-800 font-bold">
          <svg
            class="w-3 h-4 current-fill"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewbox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M12 5v.01M12 12v.01M12 19v.01M12 6a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2z"
            ></path>
          </svg>
        </li>
        <li>
          <nuxt-link to="/studentzone" class="text-base font-semibold text-gray-800  hover:text-red-500"
            >Student</nuxt-link
          >
          <ul class="sub-menu">
            <li><nuxt-link to="/studentgallery">Students Gallery</nuxt-link></li>
            <li><nuxt-link to="/feedetails">Fee Details</nuxt-link></li>
           <li><nuxt-link to="/privacypolicy">Privacy Policy</nuxt-link></li>
            <li><nuxt-link to="/faq">FAQs</nuxt-link></li>
            <li><nuxt-link to="#">Time Table</nuxt-link></li>
          </ul>
        </li>
        <li class="text-gray-800 font-bold">
          <svg
            class="w-3 h-4 current-fill"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewbox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M12 5v.01M12 12v.01M12 19v.01M12 6a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2z"
            ></path>
          </svg>
        </li>
        <li>
          <nuxt-link to="/contactus" class="text-base font-semibold text-gray-800 hover:text-red-500"
            >Contact</nuxt-link
          >
        </li>
      </ul>
      <a
        class="
          hidden
          lg:block
          py-2
          px-6
          bg-red-600
          hover:bg-red-700
          text-sm text-white
          font-bold
          rounded-l-xl rounded-t-xl
          transition
          duration-200
        "
        href="#"
        >Help Desk</a
      >
    </nav>
    <!-- <div class="relative bg-gray-50 pt-20 pb-24 lg:py-40 overflow-hidden">
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
        </div> -->
    <!-- <div class="hidden navbar-menu relative z-50">
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
        </div> -->
    <!-- </section> -->
  </div>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<style>
.sub-menu > li {
  display: block;
  position: relative;
  -webkit-transition: all 0.4s ease;
  transition: all 0.4s ease;
}
ul > li > .sub-menu > li:hover > a {
  color: #fff;
  background: rgb(241, 61, 61);
}

li:hover > .sub-menu {
  opacity: 1;
  visibility: visible;
  /* display: absolute; */
}
.sub-menu {
  position: absolute;
  top: 40%;
  margin-top: 25px;
  /* left: 100%; */
  z-index: 9999999999;
  float: left;
  min-width: 220px;
  padding: 0px 0px;
  text-align: left;
  list-style: none;
  background-color: #fff;
  background-clip: padding-box;
  opacity: 0;
  border-radius: 0px;
  visibility: hidden;
  -webkit-transition: opacity 0.4s ease, visibility 0.4s ease;
  transition: opacity 0.4s ease, visibility 0.4s ease;
  -webkit-box-shadow: 0px 10px 18px rgba(0, 0, 0, 0.1);
  box-shadow: 0px 10px 18px rgba(0, 0, 0, 0.1);
}
.sub-menu > li > a {
  font-size: 15px;
  color: #333;
  font-weight: 400;
  padding: 12px 30px;
  display: block;
  line-height: 20px;
  white-space: nowrap;
  position: relative;
  -webkit-transition: all 0.4s ease;
  transition: all 0.4s ease;
}
</style>
