<script setup>
  import Navbar from './components/Navbar.vue'
  import Headline from './components/Headline.vue'
  import History from './components/History.vue'
</script>

<template>
  <header>
    <Navbar/>
  </header>

  <main class="d-flex flex-column">
    <Headline/>
    <History/>
  </main>
</template>
