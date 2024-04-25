<template>
  <div>
    <b-nav>
      <b-nav-item active>Active</b-nav-item>
      <b-nav-item>Link</b-nav-item>
      <b-nav-item>Another Link</b-nav-item>
      <b-nav-item disabled>Disabled</b-nav-item>
    </b-nav>  
  </div>
</template>

<script>
</script>

<style>
/* Estilo para los elementos de navegación */
/* Estilo para los elementos de navegación */
/* Estilo para los elementos de navegación */
b-nav-item {
  margin-left: 30px; /* Enviar las letras un poco más a la izquierda */
  margin-right: 25px; /* Aumentar el espacio entre los elementos */
  font-size: 28px; /* Hacer los elementos de navegación un poco más largos */
  padding: 0px; /* Eliminar el padding adicional */
}

/* Centrar el texto en el contenedor */
div {
  position: fixed; /* Posiciona el elemento de manera fija */
  top: 0px;
  bottom: 470px;
  left: 0px; /* Lo coloca en la parte superior de la pantalla */
  width: 100%; /* Ancho completo */
  z-index: 1000; /* Asegura que esté por encima de otros elementos */
  background-image: url("/public/imagen1.png"); /* Ruta relativa a la carpeta 'public' */
  background-size: cover; /* Ajusta la imagen de fondo para que cubra todo el contenedor */
  background-position: center; /* Centra la imagen de fondo */
  color: white;
  text-align: left; /* Centra el texto */
}

</style>