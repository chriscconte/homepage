<template>
  <div>
    <NuxtLayout>
      <div class="sm:container sm:mx-auto px-10">
        <div class="flex flex-row">
          <div class="grow"></div>
          <NuxtLink
            to="http://instagram.com/chriscconte/"
            class="block border-2 border-black bg-red-500/50 px-1"
          >
            ig
          </NuxtLink>
          <NuxtLink
            to="https://github.com/chriscconte"
            class="block border-2 border-black bg-red-500/50 px-1"
          >
            gh
          </NuxtLink>
          <NuxtLink
            to="https://www.strava.com/athletes/1505235"
            class="block border-2 border-black bg-red-500/50 px-1"
          >
            st
          </NuxtLink>
          <NuxtLink
            to="https://www.linkedin.com/in/christopher-conte-b56853128/"
            class="block border-2 border-black bg-red-500/50 px-1"
          >
            in
          </NuxtLink>
        </div>
        <h1 class="text-5xl text-center p-8">Chris Conte</h1>
        <div class="flex flex-row text-center">
          <NuxtLink
            to="/about"
            class="block py-2 w-full hover:bg-red-500/50 border-2 border-black"
            activeClass="bg-red-500/50"
          >
            About
          </NuxtLink>
          <NuxtLink
            to="/work"
            class="block py-2 w-full hover:bg-yellow-400/50 border-2 border-black"
            activeClass="bg-yellow-500/50"
          >
            Work
          </NuxtLink>
          <NuxtLink
            to="/projects"
            class="block py-2 w-full hover:bg-blue-600/50 border-2 border-black"
            activeClass="bg-blue-500/50"
          >
            Projects
          </NuxtLink>
          <NuxtLink class="block py-2 w-full border-2 border-black">
            More
          </NuxtLink>
        </div>
        <div class="h-1 bg-black"></div>
        <div class="p-10 border-2 border-black">
          <NuxtPage />
        </div>
      </div>
    </NuxtLayout>
  </div>
</template>
