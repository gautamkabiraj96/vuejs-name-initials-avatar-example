<template>
  <div id="app">
    <div class="avatar-container">
      <avatar inline username="Gautam Kabiraj"></avatar>Gautam Kabiraj
    </div>
    <div class="avatar-container">
      <avatar inline username="Tom Smith"></avatar>Tom Smith
    </div>
    <div class="avatar-container">
      <avatar inline username="Lucy Frank"></avatar>Lucy Frank
    </div>
    <div class="avatar-container">
      <avatar inline username="Mona Lisa"></avatar>Mona Lisa
    </div>
  </div>
</template>

<script>
import Avatar from "vue-avatar";

export default {
  name: "App",
  components: {
    Avatar,
  },
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #000000;
  margin-top: 60px;
}
.avatar-container {
  padding: 8px;
}
</style>
