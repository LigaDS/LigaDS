<template>
  <div class="d-inline-flex px-3 py-2 m-1 tagbox rounded-pill justify-content-center align-items-center" :style="{ backgroundColor: tagColor }">
    <ion-icon :name="icon" :style="{ color: iconColor }" class="icon"></ion-icon>
    <p class="fs-6 mx-2 mb-0 label" :style="{ color: textColor }">{{ label }}</p>
  </div>
</template>

<style scoped>
.icon {
  font-size: 20pt;
}
</style>

<script>
export default {
  props: {
    icon: {
      type: String,
      required: true
    },
    iconColor: {
      type: String,
      default: '#000'
    },
    tagColor: {
      type: String,
      default: '#fff'
    },
    textColor: {
      type: String,
      default: '#000'
    },
    label: {
      type: String,
      default: 'Texto'
    }
  }
}
</script>
