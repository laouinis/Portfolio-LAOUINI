<template>
  <MainCard />
</template>

<script>
import MainCard from "./components/MainCard.vue";

export default {
  name: "App",
  components: {
    MainCard,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400;500;600;700&display=swap");
/* @import url("https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400;500;600;700&family=Lobster+Two:ital,wght@0,400;0,700;1,400;1,700&display=swap"); */
@import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400;500;600;700&family=Lobster+Two:ital,wght@0,400;0,700;1,400;1,700&family=Parisienne&display=swap');
body {
  background-color: #000;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
