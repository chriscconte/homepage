<template>
  <div class="sm:container sm:mx-auto px-10">
    <NuxtLayout>
      <div class="max-w-4xl mx-auto">
        <div class="flex flex-row">
          <div class="grow"></div>
          <NuxtLink
            to="mailto:chris@conte.org"
            class="block border-2 border-black bg-red-500/50 px-1 hover:after:content-['email'] after:content-['email']"
          >
          </NuxtLink>
          <NuxtLink
            to="http://instagram.com/chriscconte/"
            class="block border-2 border-black bg-red-500/50 px-1 hover:after:content-['instagram'] after:content-['ig']"
          >
          </NuxtLink>
          <NuxtLink
            to="https://github.com/chriscconte"
            class="block border-2 border-black bg-red-500/50 px-1 hover:after:content-['github'] after:content-['gh']"
          >
          </NuxtLink>
          <NuxtLink
            to="https://www.strava.com/athletes/1505235"
            class="block border-2 border-black bg-red-500/50 px-1 hover:after:content-['strava'] after:content-['st']"
          >
          </NuxtLink>
          <NuxtLink
            to="https://www.linkedin.com/in/christopher-conte-b56853128/"
            class="block border-2 border-black bg-red-500/50 px-1 hover:after:content-['linkedin'] after:content-['in']"
          >
          </NuxtLink>
        </div>
        <h1 class="text-5xl text-center p-8 mb-4">Chris Conte</h1>
        <div class="flex flex-row text-center">
          <NuxtLink
            to="/"
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
          <div class="block py-2 w-full border-2 border-black hover:bg-gray-100" @click="isOpen = !isOpen"> 
            More
            <div class="group relative"> 
              <div class="absolute w-full top-full bg-white" :class="{ 'hidden': !isOpen }">
                <NuxtLink
                  to="/likes"
                  class="block py-2 w-full hover:bg-green-500/50 border-2 border-black bg-white"
                >
                  Stuff I Like
                </NuxtLink>
                <NuxtLink
                  to="/writings" 
                  class="block py-2 w-full hover:bg-purple-500/50 border-2 border-black bg-white"
                >
                  Writings
                </NuxtLink>
                <NuxtLink
                  to="/media"
                  class="block py-2 w-full hover:bg-orange-500/50 border-2 border-black bg-white"
                >
                  Media
                </NuxtLink>
              </div>
            </div>
          </div>
        </div>
        <div class="h-1 bg-black"></div>
        <div class="p-10 border-2 border-black">
          <NuxtPage />
        </div>
      </div>
    </NuxtLayout>
  </div>
</template>

<script setup>
const isOpen = ref(false)
</script>