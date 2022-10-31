<template>
  <div class="mt-8">
    <div class="mt-2">
      <h2
        class="mb-2 text-xl text-gray-700 font-bold dark:text-blue-200 capitalize"
      >
        Frontend
      </h2>

      <ul class="flex flex-wrap gap-4 items-center">
        <li class="flex items-center">
          <Html class="h-10 w-10 rounded-sm drop-shadow-sm"></Html>
        </li>

        <li class="flex items-center">
          <Css class="h-10 w-10 rounded-sm drop-shadow-sm"></Css>
        </li>
        <li class="flex items-center">
          <Bootstrap class="h-10 w-10"></Bootstrap>
        </li>
        <li class="flex items-center">
          <TailwindCss class="h-10 w-10"></TailwindCss>
        </li>
        <li class="flex items-center">
          <React class="h-10 w-10"></React>
        </li>

        <li class="flex items-center">
          <Vuejs class="h-10 w-10"></Vuejs>
        </li>
           <li class="flex items-center">
          <Javascript class="h-10 w-10"></Javascript>
        </li>
      </ul>
    </div>
    <div class="mt-4">
      <h2
        class="mb-2 text-xl text-gray-700 font-bold dark:text-blue-200 capitalize"
      >
        Backend
      </h2>
      <ul class="mb-6 flex flex-wrap gap-4">
        <li class="flex items-center">
          <Laravel class="h-10 w-10"></Laravel>
        </li>
        <li class="flex items-center">
          <Node class="h-10 w-10"></Node>
        </li>
        <li class="flex items-center">
          <Php class="h-10 w-10"></Php>
        </li>

        <li class="flex items-center">
          <Mysql class="h-13 w-13"></Mysql>
        </li>
      </ul>
    </div>
       <div class="mt-2">
      <h2
        class="mb-2 text-xl text-gray-700 font-bold dark:text-blue-200 capitalize"
      >
        Cms
      </h2>

      <ul class="flex flex-wrap gap-4 items-center">
        <li class="flex items-center">
          <Firebase class="h-10 w-10 rounded-sm drop-shadow-sm"></Firebase>
        </li>
          <li class="flex items-center">
          <Sanity class="h-12 w-17 rounded-sm drop-shadow-sm"></Sanity>
        </li>
           <li class="flex items-center">
          <Aws class="h-10 w-10 rounded-sm drop-shadow-sm"></Aws>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
import Javascript from "../assets/devicon/javascript.svg?inline";
import Html from "../assets/devicon/html.svg?inline";
import Css from "../assets/devicon/css.svg?inline";
import Vuejs from "../assets/devicon/vuejs.svg?inline";
import React from "../assets/devicon/reactjs-icon.svg?inline";
import TailwindCss from "../assets/devicon/tailwindcss.svg?inline";
import Nuxt from "../assets/devicon/nuxt.svg?inline";
import Bootstrap from "../assets/devicon/bootstrap.svg?inline";
import Laravel from "../assets/devicon/svv.svg?inline";
import Php from "../assets/devicon/phpwine.svg?inline";
import Node from "../assets/devicon/node.svg?inline";
import Mysql from "../assets/devicon/mysql.svg?inline";
import Firebase from "../assets/devicon/firebase.svg?inline";
import Sanity from "../assets/devicon/Sanity.svg?inline";
import Aws from "../assets/devicon/aws-2.svg?inline";
export default {
  components: {
    Javascript,
    Html,
    Css,
    Bootstrap,
    Vuejs,
    TailwindCss,
    Nuxt,
    Laravel,
    Node,
    Php,
    React,
    Mysql,
    Firebase,
    Sanity,
    Aws,
  },
};
</script>
