<template>
  <div class="d-lg-flex flex-wrap align-content-center justify-content-center headline-body">
    <div class="headline-logo-container">
      <img src="../assets/todos.svg" class="headline-logo">
    </div>
    <div class="headline-text-container">
      <p class="p-2">Somos a primeira Liga da UNICAMP Limeira totalmente voltada ao estudo da ciência de dados e programação.</p>
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
  padding-bottom: 6vh;
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
  font-size: x-large;
  color: #eeeeee;
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
    padding-bottom: 4vh;
  }

  .headline-text-container {
    text-align: center;
    padding: 2em 2em 1em 2em;
  }
}
</style>
