<script setup>
  import Navbar from './components/Navbar.vue'
  import Headline from './components/Headline.vue'
  import History from './components/History.vue'
  import Sectors from './components/Sectors.vue';
  import Projects from './components/Projects.vue';
  import Contact from './components/Contact.vue';
  import Resources from './components/Resources.vue';
</script>

<template>
  <header>
    <Navbar/>
  </header>

  <main class="d-flex flex-column">
    <Headline/>
    <History/>
    <Sectors/>
    <Resources/>
    <Projects/>
  </main>

<footer>
  <Contact/>
</footer>
</template>
