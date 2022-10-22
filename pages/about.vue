<template>
  <div class="max-w-3xl px-4 mx-auto sm:px-6 xl:max-w-5xl xl:px-0">
    <div class="pt-6 pb-8 space-y-2 md:space-y-5">
      <p class="text-lg leading-7 text-gray-500 dark:text-gray-400">
        I'm a graduate of Zetech University, majored in BBIT with a
        specialization in Information Technology. I've done a lot of full-stack
        work, though now I'm mostly focused on back-end. I especially enjoy
        working with LARAVEL.
        </p>
            <p class="text-lg leading-7 text-gray-500 dark:text-gray-400">
        Since beginning my journey as a freelance
        developer nearly 5 years ago, I’ve done remote work for agencies,
        consulted for startups, and collaborated with talented people to create
        web products for both business and consumer use. With my strong
        conceptualization ability, I am able to visualize and create beautiful
        works. Lastly, you can find me mostly tweaking stylesheets and creating
        fluid user experiences.
        </p>
         <p class="text-lg leading-7 text-gray-500 dark:text-gray-400">
        I am adept at handling multiple design projects
        in a fast paced environment. Excellent at time management, organization,
        problem solving and meeting deadlines. I'm passionate about bringing
        both the technical and visual aspects of digital products to life. User
        experience, beautiful pixels and writing clean accessible, human code
        matters to me.
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
</template>

<script></script>
