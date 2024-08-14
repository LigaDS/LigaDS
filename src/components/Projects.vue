<template>
  <div id="Projetos"class="d-flex flex-column projects-container justify-content-center align-items-center">
    <h1 class="fs-1 projects-header-title pb-4">Projetos</h1>
    <div class="d-flex flex-column justify-content-center align-items-center">
      
      <div class="card-container">
        <div class="card">
          <img class="card-img-top" src="..." alt="Card image cap">
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="" class="btn btn-secondary">
              <i class="bi bi-github"></i>
            </a>
          </div>
        </div>
      </div>

      <div class="card-container">
        <div class="card">
          <img class="card-img-top" src="..." alt="Card image cap">
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="" class="btn btn-secondary">
              <i class="bi bi-github"></i>
            </a>
          </div>
        </div>
      </div>
      
    </div>
  </div>
</template>

<style scoped>
.projects-container {
  padding: 8vh 4vw;
  text-align: center;
}

.d-flex {
  display: flex;
}

.card-container {
  margin-bottom: 3vh;
  display: flex;
  justify-content: center;
}

.card {
  display: flex;
  flex-direction: row;
  text-align: left;
  align-items: center;
}

.card-img-top {
  width: 50%;
  height: auto;
}

.icon {
  width: 2rem;
}

@media (max-width: 768px) {
  .card {
    flex-direction: column;
  }
  .card-img-top {
    width: 100%;
    height: auto;
  }
}
</style>
