<template>
  <div class="min-h-screen bg-sky-200 dark:bg-slate-900 dark:text-slate-300">
    <NavbarVue></NavbarVue>
    <Nuxt />
  </div>
</template>

<script>
import NavbarVue from '~/components/layout/navbar.vue'
export default {
  name: 'DefaultLayout',
  components: {
    NavbarVue
  }
}
</script>
