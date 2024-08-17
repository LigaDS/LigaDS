<script setup>
import Book from './Book.vue';
</script>

<template>
  <div id="Materiais" class="d-flex flex-column sectors-container text-center" data-bs-theme="light">
    <h1  class="sectors-title fs-1 pb-4" href="#Materiais">Materiais</h1>
    <div class="gap-4 d-md-flex justify-content-center align-content-center">
      <Book source="basico.png" link="https://drive.google.com/file/d/1xRq-ntyIJTsBby6YuqQgKBCnhCritejp/view?usp=drive_link"/>
      <Book source="intermediario.png" link="https://drive.google.com/file/d/1mRHPROPgbMYV0aULZoe103RCiixs98cd/view?usp=drive_link"/>
      <Book source="pandas.png" link="https://drive.google.com/file/d/1uTbgbLr_trUPFNYW8DeYsIQ0rZQ4hUey/view?usp=drive_link"/>
    </div>
  </div>
  
</template>

<style scoped>
.sectors-container {
  background: rgb(0,211,204);
  background: linear-gradient(0deg, rgba(0,211,204,1) 0%, rgba(0,163,204,1) 100%);
  padding: 8vh 4vw;
}

.sectors-title {
  color: #ffffff;
}

.card {
  min-width: 18rem;
  margin-bottom: 2rem;
  padding-top: 0.5rem;
}
</style>