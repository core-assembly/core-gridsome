<template>
<Layout>
  <div class="centerCard bg-white m-4 mx-auto max-w-sm shadow-lg rounded-lg overflow-hidden">
    <div class="p-4 text-center sm:flex-grow">
      <div class="m-4">
        <h1 class="text-xl">CORE Assembly</h1>
        <p class="pt-4 text-xm leading-tight text-grey-darker">
          What we do here
        </p>
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

<style>
.centerCard {
  position: fixed;
  top: 50%;
  left: 50%;
  -webkit-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
}
</style>
