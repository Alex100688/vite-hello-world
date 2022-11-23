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

<style scoped>
  h1{
    text-align: center;
    padding: 1.25rem, 0;
  }
</style>


