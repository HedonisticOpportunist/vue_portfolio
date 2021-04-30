<template>
  <div id="app">
    <navigation/>
    <router-view></router-view>
    <Footer/>

  </div>
</template>

<script>
import Navigation from './components/includes/navigation.vue'
import Footer from './components/includes/footer.vue'

export default {
  name: 'App',
  components: {
    Navigation,
    Footer

  }
}
</script>

<style>
#app {
  font-family: 'Krona One', sans-serif;
  font-size: 14px;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffe9d6;
  margin-top: 20px;
}
</style>
