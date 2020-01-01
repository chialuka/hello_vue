<template>
  <div id="note">
    <section>
      <section class="new-note"></section>
      <textarea type="text" class="input-area" />
      <p>{{ message }}</p>
    </section>
  </div>
</template>

<script>
import Vue from 'vue';

export default new Vue({
  data: {
    message: "note",
  },
});

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
