<template>

    <header class=" bg-primary lg:px-16 px-6 bg-white flex flex-wrap items-center lg:py-0 lg:py-2 justify-between">
      <div class="flex justify-between items-center">
          <nuxt-link to="/">
            <h1 class=" text-5xl text-white">COMPANY XYZ</h1>
              <!-- <img src="https://res.cloudinary.com/alexoc/image/upload/v1563162452/Protec%20EA%20Logo.svg" class="h-20 md:h-28" /> -->
          </nuxt-link>
      </div>

       <label for="menu-toggle" class="pointer-cursor lg:hidden block"><svg class="fill-current text-white" xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 20 20"><title>menu</title><path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path></svg></label>
      <input class="hidden" type="checkbox" id="menu-toggle" />

      <div class="hidden lg:flex lg:items-center lg:w-auto w-full" id="menu">
        <nav>
          <ul class="lg:flex items-center justify-between text-gray-700 pt-4 lg:pt-0 ">

              <!-- <nuxt-link to="/about" class="mx-2 lg:p-4 py-3 px-0 block border-b-2 border-transparent hover:border-gray-300 text-center text-white md:text-xl">About Us</nuxt-link>

              <nuxt-link to="/services" class="mx-2 lg:p-4 py-3 px-0 block border-b-2 border-transparent hover:border-gray-300 text-center text-white md:text-xl">Services</nuxt-link>

              <nuxt-link to="/courses" class="mx-2 lg:p-4 py-3 px-0 block border-b-2 border-transparent hover:border-gray-300 text-center text-white md:text-xl">Courses</nuxt-link> -->

              <!-- <nuxt-link to="/latest_news" class="lg:p-4 py-3 px-0 block border-b-2 border-transparent hover:border-gray-300 text-center text-white md:text-xl">Latest News</nuxt-link>
  -->
              <!-- <a class="lg:p-4 py-3 px-0 block border-b-2 border-transparent hover:border-gray-300 lg:mb-0 mb-2 text-center" href="#">Support</a> -->

              <nuxt-link to="/contact"><a class="mx-2 bg-secondary text-white lg:p-4 py-3 rounded-r rounded-l md:text-xl block border-b-2 border-transparent hover:border-gray-300 lg:mb-0 mb-2 text-center" href="#">Contact Us</a></nuxt-link>

          </ul>
        </nav>


      </div>

      </header>
</template>

<script>
export default {
  head () {
    return {
      link: [
        { rel: 'stylesheet', href: 'https://fonts.googleapis.com/css?family=Roboto&display=swap' }
      ]
    }
  }
}
</script>

<style>

    #menu-toggle:checked + #menu {
        display: block;
    }

</style>
