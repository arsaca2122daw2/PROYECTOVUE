<template>
    <div class="dificultad">
        <h2>Elige dificultad</h2>
        <div class="botones">
            <a href="#/facil" v-on:click="navegar" id="buton1">Fácil</a>
            <a href="#/medio" v-on:click="navegar" id="buton2">Medio</a>
            <a href="#/dificil" v-on:click="navegar" id="buton3">Díficil</a>
            <a href="#/" v-on:click="navegar" id="buton4">Menú</a>
        </div>
    </div>
</template>

<script>
export default {
  name: 'BotonesComponent',
  props: {
    msg: String
  }
}
</script>

<style scoped>
.dificultad {
	float: right;
	position: relative;
	margin-top: -220px;
	margin-right: 50px;
	width: 25%;
	font-size: 25px;
}

.dificultad h2 {
	margin-left: 17%;
}

.botones {
	display: flex;
	flex-direction: column;
	width: 200px;
	margin: auto;
}

a {
	align-self: center;
	margin-top: 35px;
	width: 150px;
	border-radius: 25px;
	height: 60px;
	font-size: 25px;
	cursor: pointer;
	text-align: center;
	padding-top: 25px;
	border: 2px solid black;
	text-decoration: none;
	color: black;
}

a:active{
	opacity: 0.6;
}

a:visited{
	color: black;
}

#buton1 {
	background-color: #b0f2c2;
}

#buton2 {
	background-color: #ffda9e;
}

#buton3 {
	background-color: #fcb7af;
}

#buton4 {
	background-color: lightgrey;
}
</style>