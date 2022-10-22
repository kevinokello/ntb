<template>
  <footer>
    <div class="flex flex-col items-center mt-16">
    
      <div class="flex mb-2 space-x-2 text-sm text-gray-500 dark:text-gray-400">
        <div>Copyright © {{ new Date().getFullYear() }}</div>
        <div>•</div>
        <a href="/"
          >KevCodes</a
        >
      </div>
      <div class="mb-8 text-sm text-gray-500 dark:text-gray-400">
        <a
          target="_blank"
          rel="noopener noreferrer"
          href="https://github.com/mdrathik/tailwind-nuxtjs-starter-blog"
        ></a>
      </div>
      <!-- <BuyMeACoffee></BuyMeACoffee> -->
    </div>
  </footer>
</template>

<script>
import siteMetaInfo from "@/data/sitemetainfo";
import BuyMeACoffee from "./BuyMeACoffee.vue";
export default {
  data() {
    return {
      siteMetadata: siteMetaInfo,
    };
  },
  components: { BuyMeACoffee },
};
</script>
