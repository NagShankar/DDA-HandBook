<template>
  <Navigation/>
  <Home/>
</template>

<script>
import Navigation from './components/Navigation.vue'
import Home from './pages/Home.vue'

export default {
  name: 'App',
  components: {
    Home,
    Navigation
  }
}
</script>

<style>
* {
  box-sizing: border-box;
}

html {
  font-family: sans-serif;
}

body {
  margin: 0;
}
</style>
