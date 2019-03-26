<template>
  <div class="navbar">
    <header class="header">
      <div class="font-sans antialiased" id="app">
        <nav class="nav flex items-center justify-between flex-wrap bg-blue p-3">
          <g-link to="/" class="nav__link no-underline flex items-center flex-no-shrink text-white mr-6">
            <g-image alt="CORE Logo" src="~/assets/CORE-Assembly.svg" width="135" />
            <span class="font-semibold text-xl tracking-tight ml-1">Assembly</span>
          </g-link>
          <div class="block sm:hidden mt-2">
            <button @click="toggle" class="flex items-center px-3 py-2 border rounded text-blue-lighter border-blue-light hover:text-white hover:border-white">
              <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><title>Menu</title><path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/></svg>
            </button>
          </div>
          <div :class="open ? 'block': 'hidden'" class="w-full flex-grow sm:flex sm:items-center sm:w-auto">
            <div class="text-sm md:text-right sm:flex-grow">
              <g-link to="/About" class="nav__link no-underline block mt-4 sm:inline-block sm:mt-0 text-blue-lighter hover:text-white mr-4">
                About
              </g-link>
              <g-link to="/Services" class="nav__link no-underline block mt-4 sm:inline-block sm:mt-0 text-blue-lighter hover:text-white mr-4">
                Services
              </g-link>
            </div>
            <div>
              <g-link to="/Contact" class="nav__link md:visible no-underline inline-block text-sm px-4 py-2 leading-none border rounded text-white border-white hover:border-transparent hover:text-blue hover:bg-white mt-4 sm:mt-0">Contact Us</g-link>
            </div>
          </div>
        </nav>
      </div>
    </header>
    <slot/>
  </div>
</template>

<style src="~/assets/css/main.css"></style>

<script>
export default {
  name: 'Navbar',
  data () {
    return {
      open: false
    }
  },
  methods: {
    toggle () {
      this.open = !this.open
    }
  }
}
</script>
