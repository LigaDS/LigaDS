
<template>
  <nav class="navbar navbar-expand-md" data-bs-theme="light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">
        <Logo color="#00a3cc" size="3em" strokeWidth="4"/>
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link" href="#História"> História</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#Áreas">Áreas</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#Membros">Membros</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#Projetos">Projetos</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#Contato">Contato</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<style scoped>
  .navbar {
    background-color: #ffd700;
    font-size: x-large;
  }

  .navbar-toggler-icon {
    color: #008b8b;
  }

  .nav-link {
    color: #d2681e ;
  }

  .nav-link:hover {
    color: brown;
  }

  .nav-link:focus {
    color: darkcyan;
  }
</style>

<script>
import Logo from './icons/Logo.vue';

export default {
  components: {
    Logo
  }
}
</script>
