<script setup>
defineProps({
  navigationTree: {
    type: Array,
    default: () => []
  }
})
</script>

<template>
  <ul class="navigation">
    <li v-for="(item, index) in navigationTree" :key="index">
      <NuxtLink :to="item.children ? '':item._path" :class="item.children ? '' : ''" :active-class="'text-blue-800 dark:text-gray-600'">
        {{ item.title }}
      </NuxtLink>
      <AppNavigation v-if="item.children" :navigation-tree="item.children" class="sub-navigation" />
    </li>
  </ul>
</template>

<style scoped>
.navigation ul {
  margin-left: .8rem;
}
</style>
