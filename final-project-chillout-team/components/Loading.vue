<template>
  <div
    class="fixed bg-white inset-0 w-full z-40 flex items-center justify-center h-[100vh] overflow-hidden"
  >
    <div class="p-3 rounded-md bg-orange-100">
      <svg class="animate-spin h-24 w-24 text-orange-500" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24">
        <circle class="opacity-25" cx="12" cy="12" r="10" stroke="currentColor" stroke-width="4"></circle>
        <path class="opacity-75" fill="currentColor" d="M4 12a8 8 0 018-8V0C5.373 0 0 5.373 0 12h4z"></path>
      </svg>
      <div class="text-center pt-5 text-xl font-bold text-orange-600">Loading...</div>
    </div>
  </div>
</template>

<script setup></script>
