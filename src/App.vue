<template>
  <div id="app">
    <h2>Quick Notes</h2>
    <Note />
  </div>
</template>

<script>
import Note from './components/note.vue';

export default {
  name: 'app',
  components: {
    Note
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
