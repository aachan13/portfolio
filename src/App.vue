<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <navigation-component></navigation-component>

  <div class="container p-5">
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
@font-face {
    font-family: 'Calibre';
    src: url('fonts/CalibreBlack.otf');
    font-weight: bolder;
    font-style: normal;
}

@font-face {
    font-family: 'Calibre';
    src: url('fonts/CalibreBold.otf');
    font-weight: bold;
    font-style: normal;
}

@font-face {
    font-family: 'Calibre';
    src: url('fonts/CalibreMedium.otf');
    font-weight: 500;
    font-style: normal;
}

@font-face {
    font-family: 'Calibre';
    src: url('fonts/CalibreMediumItalic.otf');
    font-weight: 500;
    font-style: italic;
}

@font-face {
    font-family: 'Calibre';
    src: url('fonts/CalibreRegular.otf');
    font-weight: 400;
    font-style: normal;
}

@font-face {
    font-family: 'Calibre';
    src: url('fonts/CalibreRegularItalic.otf');
    font-weight: 400;
    font-style: italic;
}

#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif; */
  font-family: 'Calibre';
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
