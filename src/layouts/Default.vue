<template>
<div class="layout">
  <div class="h-screen" id="bg-div">
    <Navbar />
      <slot />
    <Footer />
  </div>
</div>
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
