<template>
  <div class="mt-4">
    <div class="flex flex-col items-center">
      <img src="@/assets/img/website-sketch.jpg" alt="Sketch of website design" class="w-full max-w-2xl my-4" />
      <p class="text-sm text-gray-600 italic">A preliminary sketch of my website done in the design phase</p>
    </div>

    <p>
      This website is a portfolio of my work. It's built with Nuxt.js and Tailwind CSS, and hosted on GitHub Pages. It's
      a work in progress, and I'll be adding more projects as I complete them. I'm using it to play around with new
      technologies and ideas, as well as to share my work with others.
    </p>

    <h3 class="text-xl font-bold">Project Brief</h3>
    <p class="mt-2">
      I wanted to create a simple but effective portfolio website to showcase my work and experiments with web
      technologies. The key requirements were:
    </p>

    <ul class="list-disc ml-8 mt-2">
      <li>Is easy to learn more about me</li>
      <li>Looks good</li>
      <li>Easy to maintain and update</li>
      <li>Modern tech stack to enable experimentation</li>
      <li>Is easy to build on</li>
    </ul>
    <b>Content:</b>
    <ul class="list-disc ml-8 mt-2">
      <li>Resume</li>
      <li>Work experience</li>
      <li>
        Projects in article format (i.e. narrativizing motive, process, results, instructions for people to build on it,
        somewhere between a lab report and instruction set)
      </li>
      <li>About me section (interests like future of food, machine learning, industrial design, etc.)</li>
      <li>
        Stuff I'm thinking about (things that have inspired me, things that I'm curious about, etc. Can add non coding
        media or link to other people's work. Help situate myself re: other people's work)
      </li>
    </ul>

    <b>Audience:</b>
    <ul class="list-disc ml-8 mt-2">
      <li>Potential employers</li>
      <li>Other software engineers</li>
      <li>Friends</li>
      <li>Family</li>
    </ul>

    <h3 class="text-xl font-bold mt-6">Design</h3>
    <p class="mt-2">
      The design process started with research into other personal websites, and taking notes on what I liked. I
      followed up with sketches and wireframes using my iPad to establish the core layout and navigation structure. Key
      design decisions included:
    </p>
    <ul class="list-disc ml-8 mt-2">
      <li>Simple, straightforward, mobile and desktop friendly</li>
      <li>Single-page application with client-side routing</li>
      <li>Consistent header with navigation menu</li>
      <li>Simple color scheme with accent colors for different sections</li>
      <li>Responsive grid layout for content</li>
      <li>Blocky, bold elements</li>
      <li>Large images</li>
      <li>Serif font</li>
      <li>Animation/transition effects on scroll</li>
      <li>Clear visual identity <i>(commits to the bit)</i></li>
    </ul>

    <h3 class="text-xl font-bold mt-6">Implementation</h3>
    <p class="mt-2">The website was built using:</p>
    <ul class="list-disc ml-8 mt-2">
      <li>Nuxt.js 3 for the framework</li>
      <li>Vue 3 with Composition API</li>
      <li>Tailwind CSS for styling</li>
      <li>GitHub Actions for CI/CD</li>
      <li>GitHub Pages for hosting</li>
    </ul>

    <h3 class="text-xl font-bold mt-6">Ongoing Development</h3>
    <p class="mt-2">Current focus areas include:</p>
    <ul class="list-disc ml-8 mt-2">
      <li>Mobile optimization</li>
      <li>Dark mode implementation</li>
      <li>Content expansion across all sections</li>
      <li>SEO improvements</li>
    </ul>
  </div>
</template>
