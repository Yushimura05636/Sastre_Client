<script setup lang="ts">
  import { heroImageUrl } from '@/utils/hero'

  const { optimizeImage } = useOptimizeImage()
  const heroImageOptimized = {
    alt: `hero`,
    cover: true,
    ...optimizeImage(
      heroImageUrl,
      /* options */
      {
        /* If using local images instead of unsplash url, enable netlify provider */
        // provider:
        //     process.env.NODE_ENV === 'production'
        //       ? 'netlify'
        //       : null /* defaults to ipx or ipxStatic */,
        placeholder: true, // placeholder image before the actual image is fully loaded.
      },
      true /* return bgStyles */,
    ),
  }

  const heroImage = heroImageOptimized.src
  const bgStyles = heroImageOptimized.bgStyles

  //use this only for not splash images url
  const bgStylesT = bgStyles.replaceAll('768w' || '2560w', '');

</script>
<template>
  <section class="container mx-auto pb-12 px-4">
    <div
      class="bg-center bg-cover bg-no-repeat blur-none rounded-3xl z-0"
      :style='bgStylesT'
    >
      <!-- <div
      class="bg-center bg-cover bg-no-repeat blur-none rounded-3xl z-0 bg-design-image lg:bg-design-image-large"
    > -->
      <div class>
        <div class="lg:px-12 md:py-36 pb-6 pt-72 px-6 relative rounded-3xl">
          <div
            class="-mx-4 flex flex-wrap items-center mt-24 space-y-6 lg:space-y-0"
          >
            <div class="px-4 w-full md:w-8/12 xl:w-6/12">
              <h4
                class="font-bold font-serif mb-1 text-primary-600 dark:text-primary-200 uppercase"
              >
                Adopt A Chibi Pet
              </h4>
              <h1 class="capitalize leading-tight mb-2 text-white">
                Thousands of homeless chibi pets, one act of kindness
              </h1>
              <p class="font-thin mb-6 text-gray-300">
                Find your new star rail friends today! We have a wide variety of
                lovable chibi pets available for adoption. Come visit us and take home
                your new best friend!
              </p>
              <BaseButton
                size="xl"
                label="Adopt Now"
                target="_blank"
                to="https://hsr.hoyoverse.com/en-us/"
              >
                <NuxtLink to ="/adopt" class="inline-block ml-1 p-1.5 text-lg">Adopt Now</NuxtLink>
                <img
                  src="https://64.media.tumblr.com/9156a39fee5687ee2e1195865ca4617a/4caafae280536c78-84/s540x810/881c446ea9bb2bbd2290b28ab34a914c9cb0903f.png"
                  class="w-10 h-10"
                   />
              </BaseButton>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<style scoped></style>
