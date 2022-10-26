<template>
  <div>
    <h1 class="text-2xl font-bold">Align Item</h1>

    <div class="flex flex-wrap">
      <div class="mt-12 ml-24">
        <p class="text-lg font-bold">Item Start</p>
        <div
          class="h-96 border border-black dark:border-white p-2 flex items-start"
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
        </div>
      </div>

      <div class="mt-12 ml-24">
        <p class="text-lg font-bold">Item End</p>
        <div
          class="h-96 border border-black dark:border-white p-2 flex items-end"
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
        </div>
      </div>

      <div class="mt-12 ml-24">
        <p class="text-lg font-bold">Item Center</p>
        <div
          class="h-96 border border-black dark:border-white p-2 flex items-center"
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
        </div>
      </div>

      <div class="mt-12 ml-24">
        <p class="text-lg font-bold">Item Baseline</p>
        <div
          class="h-96 border border-black dark:border-white p-2 flex items-baseline"
        >
          <div
            class="bg-blue-400 w-24 h-24 m-2 dark:text-slate-900 text-xl text-center pt-4 font-bold"
          >
            1
          </div>
          <div
            class="bg-blue-400 w-24 h-24 m-2 dark:text-slate-900 text-xl text-center pt-2 font-bold"
          >
            2
          </div>
          <div
            class="bg-blue-400 w-24 h-24 m-2 dark:text-slate-900 text-xl text-center pt-6 font-bold"
          >
            3
          </div>
        </div>
      </div>

      <div class="mt-12 ml-24">
        <p class="text-lg font-bold">Item Scretch</p>
        <div
          class="h-96 border border-black dark:border-white p-2 flex items-stretch"
        >
          <div
            class="bg-blue-400 w-24 m-2 dark:text-slate-900 text-3xl text-center pt-6 font-bold"
          >
            1
          </div>
          <div
            class="bg-blue-400 w-24 m-2 dark:text-slate-900 text-3xl text-center pt-6 font-bold"
          >
            2
          </div>
          <div
            class="bg-blue-400 w-24 m-2 dark:text-slate-900 text-3xl text-center pt-6 font-bold"
          >
            3
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AlignItemPage'
}
</script>
