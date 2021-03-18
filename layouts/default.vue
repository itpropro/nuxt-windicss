<template>
  <div class="relative h-screen flex overflow-hidden bg-gray-100 font-sans">
    <sidebar />
    <div class="relative h-full w-full">
      <div
        class="relative h-full pt-6 px-8 scrollbar-thin scrollbar-thumb-brand-green scrollbar-track-white overflow-y-scroll"
      >
        <Nuxt class="mb-24" />
      </div>
    </div>
  </div>
</template>
