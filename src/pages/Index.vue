<template>
  <Layout>
    <div class="card">
      <div class="bg-white m-4 mx-auto max-w-sm shadow-lg rounded-lg overflow-hidden">
        <div class="text-center sm:flex-grow">
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
    </div>

  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'CORE Assembly Home'
  }
}
</script>


<style>
.card {
  position: absolute;
  top: 0; left: 0; bottom: 0; right: 0;}
</style>
