<script setup lang="ts">
  const callToActions = [
    {
      img: 'https://preview.redd.it/today-is-march-7th-day-v0-wao05mqmsrmc1.jpeg?auto=webp&s=f1f783bf929e55fa50a316e233d42caff0113593',
      action: 'Adopt',
      to: '/adopt',
    },
    {
      img: 'https://preview.redd.it/stelle-honkai-star-rail-v0-roftp776rc3b1.jpg?auto=webp&s=a62e6ef30519c7094b1b76900628d2d265f45149',
      action: 'Volunteer',
      to: '/volunteer',
    },
    {
      img: 'https://preview.redd.it/its-been-a-whole-version-what-do-you-guys-think-about-v0-97iqpzgtdo5b1.png?auto=webp&s=3ac2590040e1f433f755824c1a21bca4ec2d6d4f',
      action: 'Donate',
      to: '/quick-start',
    },
  ]
</script>
<template>
  <section class="container mx-auto px-4 py-12">
    <div>
      <h6 class="text-primary-600 dark:text-primary-200 text-center uppercase">
        Get Involved
      </h6>
      <h3 class="capitalize mt-3 text-center">
        Small gesture for a big impact like genshin impact!
      </h3>
      <p class="mt-4 text-center">
        Star Rail Chibi Characters and More! 
      </p>
    </div>
    <div class="-mx-4 flex flex-wrap justify-center mt-12">
      <CallToActionCard
        v-for="(callToAction, index) in callToActions"
        :key="index"
        :action="callToAction.action"
        :img="callToAction.img"
        :to="callToAction.to"
      />
    </div>
  </section>
</template>
<style scoped></style>
