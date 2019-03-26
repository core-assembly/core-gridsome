<template>
<Layout>
  <div class="bg-card m-4 mx-auto max-w-sm shadow-lg rounded-lg overflow-hidden">
    <div class="p-4 text-center sm:flex-grow">
      <div class="m-4">
        <h1 class="text-xl">CORE Assembly</h1>
        <p class="text-xm italic leading-tight text-grey-dark">Architecting Complex Systems</p>
      </div>
      <div class="m-4">
        <g-link to="/Contact" class="nav__link">
          <button class="text-xs font-semibold px-4 py-1 leading-normal bg-blue-dark border border-blue-darker text-grey-light hover:bg-blue hover:text-grey-lighter">CONTACT US</button>
        </g-link>
      </div>
    </div>
  </div>
</Layout>
</template>

<script>
import CenterCard from '~/components/CenterCard.vue'

export default {
  components: {
    CenterCard
  },
  metaInfo: {
    title: 'CORE Assembly Ltd.'
  }
}
</script>
