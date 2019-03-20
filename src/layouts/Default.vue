<template>
  <div class="layout">
    <header class="header">
        <g-link to="/">
          <g-image alt="CORE Logo" src="~/assets/CORE-trans.png" width="135" />
        </g-link>
      <nav class="nav">
        <g-link class="nav__link" to="/">Home</g-link>
        <g-link class="nav__link" to="/about">About</g-link>
        <g-link class="nav__link" to="/contact">Contact</g-link>
      </nav>
    </header>
    <slot/>
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
