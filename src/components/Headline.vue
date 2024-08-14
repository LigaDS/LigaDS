<template>
  <div class="d-lg-flex flex-wrap align-content-center justify-content-center headline-body">
    <div class="headline-logo-container">
      <img src="../assets/todos.svg" class="headline-logo">
    </div>
    <div class="headline-text-container">
      <p class="p-2">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer leo ligula, vulputate nec eleifend ut, viverra ut dui. Maecenas vestibulum blandit viverra. Integer vehicula mauris urna, rutrum aliquam purus rhoncus eu. Donec faucibus ipsum ac faucibus varius. Donec eget iaculis ipsum, vitae fringilla augue.</p>
    </div>
  </div>
</template>

<style scoped>
.headline-body {
  background: rgb(0,211,204);
  background: linear-gradient(0deg, rgba(0,211,204,1) 0%, rgba(0,163,204,1) 100%);
  height: auto;
  padding: 6vh 4vw 6vh 4vw;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}

.headline-logo-container {
  flex: 0 1 auto;
  display: flex;
  justify-content: center;
  padding-bottom: 2vh;
}

.headline-logo {
  filter: drop-shadow(0 0 10px rgba(238, 238, 238, 0.8));
  max-width: 80%;
}

.headline-text-container {
  flex: 0 0 40%;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: justify;
  font-size: larger;
}

.headline-text {
  max-width: 20em;
  overflow-wrap: break-word;
  word-break: break-word;
}

@media (max-width: 768px) {
  .headline-body {
    flex-direction: column;
    height: auto;
    text-align: center;
    padding: 6vh 0 2vh 0;
  }

  .headline-logo-container {
    margin-top: 2vh;
  }

  .headline-text-container {
    padding: 2em 2em 1em 2em;
  }
}
</style>
