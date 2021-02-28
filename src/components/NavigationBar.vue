<template>
  <section class="w-screen mx-auto px-4">
    <nav class="flex flex-wrap p-6 justify-between">
      <div class="flex flex-shrink-0 mr-6 text-center">
        <img src="../assets/img/logoKosku.jpg" class="h-10 w-50 mr-2" />
      </div>
      <div class="block lg:hidden">
        <a @click="showMenu = !showMenu" class="flex items-center px-3 py-2 rounded border border-indigo-400 text-indigo-500 hover:text-indigo-700 hover:border-indigo-700">
          <svg
            class="fill-current h-3 w-3"
            viewBox="0 0 20 20"
            xmlns="http://www.w3.org/2000/svg"
          >
            <title>Menu</title>
            <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
          </svg>
        </a>
      </div>
      <div :class="showMenu ? 'block' : 'hidden'" class="w-full block flex-grow lg:flex lg:items-center lg:w-auto">
        <div class="text-sm lg:flex-grow">
          <a
            href="#about"
            class="block mt-4 lg:inline-block lg:mt-0 text-gray-600 hover:text-gray-900 text-lg mr-4"
          >
            About me
          </a>
          <a
            href="#recent"
            class="block mt-4 lg:inline-block lg:mt-0 text-gray-600 hover:text-gray-900 text-lg mr-4"
          >
            Recent work
          </a>
          <a
            href="#skill"
            class="block mt-4 lg:inline-block lg:mt-0 text-gray-600 hover:text-gray-900 text-lg mr-4"
          >
            Framework skill
          </a>
          <a
            href="#contact"
            class="block mt-4 lg:inline-block lg:mt-0 text-gray-600 hover:text-gray-900 text-lg mr-4"
          >
            Contact me
          </a>
        </div>
        <div>
            <a
              href="#"
              class="inline-block text-sm px-4 py-2 rounded text-gray-600 border border-gray-600 hover:border-transparent hover:text-white hover:bg-indigo-700 mt-4 lg:mt-0"
            >
              Contact me
            </a>
        </div>
      </div>
    </nav>
  </section>
</template> 

<script>
export default {
  name: "NavigationBar",
  data() {
    return {
      showMenu: false
    }
  },
  methods: {
    toggleNavbar: function() {
      this.showMenu = !this.showMenu;
    }
  }
};
</script>