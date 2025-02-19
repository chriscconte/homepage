<template>
  <div class="flex flex-col items-center justify-center min-h-screen">
    <h1 class="text-4xl font-bold mb-4">404 - Page Not Found</h1>
    <p class="mb-4">The page you're looking for doesn't exist.</p>
    <button @click="handleError" class="px-4 py-2 border-2 border-black hover:bg-red-500/50">
      Go back home
    </button>
  </div>
</template>

<script setup>
const handleError = () => {
  navigateTo('/')
}
</script> 