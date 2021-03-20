<template>
  <div class="flex flex-shrink-0">
    <div class="flex flex-col w-64 bg-cool-gray-900 px-2 py-5">
      <div
        class="mt-5 flex-1 flex flex-col divide-y divide-cyan-800 overflow-y-auto"
      >
        <div class="px-2 space-y-1">
          <NuxtLink
            v-for="(entry, index) in ['First', 'Second', 'Third']"
            :key="index"
            to="/"
            class="relative group flex items-center px-2 py-5 text-sm leading-6 font-normal rounded-lg"
            :class="index === 2 ? 'menu-selected' : 'menu-default'"
          >
            <span class="absolute left-10">
              {{ entry }}
            </span>
          </NuxtLink>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.menu-selected {
  @apply bg-cyan-800 text-white;
}
.menu-default {
  @apply text-cyan-100 hover:text-white hover:bg-cyan-600;
}
</style>
