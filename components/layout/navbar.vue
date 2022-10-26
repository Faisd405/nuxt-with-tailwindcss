<template>
  <nav class="bg-sky-400 dark:bg-gray-800">
    <div class="mx-auto max-w-7xl px-2 sm:px-6 lg:px-8">
      <div class="relative flex h-16 items-center justify-between">
        <div class="absolute inset-y-0 left-0 flex items-center sm:hidden">
          <!-- Mobile menu button-->
          <button
            type="button"
            class="inline-flex items-center justify-center rounded-md p-2 text-gray-400 hover:bg-gray-700 hover:text-white focus:outline-none focus:ring-2 focus:ring-inset focus:ring-white"
            aria-controls="mobile-menu"
            aria-expanded="false"
          >
            <span class="sr-only">Open main menu</span>
            <!--
            Icon when menu is closed.

            Heroicon name: outline/bars-3

            Menu open: "hidden", Menu closed: "block"
          -->
            <svg
              :class="
                (isOpen ? 'hidden ' : 'block ') +
                'h-6 w-6 stroke-black dark:stroke-white'
              "
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              aria-hidden="true"
              @click="toggleMenu"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5"
              />
            </svg>
            <!--
            Icon when menu is open.

            Heroicon name: outline/x-mark

            Menu open: "block", Menu closed: "hidden"
          -->
            <svg
              :class="
                (isOpen ? 'block ' : 'hidden ') +
                'h-6 w-6 stroke-black dark:stroke-white'
              "
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              aria-hidden="true"
              @click="toggleMenu"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M6 18L18 6M6 6l12 12"
              />
            </svg>
          </button>
        </div>
        <div
          class="flex flex-1 items-center justify-center sm:items-stretch sm:justify-start"
        >
          <div
            class="flex flex-shrink-0 items-center text-black dark:text-white"
          >
            Nuxt Tailwind
          </div>
          <div class="hidden sm:ml-6 sm:block">
            <div class="flex space-x-4">
              <!-- Current: "bg-gray-900 text-white", Default: "text-gray-300 hover:bg-gray-700 hover:text-white" -->
              <nuxt-link
                to="/"
                :class="
                  ($route.matched[0].path === '' ? 'nav-active-link ' : 'nav-link ') +
                  ' px-3 py-2 rounded-md text-sm font-medium'
                "
                aria-current="page"
                >Dashboard</nuxt-link
              >
              <nuxt-link
                to="/flex"
                :class="
                  ($route.matched[0].path === '/flex' ? 'nav-active-link ' : 'nav-link ') +
                  'px-3 py-2 rounded-md text-sm font-medium'
                "
                >Flex</nuxt-link
              >
              <nuxt-link
                to="/grid"
                :class="
                  ($route.matched[0].path === '/grid' ? 'nav-active-link ' : 'nav-link ') +
                  'px-3 py-2 rounded-md text-sm font-medium'
                "
                >Grid</nuxt-link
              >
            </div>
          </div>
        </div>
        <div
          class="absolute inset-y-0 right-0 flex items-center pr-2 sm:static sm:inset-auto sm:ml-6 sm:pr-0"
        >
          <button
            class="px-2 py-2 transition duration-200 rounded-lg hover:bg-sky-600 dark:hover:bg-slate-600"
            @click="toggleColorMode"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="w-6 h-6 hidden dark:block stroke-white"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M12 3v2.25m6.364.386l-1.591 1.591M21 12h-2.25m-.386 6.364l-1.591-1.591M12 18.75V21m-4.773-4.227l-1.591 1.591M5.25 12H3m4.227-4.773L5.636 5.636M15.75 12a3.75 3.75 0 11-7.5 0 3.75 3.75 0 017.5 0z"
              />
            </svg>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="w-6 h-6 dark:hidden"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M21.752 15.002A9.718 9.718 0 0118 15.75c-5.385 0-9.75-4.365-9.75-9.75 0-1.33.266-2.597.748-3.752A9.753 9.753 0 003 11.25C3 16.635 7.365 21 12.75 21a9.753 9.753 0 009.002-5.998z"
              />
            </svg>
          </button>
        </div>
      </div>
    </div>

    <!-- Mobile menu, show/hide based on menu state. -->
    <div id="mobile-menu" class="sm:hidden">
      <div
        :class="(isOpen ? 'block ' : 'hidden ') + 'space-y-1 px-2 pt-2 pb-3'"
      >
        <!-- Current: "bg-gray-900 text-white", Default: "text-gray-300 hover:bg-gray-700 hover:text-white" -->
        <nuxt-link
          to="/"
          :class=" ($route.matched[0].path === '/' ? 'nav-active-link ' : 'nav-link ') + 'block px-3 py-2 rounded-md text-base font-medium'"
          aria-current="page"
          >Dashboard</nuxt-link
        >
        <nuxt-link
          to="/flex"
          :class=" ($route.matched[0].path === '/flex' ? 'nav-active-link ' : 'nav-link ') + 'block px-3 py-2 rounded-md text-base font-medium'"
          aria-current="page"
          >Flex</nuxt-link
        >
        <nuxt-link
          to="/grid"
          :class=" ($route.matched[0].path === '/grid' ? 'nav-active-link ' : 'nav-link ') + 'block px-3 py-2 rounded-md text-base font-medium'"
          aria-current="page"
          >Grid</nuxt-link
        >
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'NavbarLayout',
  data() {
    return {
      isOpen: false
    }
  },
  methods: {
    toggleMenu() {
      this.isOpen = !this.isOpen
    },
    toggleColorMode() {
      this.$colorMode.preference =
        this.$colorMode.value === 'dark' ? 'light' : 'dark'
    }
  }
}
</script>
