<template>
  <div>
    <h1 class="text-2xl font-bold">Flex</h1>

    <div class="mt-12 ml-24">
      <p class="text-lg font-bold">Flex</p>
      <div class="w-96 border border-black dark:border-white p-2 flex">
        <div
          class="bg-blue-400 w-24 h-24 m-2 dark:text-slate-900 text-3xl text-center pt-6 font-bold"
        >
          1
        </div>
        <div
          class="bg-blue-400 w-24 h-24 m-2 dark:text-slate-900 text-3xl text-center pt-6 font-bold"
        >
          2
        </div>
        <div
          class="bg-blue-400 w-24 h-24 m-2 dark:text-slate-900 text-3xl text-center pt-6 font-bold"
        >
          3
        </div>
      </div>
    </div>

    <div class="mt-12 ml-24">
      <p class="text-lg font-bold">Flex Basis</p>
      <div class="w-96 border border-black dark:border-white p-2 flex">
        <div
          class="bg-blue-400 w-24 h-24 m-2 dark:text-slate-900 text-lg text-center pt-6 font-bold basis-1/4"
        >
          1/4
        </div>
        <div
          class="bg-blue-400 w-24 h-24 m-2 dark:text-slate-900 text-lg text-center pt-6 font-bold basis-1/2"
        >
          1/2
        </div>
        <div
          class="bg-blue-400 w-24 h-24 m-2 dark:text-slate-900 text-md text-center pt-3 font-bold basis-1/4 hover:basis-1/2 transition-all group"
        >
          <span class="group-hover:hidden block transition">1/4</span>
          <span class="group-hover:block hidden transition">1/2</span>
        </div>
      </div>
      hover 3rd item to see the transition
    </div>

    <div class="mt-12 ml-24">
      <p class="text-lg font-bold">Flex Grow</p>
      <div class="w-96 border border-black dark:border-white p-2 flex">
        <div
          class="bg-blue-400 w-16 h-24 m-2 dark:text-slate-900 text-3xl text-center pt-6 font-bold grow"
        >
          1
        </div>
        <div
          class="bg-blue-400 w-16 h-24 m-2 dark:text-slate-900 text-3xl text-center pt-6 font-bold hover:grow transition-all"
        >
          2
        </div>
        <div
          class="bg-blue-400 w-16 h-24 m-2 dark:text-slate-900 text-3xl text-center pt-6 font-bold hover:grow transition-all"
        >
          3
        </div>
      </div>
      hover 2 and 3 to see the grow effect
    </div>

    <div class="mt-12 ml-24">
      <p class="text-lg font-bold">Flex Shrink</p>
      <div class="w-96 border border-black dark:border-white p-2 flex">
        <div
          class="bg-blue-400 w-24 h-24 m-2 dark:text-slate-900 text-3xl text-center pt-6 font-bold"
        >
          1
        </div>
        <div
          class="bg-blue-400 w-64 h-24 m-2 dark:text-slate-900 text-3xl text-center pt-6 font-bold shrink hover:shrink-0 transition-all duration-200"
        >
          2
        </div>
        <div
          class="bg-blue-400 w-24 h-24 m-2 dark:text-slate-900 text-3xl text-center pt-6 font-bold"
        >
          3
        </div>
      </div>
      hover 2nd item to see the shrink effect
    </div>

    <div class="mt-12 ml-24">
      <p class="text-lg font-bold">Order Flex</p>
      <div class="w-96 border border-black dark:border-white p-2 flex">
        <div
          class="bg-blue-400 w-24 h-24 m-2 dark:text-slate-900 text-3xl text-center pt-6 font-bold order-3"
        >
          1
        </div>
        <div
          class="bg-blue-400 w-24 h-24 m-2 dark:text-slate-900 text-3xl text-center pt-6 font-bold order-1"
        >
          2
        </div>
        <div
          class="bg-blue-400 w-24 h-24 m-2 dark:text-slate-900 text-3xl text-center pt-6 font-bold order-2"
        >
          3
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'FlexPage'
}
</script>
