<template>
  <div>
    <h1 class="text-2xl font-bold">Flex Wrap</h1>

    <div class="flex flex-wrap">
      <div class="mt-12 ml-24">
        <p class="text-lg font-bold">Flex No Wrap</p>
        <div
          class="w-96 border border-black dark:border-white p-2 flex flex-nowrap"
        >
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
          <div
            class="bg-blue-400 w-24 h-24 m-2 dark:text-slate-900 text-3xl text-center pt-6 font-bold"
          >
            4
          </div>
        </div>
      </div>
      <div class="mt-12 ml-24">
        <p class="text-lg font-bold">Flex Wrap</p>
        <div
          class="w-96 border border-black dark:border-white p-2 flex flex-wrap"
        >
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
          <div
            class="bg-blue-400 w-24 h-24 m-2 dark:text-slate-900 text-3xl text-center pt-6 font-bold"
          >
            4
          </div>
        </div>
      </div>
      <div class="mt-12 ml-24">
        <p class="text-lg font-bold">Flex Wrap Reverse</p>
        <div
          class="w-96 border border-black dark:border-white p-2 flex flex-wrap-reverse"
        >
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
          <div
            class="bg-blue-400 w-24 h-24 m-2 dark:text-slate-900 text-3xl text-center pt-6 font-bold"
          >
            4
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'FlexWrapPage'
}
</script>
