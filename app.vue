<template>
  <div>
    <NuxtLayout>
      <div class="sm:container sm:mx-auto px-10">
        <h1 class="text-center p-8">Chris Conte</h1>
        <div class="columns-4 gap-8 text-center pb-4">
          <NuxtLink to="/about" class="group">
            <div class="w-full rounded hover:bg-red-500/50 group-[.router-link-active]:bg-red-500/50">About</div>
          </NuxtLink>
          <NuxtLink to="/work" class="group">
            <div class="w-full rounded hover:bg-yellow-400/50 group-[.router-link-active]:bg-yellow-400/50">Work</div>
          </NuxtLink>
          <NuxtLink to="/projects" class="group">
            <div class="w-full rounded hover:bg-blue-600/50 group-[.router-link-active]:bg-blue-600/50">Projects</div>
          </NuxtLink>
          <NuxtLink activeClass="font-black">
            <div class="w-full">More</div>
          </NuxtLink>
        </div>
        <div class="w-full p-10 border-2 border-black m-5">
          <NuxtPage />
        </div>
      </div>
    </NuxtLayout>
  </div>
</template>
