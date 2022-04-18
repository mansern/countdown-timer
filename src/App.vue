<template>
  <div class="app">
    <div class="flex-container">
      <img alt="logo" src="./assets/index.png" />
    </div>
    <div class="center">
      <Countdown />
    </div>
  </div>
</template>

<script>
import Countdown from "./components/Countdown.vue";

export default {
  name: "CountdownTimer",
  components: {
    Countdown,
  },
};
</script>

<style>
.app {
  text-align: center;
}
.flex-container {
  display: flex;
  justify-content: center;
  margin-top: 100px;
}
.center {
  display: flex;
  align-items: center;
  justify-content: center;
  margin-top: 10vh;
}
</style>
