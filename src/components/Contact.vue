<template>
  <div class="d-md-flex members-container justify-content-center align-items-center" data-bs-theme="dark">
    <div class="d-flex logo-container justify-content-center align-items-center">
      <a href="#"><Logo class="footer-logo" color="#eeeeee" size="5rem" strokeWidth="4" /></a>
    </div>
    
    <div class="d-flex flex-column contact-container">
      <h1 id="Contato" class="fs-3 members-header-title">Contato</h1>
      <div class="d-flex justify-content-center">
        <a href="mailto:ligadsunicamplimeira@gmail.com" class="contact-pressable"><i class="bi bi-envelope-at-fill"></i></a>
        <a href="https://www.linkedin.com/company/liga-de-data-science/about/" class="contact-pressable"><i class="bi bi-linkedin"></i></a>
        <a href="https://github.com/LigaDS" class="contact-pressable"><i class="bi bi-github"></i></a>
        <a href="https://www.instagram.com/ligadsunicamp/" class="contact-pressable"><i class="bi bi-instagram"></i></a>
      </div>
    </div>
  </div>
</template>

<style scoped>
.members-container {
  padding: 8vh 4vw;
  background: linear-gradient(0deg, rgba(0, 0, 0, 1) 0%, rgba(51, 51, 51, 1) 100%);
  flex: 1 1 auto;
}

.members-header-title {
  color: #ffffff;
  margin-bottom: 0.5em;
}

.contact-pressable {
  color: #eeeeee;
  font-size: 2rem;
  margin-right: 0.5em;
}

  .logo-container {
    margin-right: 2rem;
  }

.contact-pressable:hover {
  filter: drop-shadow(0 0 10px rgba(238, 238, 238, 0.8));
}

.footer-logo:hover {
  filter: drop-shadow(0 0 10px rgba(238, 238, 238, 0.8));
}

/* Center content on small screens */
@media (max-width: 768px) {
  .members-container {
    flex-direction: column;
    align-items: center;
    text-align: center;
  }

  .contact-container {
    margin: 0;
    align-items: center;
  }

  .contact-pressable {
    margin: 0 1rem;
  }

  .footer-logo {
    margin-bottom: 1.5em;
  }

  .logo-container {
    margin: 0;
  }
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
