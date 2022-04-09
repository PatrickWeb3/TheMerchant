<template>
    <div class="bg-gray-900 h-full">
        <div class="">
            <div class="lg:max-w-2xl mx-auto">
                <h1 class="text-white text-2xl lg:text-3xl uppercase border-b border-gray-100 w-2/5 sm:w-3/5 md:w-2/3 lg:w-11/12 mx-auto pb-10 tracking-wide font-semibold text-center pt-20">About Us</h1>
                    <span class="flex flex-col lg:flex-row lg:max-w-xl lg:mx-auto lg:pt-10">
                        <p class="text-gray-400 max-w-xl mx-auto p-10 lg:pl-0 leading-relaxed">The Merchant Fitness (TMF) provides innovative fitness and recovery tools to help alleviate muscle soreness, neck tension, lower back pain, and general tightness. Operating out of Kansas City, TMF helps gym-goers, athletes, trainers, and many other walks of life continue performing at their best. Our portable massage guns, smart scales, and smartwatches keep you in top shape to achieve your goals. Find us on Instagram by searching (@massagepro_tmf) or visit The Merchant Fitness Facebook page to stay updated.</p>
                        <span class="flex lg:flex-col justify-center space-x-10 lg:space-x-0 lg:space-y-5 text-4xl lg:text-5xl text-gray-300">
                            <a href=""><i class="fa-brands fa-instagram-square hover:text-gray-100"></i></a>
                            <a href=""><i class="fa-brands fa-facebook-square hover:text-gray-100"></i></a>
                            <a href=""><i class="fa-brands fa-twitter-square hover:text-gray-100"></i></a>
                        </span>
                    </span>
            </div>

            <div class="lg:max-w-2xl mx-auto flex flex-col pb-10">
                <h1 class="text-white text-2xl lg:text-3xl uppercase mx-auto tracking-wide font-semibold text-center pt-20">
                    JOIN THE
                    <span class="text-blue-400">TMF MOVEMENT</span>    
                </h1>
                <h2 class="text-gray-400 text-center leading-none">MassagePro - The Perfect Recovery Tool for Everyone</h2>
            </div>
            <div class="sliderImage bg-cover bg-center lg:bg-top bg-full relative">
                <div class="absolute top-0 left-0 h-full w-full bg-black opacity-40"></div>
                <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2">
                    <div class="max-w-md sm:max-w-2xl text-center">
                        <h3 class="text-gray-100 tracking-widest">
                            <span class="block leading-none">Merchant Fitness</span>
                        </h3>
                        <h1 class="text-white text-4xl font-bold tracking-tight lg:py-0">
                            <!-- Mobile Header Text-->
                            <span class="block lg:hidden">Rest Better</span>
                            <span class="flex flex-col lg:hidden">& Go Further</span>
                            <!-- Desktop Header Text -->
                            <span class="hidden lg:block">Rest Better & Go Further</span>
                            <span class="hidden lg:block text-blue-500">WITH A FEW CLICKS.</span>
                        </h1>
                        <p class="text-gray-200 font-thin tracking-wide">
                            <span class="block">Join the TMF Movement Today</span>
                        </p>
                        <div class="pt-5">
                            <a href="#" 
                                class="px-16 lg:px-32 py-3 border border-transparent shadow-sm text-sm font-medium text-white bg-blue-500 hover:bg-blue-600 focus:outline-none focus:ring-2 focus:ring-offset-1 focus:ring-offset-white focus:ring-blue-700">
                                Purchase <span class="">Here</span>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style>

    .sliderImage {
        background-image: url('../static/aboutimage.webp');
        height:80vh;
    }

</style>