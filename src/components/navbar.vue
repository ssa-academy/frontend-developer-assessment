<script setup>
import { ref } from 'vue'

</script>

<template>
 <nav>
  <div class=" mx-auto max-w-7xl sm:px-6 lg:pl-[0]">
    <div class="relative flex items-center justify-between h-16">
      <div class="absolute inset-y-0 left-0 flex items-center sm:hidden">
        <!-- Mobile menu button-->
        <button type="button" class="inline-flex items-center justify-center p-2 text-gray-400 rounded-md hover:bg-gray-700 hover:text-white focus:outline-none focus:ring-2 focus:ring-inset focus:ring-white" aria-controls="mobile-menu" aria-expanded="false">
          <span class="sr-only">Open main menu</span>
          <!--
            Icon when menu is closed.

            Menu open: "hidden", Menu closed: "block"
          -->
          <svg class="block w-6 h-6" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true">
            <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
          </svg>
          <!--
            Icon when menu is open.

            Menu open: "block", Menu closed: "hidden"
          -->
          <svg class="hidden w-6 h-6" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true">
            <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" />
          </svg>
        </button>
      </div>
      <div class="flex items-center justify-center flex-1 sm:items-stretch sm:justify-start">
        <div class="flex items-center flex-shrink-0">
          <img class="block w-auto h-12 lg:hidden" src="src/assets/logo1.svg" alt="Your Company">
          <img class="hidden w-auto h-12 lg:block" src="src/assets/logo1.svg" alt="Your Company">
          <h1 class="px-3 py-2  text-gray-800 font-bold rounded-md text-[1.5rem] hover:text-blue-700">Protoapp</h1>
        </div>
        <div class="hidden sm:ml-6 sm:block">
          <div class="flex space-x-4">
            <a href="#" class="px-3 py-2 font-normal  text-gray-800 rounded-md text-[1.5rem] hover:text-blue-700">Home</a>
          </div>
        </div>
      </div>
      <div class="absolute inset-y-0 right-0 flex items-center pr-2 sm:static sm:inset-auto sm:ml-6 sm:pr-0">
      </div>
    </div>
  </div>

  <!-- Mobile menu, show/hide based on menu state. -->
  <div class="sm:hidden" id="mobile-menu">
    <div class="px-2 pt-2 pb-3 space-y-1">
      <a href="#" class="block px-3 py-2 text-base font-medium text-gray-300 rounded-md hover:bg-gray-700 hover:text-white">Home</a>
    </div>
  </div>
</nav>

</template>

