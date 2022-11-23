<script>
import AppHero from './AppHero.vue';

export default {
  components:{
    AppHero
  },
  data() {
    return {
      title: 'La mia prima app con Vite!'
    }
  }
}
</script>

<template>
  <h1>{{ title }}</h1>
  <div><AppHero/></div>
</template>

<style scoped></style>


