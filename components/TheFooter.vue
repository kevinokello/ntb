<template>
  <footer>
    <div class="flex flex-col items-center mt-16">
    
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
