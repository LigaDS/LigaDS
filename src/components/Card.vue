<template>
  <div class="container">
    <div class="card d-flex shadow">
      <img class="card-img-top" :src="getImageUrl()" alt="Card image cap">
      <div class="card-body d-flex flex-column gap-2">
        <h2 class="card-title my-2 mb-4"> {{ title }} </h2>
        <div class="card-text text-start">
          <div class="container">
            <h5>Contexto</h5>
            <p>{{ description }}</p>
          </div>
          <div class="container">
            <h5>Objetivos</h5>
            <slot></slot>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.card {
  flex: 1 1 auto;
  flex-direction: column;
}
.card-img-top {
  height: 20vh;
  object-fit: cover;
}
</style>

<script>
export default {
  props: {
    title: {
      type: String,
      required: false
    },
    description: {
      type: String,
      required: false
    },
    source: {
      type: String,
      required: true
    }
  },
  methods: {
    getImageUrl() {
      return new URL(`../assets/${this.source}`, import.meta.url);
    }
  }
}
</script>
