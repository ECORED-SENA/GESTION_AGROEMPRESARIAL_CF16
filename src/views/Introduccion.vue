<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    p Las empresas agroindustriales colombianas tienen que hacer frente al cambio incorporando a la gestión y administración de las mismas elementos tecnológicos que les permitan ser transformadoras en su sector e innovar para poder ser competentes, es por ello que el análisis de datos - Big data y la presentación de informes de alta calidad a las juntas o directivas de las empresas, con relación a sí mismas y a su competencia, ya sea a nivel nacional o internacional, se hace necesaria, hoy por hoy, con el fin de tomar decisiones claves para mantenerse en el mercado.
    p.mb-5 Esto lo puede contemplar en el siguiente video introductorio sobre la importancia del análisis de datos y elaboración de informes del programa.
    figure
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/0vTv9pTVgvQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
