<template>
  <div>
    <h1 class="text-2xl font-bold">Justify Content</h1>

    <div class="flex flex-wrap">
      <div class="flex flex-col">
        <div class="mt-12 ml-24">
          <p class="text-lg font-bold">Justify Content Start</p>
          <div
            class="w-96 border border-black dark:border-white p-2 flex justify-start"
          >
            <div
              class="bg-blue-400 w-16 h-16 m-2 dark:text-slate-900 text-3xl text-center pt-3 font-bold"
            >
              1
            </div>
            <div
              class="bg-blue-400 w-16 h-16 m-2 dark:text-slate-900 text-3xl text-center pt-3 font-bold"
            >
              2
            </div>
            <div
              class="bg-blue-400 w-16 h-16 m-2 dark:text-slate-900 text-3xl text-center pt-3 font-bold"
            >
              3
            </div>
          </div>
        </div>

        <div class="mt-12 ml-24">
          <p class="text-lg font-bold">Justify Content Center</p>
          <div
            class="w-96 border border-black dark:border-white p-2 flex justify-center"
          >
            <div
              class="bg-blue-400 w-16 h-16 m-2 dark:text-slate-900 text-3xl text-center pt-3 font-bold"
            >
              1
            </div>
            <div
              class="bg-blue-400 w-16 h-16 m-2 dark:text-slate-900 text-3xl text-center pt-3 font-bold"
            >
              2
            </div>
            <div
              class="bg-blue-400 w-16 h-16 m-2 dark:text-slate-900 text-3xl text-center pt-3 font-bold"
            >
              3
            </div>
          </div>
        </div>

        <div class="mt-12 ml-24">
          <p class="text-lg font-bold">Justify Content End</p>
          <div
            class="w-96 border border-black dark:border-white p-2 flex justify-end"
          >
            <div
              class="bg-blue-400 w-16 h-16 m-2 dark:text-slate-900 text-3xl text-center pt-3 font-bold"
            >
              1
            </div>
            <div
              class="bg-blue-400 w-16 h-16 m-2 dark:text-slate-900 text-3xl text-center pt-3 font-bold"
            >
              2
            </div>
            <div
              class="bg-blue-400 w-16 h-16 m-2 dark:text-slate-900 text-3xl text-center pt-3 font-bold"
            >
              3
            </div>
          </div>
        </div>
      </div>
      <div class="flex flex-col">
        <div class="mt-12 ml-24">
          <p class="text-lg font-bold">Justify Space Between</p>
          <div
            class="w-96 border border-black dark:border-white p-2 flex justify-between"
          >
            <div
              class="bg-blue-400 w-16 h-16 m-2 dark:text-slate-900 text-3xl text-center pt-3 font-bold"
            >
              1
            </div>
            <div
              class="bg-blue-400 w-16 h-16 m-2 dark:text-slate-900 text-3xl text-center pt-3 font-bold"
            >
              2
            </div>
            <div
              class="bg-blue-400 w-16 h-16 m-2 dark:text-slate-900 text-3xl text-center pt-3 font-bold"
            >
              3
            </div>
          </div>
        </div>

        <div class="mt-12 ml-24">
          <p class="text-lg font-bold">Justify Space Around</p>
          <div
            class="w-96 border border-black dark:border-white p-2 flex justify-around"
          >
            <div
              class="bg-blue-400 w-16 h-16 m-2 dark:text-slate-900 text-3xl text-center pt-3 font-bold"
            >
              1
            </div>
            <div
              class="bg-blue-400 w-16 h-16 m-2 dark:text-slate-900 text-3xl text-center pt-3 font-bold"
            >
              2
            </div>
            <div
              class="bg-blue-400 w-16 h-16 m-2 dark:text-slate-900 text-3xl text-center pt-3 font-bold"
            >
              3
            </div>
          </div>
        </div>

        <div class="mt-12 ml-24">
          <p class="text-lg font-bold">Justify Space Evenly</p>
          <div
            class="w-96 border border-black dark:border-white p-2 flex justify-evenly"
          >
            <div
              class="bg-blue-400 w-16 h-16 m-2 dark:text-slate-900 text-3xl text-center pt-3 font-bold"
            >
              1
            </div>
            <div
              class="bg-blue-400 w-16 h-16 m-2 dark:text-slate-900 text-3xl text-center pt-3 font-bold"
            >
              2
            </div>
            <div
              class="bg-blue-400 w-16 h-16 m-2 dark:text-slate-900 text-3xl text-center pt-3 font-bold"
            >
              3
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'JustifyContentPage'
}
</script>
