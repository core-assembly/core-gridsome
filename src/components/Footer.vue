<template>
  <div class="footer fixed pin-x pin-b">
    <footer class="bg-grey-darkest">
      <div class="font-sans antialiased">
        <nav class="flex items-center justify-center flex-wrap bg-grey-darkest p-2">
          <g-link to="/" class="nav__link no-underline flex items-center flex-no-shrink text-grey-light mr-6">
            <span class="font-semibold text-sm tracking-tight ml-1">&copy; CORE Assembly Ltd.</span>
          </g-link>
        </nav>
      </div>
    </footer>
    <slot/>
  </div>
</template>

<style src="~/assets/css/main.css"></style>
