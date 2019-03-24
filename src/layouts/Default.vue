<template>
  <div class="layout">
    <Navbar />
    <slot/>
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

<style src="~/assets/css/main.css"></style>

<script>
import Navbar from '~/components/Navbar.vue'
import Footer from '~/components/Footer.vue'

export default {
  components: {
    Navbar,
    Footer
  },
  metaInfo: {
    title: 'About us'
  }
}
</script>
