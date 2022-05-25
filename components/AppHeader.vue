<script>
</script>

<template>
  <header class="shadow-sm d-header">
    <div class="flex items-center h-full px-1 mx-auto max-w-7xl sm:px-3 lg:px-6">
      <nuxt-link to="/" class="flex items-center justify-center flex-1 lg:justify-start">
        <h1>Nexus Component</h1>
      </nuxt-link>
      <nav class="items-center justify-center hidden h-full lg:flex " />
      <div>
        <ColorModeSwitch />
      </div>
    </div>
  </header>
</template>

<style >
.d-header {
  border-style: none;
  -webkit-backdrop-filter: blur(12px);
  backdrop-filter: blur(12px);
  --tw-bg-opacity: 1;
  --tw-bg-opacity: 0.8;
  height: 4.5rem;
  position: sticky;
  position: -webkit-sticky;
  top: 0;
  width: 100%;
  z-index: 50;
}
</style>
