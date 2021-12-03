<template>
  <img alt="Vue logo" src="./assets/profile_photo.jpg" width="500">
  <Carola msg="Carola Imgrund"/>
</template>

<script>
import Carola from './components/Carola.vue'

export default {
  name: 'App',
  components: {
    Carola
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
