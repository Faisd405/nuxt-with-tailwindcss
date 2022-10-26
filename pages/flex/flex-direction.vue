<template>
  <div>
    <h1 class="text-2xl font-bold">Flex Direction</h1>

    <div class="flex flex-wrap">
      <div>
        <div class="mt-12 ml-24">
          <p class="text-lg font-bold">Flex Row</p>
          <div
            class="w-96 border border-black dark:border-white p-2 flex flex-row"
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
          <p class="text-lg font-bold">Flex Row Reverse</p>
          <div
            class="w-96 border border-black dark:border-white p-2 flex flex-row-reverse"
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
      </div>
      <div class="mt-12 ml-24">
        <p class="text-lg font-bold">Flex Col</p>
        <div
          class="h-96 border border-black dark:border-white p-2 flex flex-col"
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
        <p class="text-lg font-bold">Flex Col Reverse</p>
        <div
          class="h-96 border border-black dark:border-white p-2 flex flex-col-reverse"
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
    </div>
  </div>
</template>

<script>
export default {
  name: 'FlexDirectionPage',
}
</script>
