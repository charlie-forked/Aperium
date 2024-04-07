<template class="">
    <div class="mt-20 w-full h-full flex flex-col justify-center items-center">
        <h2 class="text-xl font-black bg-gradient-to-r from-[#8b9ce1] via-[#a88aef] to-[#dc75fc] text-transparent bg-clip-text">About Us</h2>
        <h1 class="mt-4 text-5xl font-bold text-white">Who we are?</h1>
        <div id="items" class="flex mt-12 mb-20 justify-center">
            <div class="w-[275px] h-[405px] flex flex-col ml-12 z-9 mt-[100px] justify-center dark-bg-discord rounded-xl items-center"></div>
            <div class="w-[555px] h-[675px] flex flex-col z-8 justify-center rounded-xl border border-gray-700 bg-[#0d0d12] items-center"></div>
        </div>
    </div>
</template>

<style>
.dark-bg-discord {
    background-image: url('discord-mockup.png');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
}
</style>