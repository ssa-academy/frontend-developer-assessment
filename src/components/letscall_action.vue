<script setup>
import { ref } from "vue";
</script>

<template>
  <section class="relative pb-[250px]">
          <img class="absolute right-0 -bottom-0" src="src/assets/bg-decals3.svg" alt="">
    <div class="relative max-w-screen-xl px-4 py-8 mx-auto lg:py-16 lg:px-6 mb">

      <div class="max-w-screen-sm mx-auto mb-8 text-center lg:mb-16">
        <h2
          class="mb-4 text-3xl font-bold tracking-tight text-gray-800 lg:text-4xl"
        >
          Lets Call to Action
        </h2>
        <p class="font-light text-gray-700 sm:text-xl">
          Another Section content goes here
        </p>
      </div>
      <div class="grid gap-8 lg:grid-cols-2">
        <article
          class="grid gap-8 p-6 bg-yellow-500 border border-gray-200 rounded-lg shadow-md lg:grid-cols-2"
        >
          <div class="flex flex-col items-center text-gray-100">

            <div class="flex items-center justify-between">
              <div class="flex items-center space-x-4">
                <img
                  class="w-[200px] h-full rounded-full pb-12"
                  src="src/assets/badge.laravel-mix.svg"
                  alt="Jese Leos avatar"
                />
              </div>
            </div>
             <span class="block px-3 py-[4px]  font-medium bg-yellow-800 rounded-[30px]"> Automation </span>
          </div>
          <div>
                      <span
              class="inline-flex mt-12 text-lg font-medium rounded items-right text-primary-800"
            >
              Roll out
            </span>
            <h2 class="mb-2 text-2xl font-bold tracking-tight text-gray-100">
              <a class="text-gray-100" href="#">Automatic Prototypiong</a>
            </h2>
            <p class="mb-5 font-light text-gray-100">
              Static websites are now used to bootstrap lots of websites and are
              becoming the basis for a variety of tools that even influence both
              web designers and developers influence both web designers and
              developers.
            </p>
          </div>
        </article>
                <article
          class="grid gap-8 p-6 border border-gray-200 rounded-lg shadow-md bg-cyan-500 lg:grid-cols-2 "
        >
          <div class="flex flex-col items-center text-gray-100">

            <div class="flex items-center justify-between">
              <div class="flex items-center space-x-4">
                <img
                  class="w-[200px] h-full rounded-full pb-12"
                  src="src/assets/badge.how-to-read-code.svg"
                  alt="Jese Leos avatar"
                />
              </div>
            </div>
             <span class="block px-3 py-[4px]  font-medium rounded-[30px] bg-cyan-800"> Simplicity </span>
          </div>
          <div>
                      <span
              class="inline-flex mt-12 text-lg font-medium rounded items-right text-primary-800"
            >
              SIP COFFEE
            </span>
            <h2 class="mb-2 text-2xl font-bold tracking-tight text-gray-100">
              <a class="text-gray-100" href="#">Complexity Simplicity</a>
            </h2>
            <p class="mb-5 font-light text-gray-100">
             I know too many  backend developers who are stifled by one glaring phobia:css.How do you construct a layout when nothing line up ?
            </p>
          </div>
        </article>
      </div>
    </div>
  </section>
</template>

