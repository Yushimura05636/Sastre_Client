<script setup lang="ts">
  //...
</script>

<template>
  <div>
    <!-- <div class="container mx-auto"> -->
    <div
      style="background: url('https://i.pinimg.com/736x/85/4f/9d/854f9d4444e8f9721f123ef756eed597.jpg'); 
            background-repeat: no-repeat; 
            background-size: cover; 
            background-position: center;  
            background-attachment:fixed;"
      class="min-h-screen flex flex-col  text-neutral-900 dark:text-neutral-50"
    >
      <NavBar class="fixed shadow z-20 bg-white dark:bg-neutral-950" />
      <div class="mt-24">
        <main class="shadow">
          <slot />
        </main>
      </div>
      <TheFooter />
    </div>
    <!-- </div> -->
  </div>
</template>
<style></style>
