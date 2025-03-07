<template>
  <h1 class="text-4xl font-bold mb-4">Projects</h1>

  <div class="flex flex-col gap-2">
    <div class="border-2 border-black p-4 mt-4 transition-all duration-700 origin-top">
      <button
        class="flex items-center justify-between w-full text-xl font-bold"
        @click="isDetailsOpen = !isDetailsOpen"
      >
        <span>
          This website
          <NuxtLink
            to="https://github.com/chriscconte/homepage"
            class="mx-1 px-2 py-1 border-2 border-black hover:bg-gray-100"
          >
            GitHub Repo
          </NuxtLink>
          <span class="px-2 py-1 bg-green-500/50 border-2 border-black">Live</span>
        </span>
        <span class="text-2xl">{{ isDetailsOpen ? "−" : "+" }}</span>
      </button>
      <Transition
        name="fade"
        mode="in-out"
        enter-from-class="max-h-0"
        enter-to-class="max-h-screen"
        leave-from-class="max-h-screen"
        leave-to-class="max-h-0"
        duration="1000"
      >
        <WebsiteProject
          v-show="isDetailsOpen"
          class="transition-all overflow-hidden max-h-screen ease-in-out duration-1000"
        />
      </Transition>
    </div>
  </div>
  <div class="mt-8">
    <i> More projects coming soon! </i>
  </div>
</template>
<script setup>
const isDetailsOpen = ref(false);
import WebsiteProject from "@/components/WebsiteProject.vue";
</script>
