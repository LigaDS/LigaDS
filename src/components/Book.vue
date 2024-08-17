<template>
  <a :href="link"><img class="book-cover shadow rounded mb-4 grow" :src="getImageUrl()" alt="Book image cap"></a>
</template>

<style>
.book-cover {
  height: 20rem;
}

.grow { 
    transition: all .2s ease-in-out; 
}

.grow:hover { 
    transform: scale(1.1); 
}
</style>

<script>
export default {
  props: {
    link: {
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