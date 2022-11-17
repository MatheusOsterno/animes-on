<template>
  <HeaderAnimeOn />
  <CarroselAnimeOn />
  <SectionMain />
  <FooterAnimeOn />
</template>

<script>

import CarroselAnimeOn from './components/CarroselAnimeOn.vue';
import HeaderAnimeOn from './components/HeaderAnimeOn.vue';
import SectionMain from './components/SectionMain.vue';
import FooterAnimeOn from './components/FooterAnimeOn.vue'


export default {
    components: { HeaderAnimeOn, CarroselAnimeOn, SectionMain, FooterAnimeOn }
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

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
