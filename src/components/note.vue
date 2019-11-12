<template>
  <div class="note">
    <section>
      <section class="new-note" v-on:click="createNote"></section>
      <textarea type="text" class="input-area" />
    </section>
  </div>
</template>

<script>
export default {
  name: "note",
  method: {
    createNote: () => {}
  }
};
</script>

<style scoped>
.new-note {
  background-color: rgb(240, 183, 28);
  color: #2b2b2b;
  height: 200px;
  width: 200px;
}
.input-area {
  overflow: hidden;
  background-color: rgb(240, 183, 28);
  border: none;
  color: #2b2b2b;
  height: 200px;
  width: 200px;
}
</style>
