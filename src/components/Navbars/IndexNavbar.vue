<template>
  <nav
    class="top-0 fixed z-50 w-full flex flex-wrap items-center justify-between px-2 py-3 navbar-expand-lg bg-white shadow"
  >
    <div
      class="container px-4 mx-auto flex flex-wrap items-center justify-between"
    >
      <div
        class="w-full relative flex justify-between lg:w-auto lg:static lg:block lg:justify-start"
      >
        <router-link to="/">
          <img class=" inline-block" style="height:30px" src="../../assets/logo/lay2.png">
          <a
            class="text-gray-800 text-lg font-bold leading-relaxed inline-block mr-4 pl-4 py-2 whitespace-no-wrap uppercase"
            href="#pablo"
          >
            Lay2
          </a>
        </router-link>
        <button
          class="cursor-pointer text-xl leading-none px-3 py-1 border border-solid border-transparent rounded bg-transparent block lg:hidden outline-none focus:outline-none"
          type="button"
          v-on:click="setNavbarOpen"
        >
          <i class="fas fa-bars"></i>
        </button>
      </div>
      <div
        class="lg:flex flex-grow items-center"
        :class="[navbarOpen ? 'block' : 'hidden']"
        id="example-navbar-warning"
      >
        <ul class="flex flex-col lg:flex-row list-none lg:ml-auto">
          <!--
          <li class="flex items-center">
            <index-dropdown />
          </li>
          -->
          <li class="flex items-center">
            <a
              class="hover:text-gray-600 text-gray-800 px-3 py-2 flex items-center text-xs uppercase font-bold"
              href="/"
            >
              Home
            </a>
          </li>
          <li class="flex items-center">
            <router-link to="/team">
              <a class="hover:text-gray-600 text-gray-800 px-3 py-2 flex items-center text-xs uppercase font-bold">
                Team
              </a>
            </router-link>
          </li>
          <li class="flex items-center">
            <router-link to="/joinus">
              <a class="hover:text-gray-600 text-gray-800 px-3 py-2 flex items-center text-xs uppercase font-bold">
                Join us
              </a>
            </router-link>
          </li>
          <li class="flex items-center mr-4">
            <a class="hover:text-gray-600 text-gray-800 px-3 py-2 flex items-center text-xs uppercase font-bold"
              href="https://docs.lay2.dev/"
              target="_blank">
              Docs
            </a>
          </li>
          <li class="flex items-center">
            <a
              class="px-3 py-2 flex items-center text-xs uppercase font-bold"
              href="https://twitter.com/Lay2dev"
              target="_blank"
            >
              <i class="text-gray-500 fab fa-twitter text-lg leading-lg hover:text-blue-500" />
            </a>
            <a
              class="px-3 py-2 flex items-center text-xs uppercase font-bold"
              href="https://discord.gg/6BwTnT6"
              target="_blank"
            >
              <i class="text-gray-500 fab fa-discord text-lg leading-lg hover:text-blue-500" />
            </a>

            <a
              class="px-3 py-2 flex items-center text-xs uppercase font-bold"
              href="https://github.com/lay2dev"
              target="_blank"
            >
              <i class="text-gray-500 fab fa-github text-lg leading-lg hover:text-blue-500" />

            </a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
// import IndexDropdown from "@/components/Dropdowns/IndexDropdown.vue";

export default {
  data() {
    return {
      navbarOpen: false,
    };
  },
  methods: {
    setNavbarOpen: function () {
      this.navbarOpen = !this.navbarOpen;
    },
  },
  components: {
    // IndexDropdown,
  },
};
</script>
