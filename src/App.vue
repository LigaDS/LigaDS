<script setup>
  import Navbar from './components/Navbar.vue'
  import Headline from './components/Headline.vue'
  import History from './components/History.vue'
  import Sectors from './components/Sectors.vue';
  import Projects from './components/Projects.vue';
  import Contact from './components/Contact.vue';
</script>

<template>
  <header>
    <Navbar/>
  </header>

  <main class="d-flex flex-column">
    <Headline/>
    <History/>
    <Sectors/>
    <Projects/>
  </main>

<footer>
  <Contact/>
</footer>
</template>
