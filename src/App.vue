<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <MiPrueba mensaje/>
  <ListaComida/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MiPrueba from './components/MiPrueba.vue'
import ListaComida from './components/ListaComida.vue'

export default {
  name: 'App',
  components: {
    HelloWorld, 
    MiPrueba,
    ListaComida
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
  margin-top: 60px;
  margin-left: auto;
  margin-right: auto;
}
</style>
