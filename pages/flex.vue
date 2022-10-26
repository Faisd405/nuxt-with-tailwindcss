<template>
  <div>
    <div class="sm:flex">
      <Sideflex></Sideflex>
      <main class="p-4">
        <Nuxt />
      </main>
    </div>
  </div>
</template>

<script>
import Sideflex from '~/components/sideflex.vue';

export default {
    name: "FlexPage",
    components: { Sideflex }
}
</script>
