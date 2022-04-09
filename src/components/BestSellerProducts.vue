<template>
    <div class="h-full lg:h-full bg-gray-900">
        <div class="h-full lg:h-3/4 bg-gray-100 text-center pb-20 ">
            <div class="max-w-7xl mx-auto">
                <h1 class="text-gray-800 uppercase font-semibold tracking-wide text-2xl lg:text-3xl py-10">Popular Products</h1>
                <div class="bg-white mx-10 sm:w-2/3 lg:w-2/3 sm:mx-auto max-w-7xl mx-auto">
                    <div class="flex flex-col lg:flex-row justify-evenly border-2 border-blue-400 rounded shadow-lg">
                        
                        <div class="p-2 pt-4 lg:w-1/2 shadow relative">
                        <a href="#">
                        <div class="absolute w-full h-full left-0 top-0 hover:bg-black hover:opacity-20 transition ease-in-out delay-100"></div>
                            <a class="text-lg font-semibold" href="#">MassagePro - Silver</a>
                            <h2 class="text-red-500 tracking-tighter text-lg relative">$105.00</h2>
                            <img class="mx-auto h-72 w-72 lg:h-96 lg:w-96" src="../static/popularproduct1.jpg" alt="">
                        </a>
                        </div>
                        <div class="p-2 pt-4 lg:w-1/2 shadow relative">
                        <a href="#">
                        <div class="absolute w-full h-full left-0 top-0 hover:bg-black hover:opacity-20 transition ease-in-out delay-100"></div>
                            <a class="text-lg font-semibold" href="#">MassagePro - Black</a>
                            <h2 class="text-red-500 tracking-tighter text-lg relative">$115.00</h2>
                            <img class="mx-auto h-72 w-72 lg:h-96 lg:w-96" src="../static/popularproduct2.webp" alt="">
                        </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="max-w-7xl mx-auto">
        <h2 class="text-white text-2xl lg:text-3xl uppercase border-b border-gray-100 w-2/5 sm:w-3/5 md:w-2/3 lg:w-11/12 mx-auto pb-10 tracking-wide font-semibold text-center pt-20 max-w-2xl">We provide</h2>
        <div class="md:grid md:grid-cols-2 lg:grid-cols-4 lg:p-0 p-20 space-y-20 md:space-y-0 pt-10">
            <div class="text-gray-100 flex flex-col items-center lg:py-20">
                <TruckIcon class="h-12 w-12" />
                <h2 class="text-white font-semibold text-xl pt-2">Free Shipping</h2>
                <h3 class="text-gray-400 leading-none">on all orders over $100</h3>
            </div>
            <div class="text-gray-100 flex flex-col items-center lg:py-20">
                <RefreshIcon class="h-12 w-12" />
                <h2 class="text-white font-semibold text-xl pt-2">Easy & Fast Return</h2>
                <h3 class="text-gray-400 leading-none">30 days money guarantee</h3>
            </div>
            <div class="text-gray-100 flex flex-col items-center md:pt-20">
                <LockClosedIcon class="h-12 w-12" />
                <h2 class="text-white font-semibold text-xl pt-2">100% Secure Payment</h2>
                <h3 class="text-gray-400 leading-none">Paypal/ Mastercard/ Visa</h3>
            </div>
            <div class="text-gray-100 flex flex-col items-center md:pt-20">
                <SupportIcon class="h-12 w-12" />
                <h2 class="text-white font-semibold text-xl pt-2">24/7 Customer Help</h2>
                <h3 class="text-gray-400 leading-none">Online customer support</h3>
            </div>
        </div>
        </div>
    </div>
</template>

<script>
import { TruckIcon, RefreshIcon, LockClosedIcon, SupportIcon } from '@heroicons/vue/outline'

export default {
  components: {
    TruckIcon,
    RefreshIcon,
    LockClosedIcon,
    SupportIcon,
  },
}
</script>