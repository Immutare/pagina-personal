<template lang="html">
  <div class="parallax"></div>
</template>

<script>
export default {
}
</script>

<style lang="css">
.parallax{
  background-image:url("/static/images/fondo.jpg");/*Imagen que se va poner en el fondo*/
	height: 100vh; /*El vh sirve para que siempre cubra el 100% del tamaño del navegador*/
	background-size: cover;/*Hace que la imagen cubra toda la sección*/
	background-repeat: no-repeat; /*Evita que se repita el fondo*/
	background-attachment: fixed;/*En este se dice que no se mueva la imagen de lugar y haga el efecto de parallax*/
}
</style>
