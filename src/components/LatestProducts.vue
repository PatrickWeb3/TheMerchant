<template>
    <div class="bg-gray-100 lg:h-max-content">
        <div class="max-w-7xl mx-auto pt-20 lg:hidden">
            <h1 class="text-gray-800 uppercase font-semibold tracking-wide text-2xl lg:text-3xl text-center">Latest Products</h1>
            <h2 class="text-gray-500 text-center leading-none">Lightweight, Stylish, Portable Massage Guns & Accessories</h2>
        </div>
        <div class="flex flex-col lg:flex-row max-w-7xl mx-auto">
            <div class="lg:flex flex-col lg:w-3/5 ">
                <div class="lg:pt-20 text-center">
                    <h1 class="hidden lg:block text-gray-800 uppercase font-semibold tracking-wide text-2xl lg:text-3xl">Latest Products</h1>
                    <h2 class="hidden lg:block text-gray-500 leading-none">Lightweight, Stylish, Portable Massage Guns & Accessories</h2>
                </div>
                <div class="grid grid-cols-2 md:grid-cols-3 px-10 py-20 lg:pt-10">
                    <div class="flex flex-col items-center mb-8">
                        <div class="relative">
                            <div class="absolute w-full h-full left-0 top-0 hover:bg-black hover:opacity-20 transition ease-in-out delay-10"></div>
                            <img class="mx-auto h-40 w-40 lg:h-32 lg:w-32 shadow-md border-2 border-blue-400 rounded shadow-lg" src="../static/popularproduct1.jpg" alt="">
                        </div>
                        <a class="text-lg font-semibold hover:text-gray-700 pt-2" href="#">MassagePro - Silver</a>
                        <h3 class="text-red-500 tracking-tighter text-lg">$105.00</h3>
                    </div>
                    <div class="flex flex-col items-center">
                        <div class="relative">
                            <div class="absolute w-full h-full left-0 top-0 hover:bg-black hover:opacity-20 transition ease-in-out delay-10"></div>
                            <img class="mx-auto h-40 w-40 lg:h-32 lg:w-32 border-2 border-blue-400 rounded shadow-lg" src="../static/popularproduct2.webp" alt="">
                        </div>
                        <a class="text-lg font-semibold hover:text-gray-700 pt-2" href="#">MassagePro - Black</a>
                        <h3 class="text-red-500 tracking-tighter text-lg">$115.00</h3>
                    </div>
                    <div class="flex flex-col items-center mb-8">
                        <div class="relative bg-white">
                            <div class="absolute w-full h-full left-0 top-0 hover:bg-black hover:opacity-20 transition ease-in-out delay-10"></div>
                            <img class="mx-auto h-40 w-40 lg:h-32 lg:w-32 border-2 border-blue-400 rounded shadow-lg p-4" src="../static/fitbit1.webp" alt="">
                        </div>
                        <a class="text-lg font-semibold hover:text-gray-700 pt-2" href="#">SmartWatch - Pink</a>
                        <h3 class="text-red-500 tracking-tighter text-lg">$65.00</h3>
                    </div>
                    <div class="flex flex-col items-center">
                        <div class="relative bg-white">
                            <div class="absolute w-full h-full left-0 top-0 hover:bg-black hover:opacity-20 transition ease-in-out delay-10"></div>
                            <img class="mx-auto h-40 w-40 lg:h-32 lg:w-32 border-2 border-blue-400 rounded shadow-lg p-4" src="../static/fibit2.webp" alt="">
                        </div>
                        <a class="text-lg font-semibold hover:text-gray-700 pt-2" href="#">SmartWatch - Silver</a>
                        <h3 class="text-red-500 tracking-tighter text-lg">$115.00</h3>
                    </div>
                    <div class="flex flex-col items-center">
                        <div class="relative bg-white">
                            <div class="absolute w-full h-full left-0 top-0 hover:bg-black hover:opacity-20 transition ease-in-out delay-100"></div>
                            <img class="mx-auto h-40 w-40 lg:h-32 lg:w-32 border-2 border-blue-400 rounded shadow-lg p-3" src="../static/massagegun2.webp" alt="">                        
                        </div>
                        <a class="text-lg font-semibold hover:text-gray-700 pt-2" href="#">MassagePro - Black</a>
                        <h3 class="text-red-500 tracking-tighter text-lg">$105.00</h3>
                    </div>
                    <div class="flex flex-col items-center">
                        <div class="relative bg-white">
                            <div class="absolute w-full h-full left-0 top-0 hover:bg-black hover:opacity-20 transition ease-in-out delay-100"></div>
                            <img class="mx-auto h-40 w-40 lg:h-32 lg:w-32 border-2 border-blue-400 rounded shadow-lg p-3" src="../static/massagegun1.webp" alt="">
                        </div>
                        <a class="text-lg font-semibold hover:text-gray-700 pt-2" href="#">MassagePro - Silver</a>
                        <h3 class="text-red-500 tracking-tighter text-lg">$105.00</h3>
                    </div>
                </div>
            </div>
            <div class="latestImage bg-bottom bg-cover lg:w-2/5 lg:my-16 lg:mr-10 relative hidden lg:block">
                <div class="absolute top-0 left-0 h-full w-full bg-black opacity-50"></div>
                <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2">
                    <span class="block text-gray-100 text-4xl font-bold tracking-tight">Rest Better</span>
                    <span class="flex flex-col text-blue-400 text-4xl font-bold tracking-tight">& Go Further</span>
                </div>
            </div>
        </div>
    </div>
</template>

<style>

    .latestImage {
        background-image: url('../static/latestimage.jpg');
    }

</style>