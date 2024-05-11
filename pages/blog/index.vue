<script setup lang="ts">
  definePageMeta({
    // layout: 'default',
    // name: 'blog',
    // alias: 'blog',
    title: 'Blog',
    description: 'Read, Learn, Enjoy: Your Blog Destination!',
    navOrder: 5,
    type: 'secondary',
    icon: 'i-mdi-home',
    // ogImage: 'images/ogImage.png', // url or local images inside public folder, for eg, ~/public/images/ogImage.png
  })
</script>
<template>
  <div class="pb-12">
    <BlogList />
  </div>
</template>
