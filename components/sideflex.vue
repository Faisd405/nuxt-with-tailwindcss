<template>
  <aside
    class="bg-sky-300 dark:bg-slate-700 border-b-4 sm:border-b-0 sm:border-r-4 border-sky-400 dark:border-slate-600 text-slate-800 dark:text-white sm:min-h-screen min-w-full sm:min-w-0 sm:w-36 md:w-48 lg:w-64 py-2 px-2"
  >
    <div class="flex flex-col space-y-4">
      <nuxt-link :to="'/flex/'">Simple Flex</nuxt-link>
      <nuxt-link :to="'/flex/flex-direction'">Flex Direction</nuxt-link>
      <nuxt-link :to="'/flex/flex-wrap'">Flex Wrap</nuxt-link>
      <nuxt-link :to="'/flex/justify-content'">Justify Content</nuxt-link>
      <nuxt-link :to="'/flex/align-item'">Align Item</nuxt-link>
    </div>
  </aside>
</template>

<script>
export default {
  name: 'SideFlex'
}
</script>
