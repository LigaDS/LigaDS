<script setup>
  import Navbar from './components/Navbar.vue'
  import Headline from './components/Headline.vue'
  import History from './components/History.vue'
  import Sectors from './components/Sectors.vue';
</script>

<template>
  <header>
    <Navbar/>
  </header>

  <main class="d-flex flex-column">
    <Headline/>
    <History/>
    <Sectors/>
  </main>
</template>
