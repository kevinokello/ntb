<template>

  <div class="max-w-3xl px-4 mx-auto sm:px-6 xl:max-w-5xl xl:px-0">
    <div class="pt-6 pb-8 space-y-2 md:space-y-5">
    <div class="flex flex-wrap justify-center">

    <img src="https://avatars.githubusercontent.com/u/76564523?v=4" alt="..." class="shadow-lg rounded max-w-full h-auto align-middle border-none" />
 
</div>

      <p class="text-lg leading-7 text-gray-500 dark:text-gray-400">
        I'm a graduate of Zetech University, majored in BBIT with a
        specialization in Information Technology.
      </p>
      <p class="text-lg leading-7 text-gray-500 dark:text-gray-400">
        Since beginning my journey as a freelance developer nearly 5 years ago,
        I’ve done remote work for agencies, consulted for startups, and
        collaborated with talented people to create web products for both
        business and consumer use. With my strong conceptualization ability, I
        am able to visualize and create beautiful works. Lastly, you can find me
        mostly tweaking on back-end. I especially enjoy working with LARAVEL.
      </p>

      <p class="text-lg leading-7 text-gray-500 dark:text-gray-400">
        I am adept at handling multiple design projects in a fast paced
        environment. Excellent at time management, organization, problem solving
        and meeting deadlines. I'm passionate about bringing both the technical
        and visual aspects of digital products to life. User experience,
        beautiful pixels and writing clean accessible, human code matters to me.
      </p>
    </div>
    <main class="relative mb-auto">
      <div class="">
        <div class="container py-12">
          <div class="flex flex-wrap -m-4">
            <project-card
              v-for="item in projectsData"
              :key="item.title"
              :title="item.title"
              :description="item.description"
              :href="item.href"
              :github="item.github"
            ></project-card>
          </div>
        </div>
      </div>
    </main>
  </div>
  <div class="grid grid-cols-3 gap-4">
  <div class="mb-4">
    <div class="relative overflow-hidden bg-no-repeat bg-cover max-w-xs">
      <img src="https://mdbcdn.b-cdn.net/img/new/fluid/city/113.webp" class="max-w-xs" alt="Louvre" />
      <div class="absolute top-0 right-0 bottom-0 left-0 w-full h-full overflow-hidden bg-fixed opacity-0 hover:opacity-50 transition duration-300 ease-in-out bg-indigo-700"></div>
    </div>
  </div>
  <div class="mb-4">
    <div class="relative overflow-hidden bg-no-repeat bg-cover max-w-xs">
      <img src="https://mdbcdn.b-cdn.net/img/new/fluid/city/113.webp" class="max-w-xs" alt="Louvre" />
      <div class="absolute top-0 right-0 bottom-0 left-0 w-full h-full overflow-hidden bg-fixed opacity-0 hover:opacity-20 transition duration-300 ease-in-out bg-purple-700"></div>
    </div>
  </div>
  <div class="mb-4">
    <div class="relative overflow-hidden bg-no-repeat bg-cover max-w-xs">
      <img src="https://mdbcdn.b-cdn.net/img/new/fluid/city/113.webp" class="max-w-xs" alt="Louvre" />
      <div class="absolute top-0 right-0 bottom-0 left-0 w-full h-full overflow-hidden bg-fixed opacity-0 hover:opacity-70 transition duration-300 ease-in-out bg-green-700"></div>
    </div>
  </div>
</div>
<div class="grid grid-cols-3 gap-4">
  <div class="mb-4 md:mb-0">
    <div class="relative overflow-hidden bg-no-repeat bg-cover max-w-xs">
      <img src="https://mdbcdn.b-cdn.net/img/new/fluid/city/113.webp" class="max-w-xs" alt="Louvre" />
      <div class="absolute top-0 right-0 bottom-0 left-0 w-full h-full overflow-hidden bg-fixed opacity-0 hover:opacity-30 transition duration-300 ease-in-out bg-red-700"></div>
    </div>
  </div>
  <div class="mb-4 md:mb-0">
    <div class="relative overflow-hidden bg-no-repeat bg-cover max-w-xs">
      <img src="https://mdbcdn.b-cdn.net/img/new/fluid/city/113.webp" class="max-w-xs" alt="Louvre" />
      <div class="absolute top-0 right-0 bottom-0 left-0 w-full h-full overflow-hidden bg-fixed opacity-0 hover:opacity-40 transition duration-300 ease-in-out bg-white"></div>
    </div>
  </div>
  <div class="mb-4 md:mb-0">
    <div class="relative overflow-hidden bg-no-repeat bg-cover max-w-xs">
      <img src="https://mdbcdn.b-cdn.net/img/new/fluid/city/113.webp" class="max-w-xs" alt="Louvre" />
      <div class="absolute top-0 right-0 bottom-0 left-0 w-full h-full overflow-hidden bg-fixed opacity-0 hover:opacity-60 transition duration-300 ease-in-out bg-blue-400"></div>
    </div>
  </div>
</div>
</template>

<script></script>
