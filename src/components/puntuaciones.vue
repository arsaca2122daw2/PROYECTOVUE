<template>
  <div>
    <div class="main">
      <div class="puntuaciones">
		<h2>PUNTUACIONES</h2>
          <table id="table">
              <tr>
                  <th>jugador</th>
                  <th>tiempo</th>
                  <th>errores</th>
                  <th>dificultad</th>
              </tr>
              <tr>
                  <td>ben isshowspeed</td>
                  <td>19:05</td>
                  <td>5</td>
                  <td>fácil</td>
              </tr>
          </table>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'PuntuacionesComponent',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>


body{
	
}

header {
	width: 100%;
}

h2{
font-size:40px;
margin-left:75px;
}

.main {
	width: 100%;
	display: flex;
}

.puntuaciones {
	width: 70%;
}

#table {
	width: 80%;
	font-size: 30px;
	margin-left: 50px;
	border-collapse: collapse;
	background-color: #ecd6c0;
}

th,
td {
	text-align: center;
	border: 3px solid black;
	background-color: #ecd6c0;
}

td {
	font-size: 25px;
}

th {
	padding: 20px;
}

.dificultad {
	float: right;
	position: relative;
	margin-top: -100px;
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
