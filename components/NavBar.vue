<template>
    <nav class="bg-white border-gray-200 w-full">
      <div class="container mx-auto py-4 px-4 sm:px-6 lg:px-8">
        <!-- Desktop version layout -->
        <div class="hidden sm:flex justify-between items-center">
          <!-- Logo (on the left) -->
          <div class="flex items-center">
            <span class="self-center text-2xl font-semibold whitespace-nowrap text-blue-700">DM</span>
          </div>
  
          <!-- Search input (takes a wider width on desktop) -->
          <div class="w-full mx-20"> <!-- Increase the width to your desired value, e.g., w-96 -->
            <form class="w-full">
              <label for="default-search" class="mb-2 text-sm font-medium text-gray-900 sr-only">Search</label>
              <div class="relative">
                <div class="absolute inset-y-0 left-0 flex items-center pl-3 pointer-events-none">
                  <svg class="w-4 h-4 text-gray-500" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 20 20">
                    <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m19 19-4-4m0-7A7 7 0 1 1 1 8a7 7 0 0 1 14 0Z" />
                  </svg>
                </div>
                <input type="search" id="default-search" class="block w-full p-2 pl-10 text-sm text-gray-900 border border-gray-300 rounded-full bg-gray-50 focus:ring-blue-500 focus:border-blue-500 placeholder-gray-400" placeholder="Search Mockups, Logos..." required>
              </div>
            </form>
          </div>
  
          <!-- Heart button (on the right) -->
          <div>
            <button class="bg-white border-solid border-2 border-gray-100 rounded-full w-10 h-10 p-2 flex justify-center items-center">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-8 h-8 text-slate-500">
                <path d="M11.645 20.91l-.007-.003-.022-.012a15.247 15.247 0 01-.383-.218 25.18 25.18 0 01-4.244-3.17C4.688 15.36 2.25 12.174 2.25 8.25 2.25 5.322 4.714 3 7.688 3A5.5 5.5 0 0112 5.052 5.5 5.5 0 0116.313 3c2.973 0 5.437 2.322 5.437 5.25 0 3.925-2.438 7.111-4.739 9.256a25.175 25.175 0 01-4.244 3.17 15.247 15.247 0 01-.383.219l-.022.012-.007.004-.003.001a.752.752 0 01-.704 0l-.003-.001z" />
              </svg>
            </button>
          </div>
        </div>
  
        <!-- Mobile version layout -->
        <div class="sm:hidden mt-4 flex-1">
          <!-- Logo and heart button on the first line -->
          <div class="flex justify-between items-center">
            <!-- Logo (on the left) -->
            <div class="flex items-center">
              <span class="self-center text-2xl font-semibold whitespace-nowrap text-blue-700">DM</span>
            </div>
  
            <!-- Heart button (on the right) -->
            <div>
              <button class="bg-white border-solid border-2 border-gray-100 rounded-full w-10 h-10 p-2 flex justify-center items-center">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-8 h-8 text-slate-500">
                  <path d="M11.645 20.91l-.007-.003-.022-.012a15.247 15.247 0 01-.383-.218 25.18 25.18 0 01-4.244-3.17C4.688 15.36 2.25 12.174 2.25 8.25 2.25 5.322 4.714 3 7.688 3A5.5 5.5 0 0112 5.052 5.5 5.5 0 0116.313 3c2.973 0 5.437 2.322 5.437 5.25 0 3.925-2.438 7.111-4.739 9.256a25.175 25.175 0 01-4.244 3.17 15.247 15.247 0 01-.383.219l-.022.012-.007.004-.003.001a.752.752 0 01-.704 0l-.003-.001z" />
                </svg>
              </button>
            </div>
          </div>
  
          <!-- Search input on the second line (takes full width) -->
          <div class="w-full mt-4">
            <form class="w-full">
              <label for="default-search" class="mb-2 text-sm font-medium text-gray-900 sr-only">Search</label>
              <div class="relative">
                <div class="absolute inset-y-0 left-0 flex items-center pl-3 pointer-events-none">
                  <svg class="w-4 h-4 text-gray-500" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 20 20">
                    <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m19 19-4-4m0-7A7 7 0 1 1 1 8a7 7 0 0 1 14 0Z" />
                  </svg>
                </div>
                <input type="search" id="default-search" class="block w-full p-4 pl-10 text-sm text-gray-900 border border-gray-300 rounded-full bg-gray-50 focus:ring-blue-500 focus:border-blue-500 placeholder-gray-400" placeholder="Search Mockups, Logos..." required>
              </div>
            </form>
          </div>
        </div>
      </div>
    </nav>
  </template>
  
  <style scoped>
  /* Add custom styles here */
  </style>
  