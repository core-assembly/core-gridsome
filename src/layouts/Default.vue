<template>
<div class="layout">
  <Navbar />
  <div class="z-0" id="bg-div"></div>
    <slot />
    <Footer />
</div>
</template>

<static-query>
query {
  metaData {
    siteName
  }
}
</static-query>

<script>
import Navbar from '~/components/Navbar.vue'
import Footer from '~/components/Footer.vue'

export default {
  components: {
    Navbar,
    Footer
  }
}
</script>

<style src="~/assets/css/main.css">
</style>
