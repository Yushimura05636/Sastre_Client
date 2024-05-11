<script setup lang="ts">
  //...
</script>
<template>
  <footer class="pt-12">
    <div class="container mx-auto px-8">
      <div class="flex flex-wrap relative">
        <div
          class="-mx-4 flex flex-col flex-wrap items-center pl-4 pr-8 py-4 md:flex-col md:flex-nowrap -mt-4 lg:items-start lg:w-1/3"
        >
          <NuxtLink class="-ml-6" to="/">
            <div to="/" class="font-serif inline-flex items-center text-3xl">
              <img
                src="https://cdn2.steamgriddb.com/logo/804bfd285116c91c935176b2b199894d.png"
                class="w-15 h-10"
              />
              <h6 class="font-serif inline-flex items-center text-3xl">
                AniList
              </h6>
            </div>
          </NuxtLink>
          <p class="mt-2 text-center w-full lg:text-left">
            Come and join us to our community and spread the love of chibi star rail characters!
          </p>
          <div class="inline-flex mt-6 space-x-3">
            <div class="flex flex-wrap space-x-4">
              <NuxtLink
                href="https://web.facebook.com/HonkaiStarRail/?_rdc=1&_rdr"
                aria-label="facebook"
                external
                target="_blank"
              >
                <BaseIcon
                  name="i-logos-facebook"
                  class="text-2xl"
                  width="28px"
                ></BaseIcon>
              </NuxtLink>
              <NuxtLink
                href="https://twitter.com/honkaistarrail?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor"
                aria-label="twitter"
                external
                target="_blank"
              >
                <BaseIcon
                  name="i-logos-twitter"
                  class="text-2xl"
                  width="28px"
                ></BaseIcon>
              </NuxtLink>
              <NuxtLink
                href="https://discord.com/invite/honkaistarrail"
                aria-label="discord"
                external
                target="_blank"
              >
                <BaseIcon
                  name="i-logos-discord-icon"
                  class="text-2xl"
                  width="28px"
                ></BaseIcon>
              </NuxtLink>
              <NuxtLink
                href="https://www.youtube.com/channel/UC2PeMPA8PAOp-bynLoCeMLA"
                aria-label="youtube"
                external
                target="_blank"
              >
                <BaseIcon
                  name="i-logos-youtube-icon"
                  class="text-2xl"
                  width="28px"
                ></BaseIcon>
              </NuxtLink>
            </div>
          </div>
          <div class="my-6 text-center">
            <NuxtLink to="/">+1 234 567-890</NuxtLink>
            <br />
            <NuxtLink to="/">Sasas@AniList.store</NuxtLink>
          </div>
        </div>
        <div
          class="flex flex-col items-center p-4 w-full sm:w-1/2 md:flex-1 md:w-1/3 lg:items-start"
        >
          <h2 class="font-bold text-primary-600 dark:text-primary-200 text-xl">
            General
          </h2>
          <ul class="text-center lg:mt-2 lg:text-left">
            <li class="mb-4">
              <NuxtLink
                to="/"
                class="hover:text-primary-600 dark:text-primary-200"
                >FAQ</NuxtLink
              >
            </li>
            <li class="mb-4">
              <NuxtLink
                to="/"
                class="hover:text-primary-600 dark:text-primary-200"
                >News</NuxtLink
              >
            </li>
            <li class="mb-4">
              <NuxtLink
                to="/"
                class="hover:text-primary-600 dark:text-primary-200"
                >Careers</NuxtLink
              >
            </li>
            <li class="mb-4">
              <NuxtLink
                to="/"
                class="hover:text-primary-600 dark:text-primary-200"
                >Contact Us</NuxtLink
              >
            </li>
          </ul>
        </div>
        <div
          class="flex flex-col items-center p-4 w-full sm:w-1/2 md:flex-1 md:w-1/3 lg:items-start"
        >
          <h2 class="font-bold text-primary-600 dark:text-primary-200 text-xl">
            Links
          </h2>
          <ul class="text-center lg:mt-2 lg:text-left">
            <li class="mb-4">
              <NuxtLink
                to="/adopt"
                class="hover:text-primary-600 dark:text-primary-200"
                >Adopt Now</NuxtLink
              >
            </li>
            <li class="mb-4">
              <NuxtLink
                to="/quick-start"
                class="hover:text-primary-600 dark:text-primary-200"
                >Donate</NuxtLink
              >
            </li>
            <li class="mb-4">
              <NuxtLink
                to="/articles"
                class="hover:text-primary-600 dark:text-primary-200"
                >Articles</NuxtLink
              >
            </li>
            <li class="mb-4">
              <NuxtLink
                to="/blog"
                class="hover:text-primary-600 dark:text-primary-200"
                >Blog</NuxtLink
              >
            </li>
            <li class="mb-4">
              <NuxtLink
                to="/volunteer"
                class="hover:text-primary-600 dark:text-primary-200"
                >Volunteer</NuxtLink
              >
            </li>
            <li class="mb-4">
              <NuxtLink
                to="#"
                class="hover:text-primary-600 dark:text-primary-200"
                >Our Mission</NuxtLink
              >
            </li>
          </ul>
        </div>
        <div class="flex flex-col items-center p-4 w-full md:w-1/3">
          <h2 class="font-bold text-primary-600 dark:text-primary-200 text-xl">
            Gallery
          </h2>
          <div class="-mx-2 flex flex-wrap items-center lg:mt-2">
            <div class="p-2 w-1/2 sm:w-4/12">
              <div class="block hover:opacity-75 overflow-hidden rounded-xl">
                <NuxtImg
                  src="https://pbs.twimg.com/profile_images/1649600358191337472/m96xbkjO_400x400.jpg"
                  class="w-full"
                />
              </div>
            </div>
            <div class="p-2 w-1/2 sm:w-4/12">
              <div class="block hover:opacity-75 overflow-hidden rounded-xl">
                <NuxtImg
                  src="https://preview.redd.it/seele-art-by-lino-3o-v0-6bgcrr1pj4xa1.jpg?auto=webp&s=65ded071db841ebf85460eaf008b29756c7d2942"
                  class="w-full"
                />
              </div>
            </div>
            <div class="p-2 w-1/2 sm:w-4/12">
              <div class="block hover:opacity-75 overflow-hidden rounded-xl">
                <NuxtImg
                  src="https://upload-os-bbs.hoyolab.com/upload/2023/05/02/329146984/45af76b70d5d21cc5bd531363f9fc750_4451139745985047815.jpg?x-oss-process=image%2Fresize%2Cs_1000%2Fauto-orient%2C0%2Finterlace%2C1%2Fformat%2Cwebp%2Fquality%2Cq_80"
                  class="w-full"
                />
              </div>
            </div>
            <div class="p-2 w-1/2 sm:w-4/12">
              <div class="block hover:opacity-75 overflow-hidden rounded-xl">
                <NuxtImg
                  src="https://64.media.tumblr.com/be8dfb03bb683e69fb4c320534b5326f/21b1c333efea79ac-28/s1280x1920/7de4b3204e17ac512c5a25584e1a3f7c32f967d4.jpg"
                  class="w-full"
                />
              </div>
            </div>
            <div class="p-2 w-1/2 sm:w-4/12">
              <div class="block hover:opacity-75 overflow-hidden rounded-xl">
                <NuxtImg
                  src="https://i.pinimg.com/736x/fd/77/da/fd77dabcc9431460046ffa56d2703953.jpg"
                  class="w-full"
                />
              </div>
            </div>
            <div class="p-2 w-1/2 sm:w-4/12">
              <div class="block hover:opacity-75 overflow-hidden rounded-xl">
                <NuxtImg
                  src="https://avatarfiles.alphacoders.com/366/thumb-1920-366624.jpg"
                  class="w-full"
                />
              </div>
            </div>
          </div>
        </div>
        <div class="flex flex-col sm:w-full md:items-end">
          <hr class="mb-4 opacity-25" />
          <p class="py-1 text-sm sm:text-center">
            &copy; 2002 - 2021. All Rights Reserved - AniList
          </p>
        </div>
      </div>
    </div>
  </footer>
</template>
<style scoped></style>
