<template>
  <div id="História"class="d-flex flex-wrap history-container">
    <div class="history-picture-container">
      <img src="../assets/foto1.jpg" alt="" class="history-picture">
    </div>
    <div class="history-text-container">
      <h1 class="fs-1">História</h1>
      <p class="p-2">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer leo ligula, vulputate nec eleifend ut, viverra ut dui. Maecenas vestibulum blandit viverra. Integer vehicula mauris urna, rutrum aliquam purus rhoncus eu. Donec faucibus ipsum ac faucibus varius. Donec eget iaculis ipsum, vitae fringilla augue.</p>
    </div>
  </div>
</template>

<style scoped>
.history-container {
  display: flex;
  flex-wrap: wrap;
  margin: 0;
  max-height: 24rem;
}

.history-picture-container {
  flex: 1;
  display: flex;
  position: relative; 
  overflow: hidden;
  max-height: 24rem;
}

.history-text-container {
  flex: 1;
  padding: 2rem 1em;
  font-size: larger;
  padding: 6vh 4vw 6vh 4vw;
  text-align: justify;
  align-content: center;
  justify-content: center;
}

.history-picture {
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: center;
}

@media (max-width: 768px) {
  .history-container {
    flex-direction: column;
    text-align: center;
    max-height: fit-content;
  }

  .history-picture-container {
    height: auto; 
    position: relative;
    overflow: hidden;
    max-height: 20rem;
  }
}
</style>
