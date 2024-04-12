<template>
	<li class="user-card list-none mt-12 bg-[#0d0d12] relative border-none text-white">
	  <a target="_blank" :href="href" class="flex items-center">
		<img class="w-12 h-12 rounded-full" :src="image" alt="Card Image" v-if="image" />
		<div class="ml-4 flex flex-col">
		  <h2 class="text-[14px] hover:text-[#e96dfcd0]/90 transition-colors duration-1000 ease-linear text-[#d3d3d3] font-bold flex">{{ title }}</h2>
		  <p class="text-[11px] font-semibold text-[#d3d3d3]/90">{{ role }}</p>
		  <p class="text-[13px] font-regular text-[#d3d3d3]/90">{{ body }}</p>
		</div>
	  </a>
	</li>
  </template>
  
  <script>
  export default {
	props: {
	  href: String,
	  title: String,
	  body: String,
	  image: String,
	  role: String
	}
  };
  </script>