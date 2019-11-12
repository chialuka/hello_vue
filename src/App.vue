<template>
  <div id="app">
    <h2>Quick Notes</h2>
    <RiteIt />
  </div>
</template>

<script>
import RiteIt from './components/note.vue';

export default {
  name: 'app',
  components: {
    RiteIt
  }
}
</script>

<style>
#app {
  font-family: "Montserrat", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 0;
}
</style>
