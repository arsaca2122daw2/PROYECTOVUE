<template>
  <div id="app">
    <h1>SUDOKU.</h1>
    <Puntuaciones msg="Welcome to Your Vue.js App"/>
    <Botones/>
  </div>
</template>

<script>
import Puntuaciones from './components/puntuaciones.vue'
//import Sudoku from './components/sudoku.vue'
import Botones from './components/botones.vue'

export default {
  name: 'App',
  components: {
    Puntuaciones, Botones
  }
}
</script>

<style>
@font-face {
	font-family: FUENTE;
	src: url("assets/go3v2.ttf");
}

* {
	font-family: FUENTE;
	background-color: #fdf9c4;
  color:black;
}

h1{
  text-align:center;
  font-size:75px;
}

</style>
