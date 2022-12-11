<template>
  <div>
    <NavBar />
    <section class="hero is-info">
      <div class="hero-body"> 
        <NuxtPage />
      </div>
    </section>
    <div>
      <Footer />
    </div>
  </div>
</template>

<style>
@import "https://cdn.jsdelivr.net/npm/bulma@0.9.4/css/bulma.min.css";
</style>

<script setup>
useHead({
  htmlAttrs: {
    lang: 'pt-BR',
    class: 'has-navbar-fixed-top'
  }
})
</script>