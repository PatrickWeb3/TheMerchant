<template>
    <div class="heroImage bg-cover bg-center relative">
        <div class="absolute top-0 left-0 h-full w-full bg-black opacity-70"></div>

         <div class="absolute top-1/2 left-1/2 lg:left-1/3 transform -translate-x-1/2 -translate-y-1/2">
            <div class="max-w-md sm:max-w-2xl">
                <h3 class="text-gray-100 tracking-widest">
                <!-- Mobile Upper Header -->
                <span class="block leading-none">Merchant Fitness</span>
                </h3>
                <h1 class="text-white text-4xl font-bold tracking-tight lg:py-0">
                <!-- Mobile Header Text-->
                <span class="block lg:hidden">Rest Better</span>
                <span class="flex flex-col lg:hidden">& Go Further</span>
                <!-- Desktop Header Text -->
                <span class="hidden lg:block">Rest Better & Go Further</span>
                <span class="hidden lg:block text-blue-400">WITH A FEW CLICKS.</span>
                </h1>
                <p class="text-gray-200 font-thin tracking-wide">
                <!-- Mobile Lower Text -->
                <span class="block lg:hidden">We offer the best portable </span>
                <span class="block lg:hidden leading-none">massage guns & accessories.</span>
                <!-- Desktop Lower Text -->
                <span class="hidden lg:block">We offer the best portable massage guns & accessories.</span>
                <span class="hidden lg:block pb-1 ">Click below to purchase today.</span>
                </p>
                <div class="pt-5">
                <a href="#" 
                    class="px-10 sm:px-16 lg:px-32 py-3 border border-transparent shadow-sm text-sm font-medium text-white bg-blue-500 hover:bg-blue-600 focus:outline-none focus:ring-2 focus:ring-offset-1 focus:ring-offset-white focus:ring-blue-700">
                    Purchase <span class="">Here</span>
                </a>
                </div>
            </div>
        </div>
    </div>
</template>

<style>

    .heroImage {
        background-image: url('../static/heroimage2.jpg');
        height:85vh;
    }

</style>