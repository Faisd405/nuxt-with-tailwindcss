<template>
  <div>
    <h1 class="text-2xl font-bold">Latihan FlexBox WPU</h1>

    <br class="mt-24" />

    <!-- Latihan 1 - Kolom -->
    <div
      class="flex my-[50] mx-auto bg-blue-300 dark:bg-slate-600 shadow-lg box-border p-5 w-[800]"
    >
      <div class="grow-[3] order-2 px-2">
        <h1 class="text-xl font-bold">Judul Artikel</h1>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur
          qui sequi iste quia eveniet, doloremque harum nihil amet quas laborum
          aspernatur odio eos repudiandae, voluptas iure unde tempora corporis
          cum maxime assumenda error aut rerum commodi cupiditate. Quod rerum
          itaque vel minus dolor accusantium! Quisquam iure nulla impedit totam
          tenetur!
        </p>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur
          qui sequi iste quia eveniet, doloremque harum nihil amet quas laborum
          aspernatur odio eos repudiandae, voluptas iure unde tempora corporis
          cum maxime assumenda error aut rerum commodi cupiditate. Quod rerum
          itaque vel minus dolor accusantium! Quisquam iure nulla impedit totam
          tenetur!
        </p>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur
          qui sequi iste quia eveniet, doloremque harum nihil amet quas laborum
          aspernatur odio eos repudiandae, voluptas iure unde tempora corporis
          cum maxime assumenda error aut rerum commodi cupiditate. Quod rerum
          itaque vel minus dolor accusantium! Quisquam iure nulla impedit totam
          tenetur!
        </p>
      </div>
      <div class="grow order-1">
        <h2 class="text-lg font-bold px-2">Sidebar Satu</h2>
        <ul class="list-disc">
          <li>Link 1</li>
          <li>Link 2</li>
          <li>Link 3</li>
          <li>Link 4</li>
          <li>Link 5</li>
        </ul>
      </div>
      <div class="grow order-3">
        <h2 class="text-lg font-bold px-2">Sidebar Dua</h2>
        <p>
          Lorem, ipsum dolor sit amet consectetur adipisicing elit.
          Exercitationem expedita explicabo iure vel magnam cupiditate placeat
          quidem. Ducimus ipsum minima sed consectetur, aut facere animi!
        </p>
      </div>
    </div>
    <!-- End Latihan 1 -->

    <hr class="border my-16" />

    <!-- Latihan 2 - Services / Features -->
    <div class="max-w-[800] my-[50] mx-auto sm:flex sm:justify-between">
      <div class="bg-blue-300 dark:bg-blue-700 sm:w-[30%] p-[20] box-border">
        <h4>Layanan 1</h4>
        <p>
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Magnam, aut?
        </p>
      </div>
      <div class="bg-green-300 dark:bg-green-700 sm:w-[30%] p-[20] box-border">
        <h4>Layanan 2</h4>
        <p>
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sequi veniam
          culpa delectus quos enim! Enim?
        </p>
      </div>
      <div class="bg-red-300 dark:bg-red-700 sm:w-[30%] p-[20] box-border">
        <h4>Layanan 3</h4>
        <p>
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Illo labore
          atque earum esse tempora ducimus culpa necessitatibus veritatis?
        </p>
      </div>
    </div>
    <!-- End Latihan 2 -->

    <hr class="border my-16" />

    <!-- Latihan 3 - Gallery -->
    <div class="max-w-[800] my-[50] mx-auto flex flex-wrap justify-center">
      <div v-for="i in 10" :key="i" class="w-1/2 sm:w-1/4">
        <img class="w-full" :src="require(`~/assets/img/${i}.jpg`)" alt="" />
      </div>
    </div>
    <!-- End Latihan 3 -->

    <hr class="border my-16" />

    <!-- Latihan 4 - Cards -->
    <div class="w-[800] my-[50] mx-auto sm:flex">
      <div
        v-for="i in 3"
        :key="i"
        :class="
          'border border-solid border-slate-900 rounded-xl bg-gray-300 dark:bg-slate-600 overflow-hidden m-3 flex-grow ' +
          (Math.round(3 / 2) == i ? 'sm:scale-105 md:scale-110' : '')
        "
      >
        <div class="h-36 bg-slate-600 dark:bg-gray-300"></div>
        <div class="text-center pb-5">
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa,
            similique.
          </p>
          <button
            class="px-2 py-1 bg-sky-300 dark:bg-sky-900 hover:bg-sky-600 hover:scale-105 text- transition-all shadow-lg rounded-lg"
          >
            Buy Now!
          </button>
        </div>
      </div>
    </div>
    <!-- End Latihan 4 -->

    <hr class="border my-16" />

    <!-- Latihan 5 - Centering -->
    <div
      class="w-96 h-96 my-[50] mx-auto border border-solid border-black dark:border-white flex"
    >
      <div class="w-32 h-32 bg-sky-700 text-white m-auto flex">
        <span class="m-auto">Hello World</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'LatihanPage'
}
</script>
