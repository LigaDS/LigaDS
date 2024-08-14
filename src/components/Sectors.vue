<template>
  <div class="d-flex flex-column sectors-container" data-bs-theme="dark">
    <h1 class="sectors-title pb-4" href="Áreas">Áreas</h1>
    <div class="row">
      <div class="col">
        <div class="card">
           <div class="card-body">
             <h5 class="card-title fs-4">📢 Marketing</h5>
             <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
           <div class="card-body">
             <h5 class="card-title fs-4">🛠️ Projetos</h5>
             <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
           <div class="card-body">
             <h5 class="card-title fs-4">📚 Training</h5>
             <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
           <div class="card-body">
             <h5 class="card-title fs-4">🤝 Recursos Humanos</h5>
             <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            </div>
        </div>
      </div>
    </div>
  </div>
  
</template>

<style scoped>
.sectors-container {
  background: rgb(34,34,34);
background: linear-gradient(0deg, rgba(34,34,34,1) 0%, rgba(17,17,17,1) 50%, rgba(34,34,34,1) 100%);
  padding: 8vh 4vw;
}

.sectors-title {
  color: #eeeeee;
}

.card {
  min-width: 18rem;
  margin-bottom: 2rem;
  padding-top: 0.5rem;
}
</style>