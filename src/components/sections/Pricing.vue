<template>
    <div class="items-center mb-16 flex font-satoshi flex-col">
        <h2 class="text-xl font-black bg-gradient-to-r from-[#8b9ce1] via-[#a88aef] to-[#dc75fc] text-transparent bg-clip-text">Pricing</h2>
        <h1 class="mt-4 text-5xl font-bold text-white">How much it costs?</h1>
        <div class="mt-10 flex flex-wrap">
        <!--Aperium Premium card-->
        <div class="p-4 relative z-10 mr-12 border-gray-700 border rounded-xl md:p-10 bg-[#0d0d12]">
            <h3 class="text-xl font-bold text-gray-800 dark:text-gray-200">Aperium Premium</h3>
                <p class="text-[13px] text-gray-500">Cancel anytime.</p>
            <div class="mt-5">
              <span class="text-6xl font-bold text-gray-800 dark:text-gray-200">$20</span>
              <span class="text-lg font-bold text-gray-800 dark:text-gray-200">.00</span>
              <span class="ms-3 text-gray-500">USD / monthly</span>
            </div>

            <div class="mt-5 grid sm:grid-cols-2 gap-y-2 py-4 first:pt-0 last:pb-0 sm:gap-x-6 sm:gap-y-0">
              <ul class="space-y-2 text-sm sm:text-base">
                <li class="flex space-x-3">
                  <span class="mt-0.5 size-5 flex justify-center items-center rounded-full border border-gray-700/30 dark:text-[#e96dfcd0]">
                    <svg class="flex-shrink-0 size-3.5" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg>
                  </span>
                  <span class="text-gray-800 dark:text-gray-200">
                    Up to 10 people
                  </span>
                </li>

                <li class="flex space-x-3">
                  <span class="mt-0.5 size-5 flex justify-center items-center rounded-full border border-gray-700/30 dark:text-[#e96dfcd0]">
                    <svg class="flex-shrink-0 size-3.5" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg>
                  </span>
                  <span class="text-gray-800 dark:text-gray-200">
                    Collect data
                  </span>
                </li>

                <li class="flex space-x-3">
                  <span class="mt-0.5 size-5 flex justify-center items-center rounded-full border border-gray-700/30 dark:text-[#e96dfcd0]">
                    <svg class="flex-shrink-0 size-3.5" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg>
                  </span>
                  <span class="text-gray-800 dark:text-gray-200">
                    Code extensibility
                  </span>
                </li>
              </ul>
            </div>

            <div class="mt-5 grid grid-cols-2 gap-x-4 py-4 first:pt-0 last:pb-0">
              <div class="flex justify-end">
                <button type="button" class="py-4 px-12 inline-flex items-center gap-x-2 text-sm font-medium rounded-lg border dark:text-gray-400 transition-all ease-linear shadow-sm disabled:opacity-50 disabled:pointer-events-none dark:bg-[#0d0d12] dark:hover:text-white dark:border duration-1000 dark:border-gray-700 dark:hover:border-[#E86DFC]/40 dark:hover:bg-[#171720]">Start free trial</button>
              </div>
            </div>
          </div>
          <!-- End Card -->
        <!--Aperium Lifetime card-->
        <div class="p-4 relative z-10 border-gray-700 border rounded-xl md:p-10 bg-[#0d0d12]">
            <h3 class="text-xl font-bold text-gray-800 dark:text-gray-200">Aperium Lifetime</h3>
                <p class="text-[13px] text-gray-500">Cancel anytime.</p>

            <div class="mt-5">
              <span class="text-6xl font-bold text-gray-800 dark:text-gray-200">$200</span>
              <span class="text-lg font-bold text-gray-800 dark:text-gray-200">.00</span>
              <span class="ms-3 text-gray-500">USD / yearly</span>
            </div>

            <div class="mt-5 grid sm:grid-cols-2 gap-y-2 py-4 first:pt-0 last:pb-0 sm:gap-x-6 sm:gap-y-0">
              <ul class="space-y-2 text-sm sm:text-base">
                <li class="flex space-x-3">
                  <span class="mt-0.5 size-5 flex justify-center items-center rounded-full border border-gray-700/30 dark:text-[#e96dfcd0]">
                    <svg class="flex-shrink-0 size-3.5" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg>
                  </span>
                  <span class="text-gray-800 dark:text-gray-200">
                    Up to 10 people
                  </span>
                </li>

                <li class="flex space-x-3">
                  <span class="mt-0.5 size-5 flex justify-center items-center rounded-full border border-gray-700/30 dark:text-[#e96dfcd0]">
                    <svg class="flex-shrink-0 size-3.5" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg>
                  </span>
                  <span class="text-gray-800 dark:text-gray-200">
                    Collect data
                  </span>
                </li>

                <li class="flex space-x-3">
                  <span class="mt-0.5 size-5 flex justify-center items-center rounded-full border border-gray-700/30 dark:text-[#e96dfcd0]">
                    <svg class="flex-shrink-0 size-3.5" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg>
                  </span>
                  <span class="text-gray-800 dark:text-gray-200">
                    Code extensibility
                  </span>
                </li>
              </ul>
            </div>

            <div class="mt-5 grid grid-cols-2 gap-x-4 py-4 first:pt-0 last:pb-0">
              <div class="flex justify-end">
                <button type="button" class="py-4 px-12 inline-flex items-center gap-x-2 text-sm font-medium rounded-lg border dark:text-gray-400 transition-all ease-linear shadow-sm disabled:opacity-50 disabled:pointer-events-none dark:bg-[#0d0d12] dark:hover:text-white dark:border duration-1000 dark:border-gray-700 dark:hover:border-[#E86DFC]/40 dark:hover:bg-[#171720]">Start free trial</button>
              </div>
            </div>
            <!-- End Card -->
          </div>
          </div>
        </div>
</template>