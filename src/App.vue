<script setup>
  import Navbar from './components/Navbar.vue'
  import Headline from './components/Headline.vue'
</script>

<template>
  <header>
    <Navbar/>
  </header>

  <main>
    <Headline/>
  </main>
</template>

<style>
@import './assets/base.css';

body {
  background-color: #eeeeee;
}
</style>
