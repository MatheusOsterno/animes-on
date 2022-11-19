<template>
  <HeaderAnimeOn />
  <router-view/>
  <FooterAnimeOn />
</template>

<script>


import HeaderAnimeOn from './components/HeaderAnimeOn.vue';

import FooterAnimeOn from './components/FooterAnimeOn.vue'


export default {
    components: { HeaderAnimeOn, FooterAnimeOn }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #1b344d;
  background: #0b0c2a;
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
