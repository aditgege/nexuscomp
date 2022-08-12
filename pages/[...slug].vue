<template>
  <div class="max-w-2xl px-4 py-10 mx-8 bg-white sm:px-8 sm:shadow dark:bg-gray-900 sm:rounded">
    <!-- Fetch and display the Markdown document from current path -->
    <ContentDoc class="prose prose-gray dark:prose-invert max-w-none">
      <!-- Slot if document is not found -->
      <template #not-found>
        <h1 class="text-2xl">
          Page not found
        </h1>
      </template>
    </ContentDoc>
  </div>
</template>
<script setup>
useHead({
  script: [{ src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }]
})
definePageMeta({
  layout: 'doc'
})
</script>
