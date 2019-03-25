<template>
  <div class="footer">
    <footer class="absolute pin-b pin-x bg-grey-darkest">
      <div class="font-sans antialiased">
        <nav class="flex items-center justify-center flex-wrap bg-grey-darkest p-3">
          <g-link to="/" class="nav__link no-underline flex items-center flex-no-shrink text-grey-light mr-6">
            <span class="font-semibold text-md tracking-tight ml-1">&copy; CORE Assembly Ltd.</span>
          </g-link>
        </nav>
      </div>
    </footer>
    <slot/>
  </div>
</template>

<style src="~/assets/css/main.css"></style>
