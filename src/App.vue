<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <div class="container mx-auto p-6">

    <navigation-component></navigation-component>
    <main-component></main-component>

  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import MainComponent from './components/MainComponent.vue'
import NavigationComponent from './components/NavigationComponent.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    MainComponent,
    NavigationComponent
  }
}
</script>

<style>

#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif; */
  font-family: 'Quicksand', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
h1,h2,h3{
  font-family: 'Inter', sans-serif;
}
</style>
