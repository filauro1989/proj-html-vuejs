<template>
  <div id="app">
    <Header></Header>
    <Main></Main>
    <Footer></Footer>

  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Main,
    Footer,
  },
};
</script>

<style lang="scss">
@import "~bootstrap/scss/bootstrap";
@import './assets/scss/style.scss';


#app {
  color: black;
  // font-family: 'Dongle', sans-serif;
  // font-size: 2em;
  .container-fluid {
    padding-left: 0;
  }
}

</style>
