<template>
    <div class="bg-gray-100">
        <!-- Top Layer -->
        <div class="bg-gray-900 p-1.5">
            <h2 
                class="text-sm text-white text-center tracking-tighter uppercase font-thin">
                Reimagining 
                <span class="text-blue-400 font-semibold">Recovery</span>
            </h2>
        </div>
        <!-- Bottom Layer -->
        <div class="mx-auto max-w-7xl lg:grid lg:grid-cols-3 p-2">
            <div class="lg:py-1  px-2 sm:px-6 lg:px-8">
                <h2 class="text-gray-500 text-sm hidden lg:block  ">customercare@themerchant.cc</h2>
            </div>
            <div class="text-center text-sm">
                <label for="search" class="sr-only">Search</label>
                <div class="relative flex justify-center">
                    <input 
                        id="search" name="search" placeholder="Search" type="search" 
                        class="w-3/5 lg:w-full py-1 pl-5 bg-gray-200 placeholder-gray-400 focus:outline-none text-gray-900 focus:text-gray-800 focus:placeholder-gray-400 ring-1 ring-gray-200 focus:ring-gray-300 focus:border-gray-300"    
                    />
                    <button class="bg-gray-300 px-3 ring-1 ring-gray-300">
                        <i class="fa-solid fa-magnifying-glass text-gray-400"></i>
                    </button>
                </div>
            </div>
            <div class="text-gray-500 lg:py-1 text-right text-sm hidden lg:block max-w-7xl px-2 sm:px-6 lg:px-8">
                <!-- Flag Icon -->
                <!-- Make into dropdown menu -->
                <h2>USD</h2>
            </div>
        </div>
    </div>
</template>

<style>

    #search::-webkit-search-cancel-button {
        position:relative;
        right:10px;
    }

</style>