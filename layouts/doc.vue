<template>
  <div>
    <AppHeader />
    <div class="d-container lg:flex">
      <SideNav />
      <div class="flex-auto w-full min-w-0 lg:static lg:max-h-full lg:overflow-visible">
        <div class="flex flex-col w-full pt-0 xl:flex-row xl:pt-10">
          <article class="flex-auto order-last min-w-0 mt-0 xl:order-first xl:mt-0">
            <slot />
          </article>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.d-container {
    max-width: 80rem;
    margin-left: auto;
    margin-right: auto;
}
</style>
