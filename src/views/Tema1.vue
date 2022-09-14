<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Análisis de datos
    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/imagen1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 El análisis de datos consiste en la interpretación de la información recolectada por sistemas como: 
          span.resaltado.text-bold la observación, las encuestas o las entrevistas
          span . Con ello, se puede generar nuevo conocimiento o alcanzar conclusiones encausadas a los propósitos del investigador y los usuarios de la información.
    p.text-center.my-5 La información puede ser:
    .row.ampliar.px-5.fondo-1.justify-content-center
      .col-xxl-5.col-xl-5.col-lg-5.col-md-12
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/tema1/icono1.svg')
          .tarjeta.fondo-2
            .p-4
              h4 Cuantitativa
              p.mb-0 Se expresa en números.
              p Compila y organiza la información.
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/tema1/icono2.svg')
          .tarjeta.fondo-2
            .p-4
              h4 Cualitativa
              p.mb-0 Es descriptiva y aporta detalles asociados a las catracterísticas del hecho investigado.
              p Se hace necesario codificar la información para su análisis, usando variables o códigos cualitativos u omisiones, según sea el caso.
      .col-xxl-5.col-xl-5.col-lg-5.col-md-12
        img(src="@/assets/curso/tema1/imagen2.jpg")
    p.my-5 Un ejemplo común es la elaboración de encuestas con preguntas cerradas; en este tipo de documentos, usualmente se limitan las posibilidades de respuesta a un número pequeño de opciones. Así, la codificación se diseña directamente sobre los mismos formularios, previa recolección de la información. Las metodologías más populares incluyen opciones de respuesta como Falso (F) o Verdadero (V), o literales o numéricos que se asocian a cada opción de respuesta, tales como: (a, b, c o 1, 2, 3).
    .row.justify-content-center
      .col-xxl-6.col-xl-6.col-lg-6.col-md-12
        img(src="@/assets/curso/tema1/imagen3.jpg")
      .col-xxl-6.col-xl-6.col-lg-6.col-md-12
        p Cuando las preguntas son abiertas, la codificación debe darse de forma posterior a la recolección de información, puesto que no hay forma de anticiparse a las posibilidades de respuesta que dará la persona consultada. Una vez se cuenta con toda la información, es posible diseñar categorías de respuestas y a cada una otorgarle algún valor para lograr consolidarlas en menos opciones.
        p La codificación es un sistema utilizado de forma frecuente con el objetivo de compactar la información y presentarla de forma más amigable a los interesados. En este sentido, lo más recomendable es que la codificación no abarque un número muy elevado de opciones, puesto que restaría utilidad a su propósito principal, así, se espera que las opciones en la codificación se mantengan por debajo de 10 códigos para cada variable.
    .cajon.color-acento-contenido.p-4.my-4.fondo-3
      p Cuando se recibe una cantidad muy variada de respuestas, se pueden desestimar aquellas que tengan poca relevancia estadística. Por ejemplo, aquellas respuestas coincidentes, que sumadas no representen más del 5%, y que, por lo tanto, no tengan tanto peso sobre el análisis de la información, pueden omitirse, para reducir las posibilidades de respuesta dadas por los consultados.
    separador
    #t_1_1.titulo-segundo.color-acento-contenido
      h2 1.1 Tabulación
    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/imagen4.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p La tabulación es un sistema que permite organizar los datos ya recolectados haciendo uso de tablas que permitan presentar la información de forma consolidada y resumida, de tal manera que se facilite el análisis por parte de los usuarios.
        br
        br
        p Su principal objetivo es presentar cuadros de fácil manejo, ahorrando tiempo y mostrándolos de una forma en la que se pueda obtener nueva información útil, identificando tendencias o las características más populares de los hechos investigados.
    p.my-5 Si bien la tabulación cuenta con una mecánica establecida, la naturaleza de la información puede llevar a aplicar estrategias diferenciadas. A continuación, se presentan una serie de instrucciones para tabular la información cuantitativa y cualitativa.
    .row.my-4.align-items-center(data-aos="fade-down-right")
      .col-xxl-1.col-xl-1.col-lg-1.col-md-1.col-sm-1.col-2
        .row
          .col-xxl-5.col-xl-5.col-lg-6.col-md-8.col-sm-10.col-7
            img(src="@/assets/curso/tema1/fondo2.jpg")
      .col-xxl-6.col-xl-6.col-lg-6.col-md-7.col-sm-10.col-10.ps-0
        h4.mb-0.ms-0.margentitulo2 Tabulación cuantitativa
    p Consolida la información cuantificable o medible, por lo que, por norma general, se subclasifican las opciones por tipo de variable de respuesta. 
    p Si estas son pocas 
      span.text-bold.resaltado (menos de 30, según diversos autores)
      span , se listan en la columna izquierda de la tabla, mientras a la derecha se presentan las frecuencias absolutas y relativas. La frecuencia absoluta consiste en el conteo de las respuestas según la variable, es decir, el número de veces que las personas consultadas dieron una misma respuesta; mientras que la relativa presenta la proporción en función del total de respuestas obtenidas.
    .row.mb-5.justify-content-center
      .col-xxl-4.col-xl-4.col-lg-4.col-md-6.col-sm-12
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/10.svg')
          .tarjeta.fondo-3.anchotarjetaavatar
            .p-4
              p.text-bold.text-center Frecuencias absolutas
              p.mb-0.text-center Conteo según la variable.
              p.text-center Número.

      .col-xxl-4.col-xl-4.col-lg-4.col-md-6.col-sm-12
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/porcentaje.svg')
          .tarjeta.fondo-3.anchotarjetaavatar
            .p-4
              p.text-bold.text-center Frecuencias relativas
              p.text-center Proporción en función del total de respuestas optenidas.
              p.text-center Porcentaje.





</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
