<template>
  <div id="app">
    <PageHeader />
    <HomePage />
  </div>
</template>

<script>
import HomePage from './components/HomePage.vue'
import PageHeader from './components/PageHeader.vue'

export default {
  components: {
    PageHeader,
    HomePage
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
