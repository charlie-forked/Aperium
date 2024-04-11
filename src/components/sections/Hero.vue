<script setup>
import CardSlider from '../cardslider/CardSlider.vue';
</script>

<template class="flex w-full h-full">
  <div class="mb-16 flex flex-col items-center mt-[150px]"> 
      <div id="spots-left" class="flex justify-center items-center">
          <div class="dark:border-gray-700 text-center border dark:bg-[#0d0d12] dark:hover:border-[#E86DFC]/40 transition-colors duration-500 ease-in-out p-2 rounded-full w-[155px] h-[34px] flex justify-center items-center">
              <span class="relative flex h-[11px] w-[11px]">
                  <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-[#E86DFC] opacity-75"></span>
                  <span class="relative inline-flex rounded-full h-[11px] w-[11px] bg-[#e96dfcbe]"></span>
              </span>
              <span class="text-[12px] mt-[1px] text-center font-bold dark:text-[#9CA3AF] ml-2">100 Spots left</span>
          </div>
      </div>
       <div id="Hero-text" class="mt-10 text-center">
          <span class="text-7xl font-bold dark:text-white flex">Your Future. Our <span class="ml-4 flex flex-col items-center">Focus.<br><div class="framer-jxmdw4 mr-6 bg-cover w-[170px] h-3 mx-auto mt-2" style="background-image: url('data:image/svg+xml;utf8,%3Csvg xmlns=%22http://www.w3.org/2000/svg%22 xmlns:xlink=%22http://www.w3.org/1999/xlink%22 viewBox=%220 0 115 6%22%3E%3Cpath d=%22M 0.329 5.492 C 3.888 5.492 3.888 1.482 7.475 1.482 C 11.035 1.482 11.035 5.492 14.621 5.492 C 18.181 5.492 18.181 1.482 21.768 1.482 C 25.327 1.482 25.327 5.492 28.914 5.492 C 32.474 5.492 32.474 1.482 36.061 1.482 C 39.62 1.482 39.62 5.492 43.207 5.492 C 46.767 5.492 46.767 1.482 50.354 1.482 C 53.913 1.482 53.913 5.492 57.5 5.492 C 61.06 5.492 61.06 1.482 64.646 1.482 C 68.206 1.482 68.206 5.492 71.793 5.492 C 75.352 5.492 75.352 1.482 78.939 1.482 C 82.499 1.482 82.499 5.492 86.086 5.492 C 89.645 5.492 89.645 1.482 93.232 1.482 C 96.792 1.482 96.792 5.492 100.379 5.492 C 103.938 5.492 103.938 1.482 107.525 1.482 C 111.085 1.482 111.085 5.492 114.671 5.492%22 fill=%22transparent%22 stroke-width=%221.55%22 stroke=%22%23e96dfc%22 stroke-linecap=%22round%22 stroke-miterlimit=%2210%22%3E%3C/path%3E%3C/svg%3E');"></div></span></span>

          <p class="text-gray-400 mt-4">You are tired of being the 99% of the population who are on mobile for<br> 9 hours going to parties etc. you are in the right place, here you<br> become <span class="hover:text-[#E86DFC] underline transition-colors duration-1000 ease-linear cursor-pointer">1%</span></p>
      </div>
      <div class="relative inline-flex group">
          <div class="transition-all duration-500 ease-linear sm:text-white sm:bg-[#171720] lg:text-gray-400 lg:hover:text-white lg:hover:border lg:hover:bg-[#171720] lg:bg-[#0d0d12] border px-6 py-3 rounded-full mt-12 lg:border-gray-700 sm:border-[#E86DFC]/40 lg:hover:border-[#E86DFC]/40"><a href="https://google.com/">Start Here &#128640;</a></div>
      </div>
      <CardSlider />
  </div>  
</template>


<script>
import CardSlider from '../cardslider/CardSlider.vue';

export default {
  components: {
    CardSlider
  },
}
</script>