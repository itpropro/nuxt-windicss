<template>
  <div class="flex gap-4 w-full justify-center mt-12">
    <div class="w-40">
      <div class="pulse-class"></div>
      <p class="text-center mt-2">class="pulse-class" (defined with @apply)</p>
    </div>
    <div class="w-40">
      <div
        class="relative w-40 h-40 rounded-full bg-teal-600 opacity-80 animate-pulse"
      ></div>
      <p class="text-center mt-2">
        class="relative w-40 h-40 rounded-full bg-teal-600 opacity-80
        animate-pulse"
      </p>
    </div>
  </div>
</template>

<style scoped>
.pulse-class {
  @apply relative w-40 h-40 rounded-full bg-teal-600 opacity-80 animate-pulse;
}
</style>
