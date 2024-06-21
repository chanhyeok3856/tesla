<template>
  <div id="app">
    <HeaderComponent />
    <MainContentComponent />
    <FooterComponent />
  </div>
</template>

<script>
import HeaderComponent from './components/Header.vue';
import MainContentComponent from './components/MainContent.vue';
import FooterComponent from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    HeaderComponent,
    MainContentComponent,
    FooterComponent
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
  margin-top: 0;
}
</style>
