<template>
  <MapOl></MapOl>
</template>
 
<script>
import MapOl from './components/MapOl.vue'
 
export default {
  name: 'App',
  components: {
    MapOl
  }
}
</script>
 
<style>
@import url('../node_modules/ol/src/ol.css');

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
 
html, body, #map, #app {
  height: 100%;
  margin: 0;
  padding: 0;
}
</style>