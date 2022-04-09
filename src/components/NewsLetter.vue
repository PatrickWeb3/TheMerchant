<template>
  <div class="bg-gray-900 py-20 sm:py-24">
    <div class="relative sm:py-16">
      <div class="mx-auto max-w-md px-4 sm:max-w-3xl sm:px-10 md:px-6 lg:max-w-5xl lg:px-8">
        <div class="relative px-6 py-10 bg-gray-200 overflow-hidden shadow-xl sm:px-12 sm:py-20">
          <div class="relative">
            <div class="sm:text-center">
              <h2 class="text-3xl font-semibold text-gray-800 tracking-tight sm:text-4xl uppercase lg:text-center">
                  <span class="block md:hidden">Subscribe to </span>
                  <span class="font-bold text-blue-500 md:hidden">our Newsletter</span>
                  <span class="hidden md:block">
                      Subscribe to our 
                      <span class="font-bold text-blue-500 hidden md:inline">Newsletter</span>
                  </span>
                  
              </h2>
              <p class="mt-2 mx-auto max-w-sm md:max-w-2xl text-lg text-gray-600 md:text-center">Get 10% Off on your first purchase with your email sign-up with a few clicks!</p>
            </div>
            <form action="#" class="mt-12 sm:mx-auto sm:max-w-lg sm:flex">
              <div class="min-w-0 flex-1">
                <label for="cta-email" class="sr-only">Email address</label>
                <input id="cta-email" type="email" class="block w-full border border-transparent px-5 py-3 text-gray-900 text-md placeholder-gray-500 shadow-sm focus:outline-none focus:border-transparent focus:ring-2 focus:ring-white focus:ring-offset-2 focus:ring-gray-400" placeholder="Enter your email" />
              </div>
              <div class="mt-4 sm:mt-0 sm:ml-3">
                <button type="submit" class="block w-full tracking-wide border border-transparent px-5 py-3 border border-transparent shadow-sm text-md font-medium text-white bg-blue-500 hover:bg-blue-600 focus:outline-none focus:ring-2 focus:ring-offset-1 focus:ring-offset-gray-200 focus:ring-blue-700">Subscribe</button>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>