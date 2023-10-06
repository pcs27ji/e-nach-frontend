<template>
  <div id="app">
    <TitleBar />
    <!-- <button class="btn btn-primary">Click me</button> -->
    <div id="vueTab">
      <router-view />
    </div>
    <FooterPage />
  </div>
</template>

<script>
// import HomePage from './components/HomePage1.vue'
import TitleBar from './components/TitleBar.vue'
import FooterPage from './components/FooterPage.vue'

export default {
  name: 'App',
  components: {
    TitleBar,
    FooterPage
  //   HomePage,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: whitesmoke;
  margin-top: 0px;
  background-color: #0b5a87;
  height: 100vh;
  width: 100vw;
  overflow-x: hidden;
  overflow-y: auto;
}
#vueTab{
  /* background-color: black; */
  width: 100vw;
  height: 200vh;
}
</style>
