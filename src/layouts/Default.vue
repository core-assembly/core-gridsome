<template>
<div>
  <Navbar />
  <div class="bg-div flex flex-col justify-center bg-transparent">
    <slot />
  </div>
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
