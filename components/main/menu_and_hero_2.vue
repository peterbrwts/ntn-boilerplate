<template>
  <section class="pb-20">
    <nav class="flex justify-between items-center py-8 px-4 xl:px-10">
      <a class="text-lg font-semibold" href="#"
        ><img class="h-7" src="zeus-assets/logo/logo-zeus-red.svg" alt="" width="auto"
      /></a>
      <div class="lg:hidden">
        <button class="navbar-burger flex items-center p-3 hover:bg-gray-50 rounded">
          <svg class="block h-4 w-4" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
            <title>Mobile menu</title>
            <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path>
          </svg>
        </button>
      </div>
      <ul class="hidden lg:flex lg:ml-auto lg:mr-12 lg:items-center lg:w-auto lg:space-x-12">
        <li><a class="text-sm font-medium" href="#">About</a></li>
        <li><a class="text-sm font-medium" href="#">Company</a></li>
        <li><a class="text-sm font-medium" href="#">Services</a></li>
        <li><a class="text-sm font-medium" href="#">Testimonials</a></li>
      </ul>
      <div class="hidden lg:block">
        <a
          class="inline-block py-3 px-8 text-sm leading-normal font-medium bg-red-50 hover:bg-red-100 text-red-500 rounded transition duration-200"
          href="#"
          >Contact Us</a
        >
      </div>
    </nav>
    <div class="container px-4 mx-auto pt-12">
      <div class="flex flex-wrap items-center -mx-4">
        <div class="w-full md:w-1/2 px-4 mb-6 md:mb-0">
          <span class="font-semibold text-xs text-blue-400">What's new at Shuffle</span>
          <h2 class="mt-8 mb-6 lg:mb-12 text-4xl lg:text-5xl font-semibold">
            Take care of your performance every day.
          </h2>
          <div class="max-w-lg mb-6 lg:mb-12">
            <p class="text-xl text-gray-500">
              Build a well-presented brand that everyone will love. Take care to develop resources continually and
              integrity them with previous projects.
            </p>
          </div>
          <div class="flex flex-wrap">
            <a
              class="inline-block px-6 py-4 mb-3 mr-4 text-sm font-medium leading-normal bg-red-400 hover:bg-red-300 text-white rounded transition duration-200"
              href="#"
              >Track your performance</a
            ><a
              class="inline-block px-6 py-4 mb-3 text-sm font-medium leading-normal hover:text-gray-700 rounded border"
              href="#"
              >Learn More</a
            >
          </div>
        </div>
        <div class="relative w-full md:w-1/2 px-4">
          <img
            class="hidden lg:block lg:absolute top-0 right-0 z-10 lg:mt-28"
            src="zeus-assets/icons/dots/yellow-dot-right-shield.svg"
            alt=""
          /><img class="relative" src="zeus-assets/images/z-picture.png" alt="" /><img
            class="hidden lg:block lg:absolute bottom-0 lg:left-0 lg:ml-6 lg:mb-20"
            src="zeus-assets/icons/dots/blue-dot-left-bars.svg"
            alt=""
          />
        </div>
      </div>
    </div>
    <div class="hidden navbar-menu relative z-50">
      <div class="navbar-backdrop fixed inset-0 bg-gray-800 opacity-25"></div>
      <nav class="fixed top-0 left-0 bottom-0 flex flex-col w-5/6 max-w-sm py-6 px-6 bg-white border-r overflow-y-auto">
        <div class="flex items-center mb-8">
          <a class="mr-auto text-lg font-semibold leading-none" href="#"
            ><img class="h-7" src="zeus-assets/logo/logo-zeus-red.svg" alt="" width="auto"
          /></a>
          <button class="navbar-close">
            <svg
              class="h-6 w-6 text-gray-500 cursor-pointer hover:text-gray-500"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
            </svg>
          </button>
        </div>
        <div>
          <ul>
            <li class="mb-1">
              <a class="block p-4 text-sm font-medium text-gray-900 hover:bg-gray-50 rounded" href="#">About</a>
            </li>
            <li class="mb-1">
              <a class="block p-4 text-sm font-medium text-gray-900 hover:bg-gray-50 rounded" href="#">Company</a>
            </li>
            <li class="mb-1">
              <a class="block p-4 text-sm font-medium text-gray-900 hover:bg-gray-50 rounded" href="#">Services</a>
            </li>
            <li class="mb-1">
              <a class="block p-4 text-sm font-medium text-gray-900 hover:bg-gray-50 rounded" href="#">Testimonials</a>
            </li>
          </ul>
        </div>
        <div class="mt-auto">
          <div class="pt-6">
            <a
              class="block py-3 text-center text-sm leading-normal bg-red-50 hover:bg-red-100 text-red-300 font-semibold rounded transition duration-200"
              href="#"
              >Contact Us</a
            >
          </div>
          <p class="mt-6 mb-4 text-sm text-center text-gray-500">
            <span>© 2021 All rights reserved.</span>
          </p>
        </div>
      </nav>
    </div>
  </section>
</template>