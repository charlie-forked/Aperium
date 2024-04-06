<template>
	<li class="user-card list-none bg-[#0d0d12] relative border-none text-white">
	  <a target="_blank" :href="href" class="flex items-center">
		<img class="w-12 h-12 rounded-full" :src="image" alt="Card Image" v-if="image" />
		<div class="ml-4 flex flex-col">
		  <h2 class="text-[14px] font-bold">{{ title }}</h2>
		  <p class="text-[11px] font-normal">{{ role }}</p>
		  <p class="text-[13px] font-normal">{{ body }}</p>
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