<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="fade-down-right")
      .titulo-principal__numero
        span 1
      h1 Análisis de datos
    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5(data-aos="fade-down-left")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/imagen1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 El análisis de datos consiste en la interpretación de la información recolectada por sistemas como: 
          span.resaltado.text-bold la observación, las encuestas o las entrevistas
          span . Con ello, se puede generar nuevo conocimiento o alcanzar conclusiones encausadas a los propósitos del investigador y los usuarios de la información.
    p.text-center.my-5(data-aos="fade-down-right") La información puede ser:
    .row.ampliar.px-5.fondo-1.justify-content-center
      .col-xxl-5.col-xl-5.col-lg-5.col-md-12(data-aos="fade-down-right")
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
      .col-xxl-5.col-xl-5.col-lg-5.col-md-12(data-aos="fade-down-left")
        img(src="@/assets/curso/tema1/imagen2.jpg")
    p.my-5(data-aos="fade-down-right") Un ejemplo común es la elaboración de encuestas con preguntas cerradas; en este tipo de documentos, usualmente se limitan las posibilidades de respuesta a un número pequeño de opciones. Así, la codificación se diseña directamente sobre los mismos formularios, previa recolección de la información. Las metodologías más populares incluyen opciones de respuesta como Falso (F) o Verdadero (V), o literales o numéricos que se asocian a cada opción de respuesta, tales como: (a, b, c o 1, 2, 3).
    .row.justify-content-center
      .col-xxl-6.col-xl-6.col-lg-6.col-md-12.mb-4(data-aos="fade-down-right")
        img(src="@/assets/curso/tema1/imagen3.jpg")
      .col-xxl-6.col-xl-6.col-lg-6.col-md-12(data-aos="fade-down-left")
        p Cuando las preguntas son abiertas, la codificación debe darse de forma posterior a la recolección de información, puesto que no hay forma de anticiparse a las posibilidades de respuesta que dará la persona consultada. Una vez se cuenta con toda la información, es posible diseñar categorías de respuestas y a cada una otorgarle algún valor para lograr consolidarlas en menos opciones.
        p La codificación es un sistema utilizado de forma frecuente con el objetivo de compactar la información y presentarla de forma más amigable a los interesados. En este sentido, lo más recomendable es que la codificación no abarque un número muy elevado de opciones, puesto que restaría utilidad a su propósito principal, así, se espera que las opciones en la codificación se mantengan por debajo de 10 códigos para cada variable.
    .cajon.color-acento-contenido.p-4.my-4.fondo-3(data-aos="fade-down-right")
      p Cuando se recibe una cantidad muy variada de respuestas, se pueden desestimar aquellas que tengan poca relevancia estadística. Por ejemplo, aquellas respuestas coincidentes, que sumadas no representen más del 5%, y que, por lo tanto, no tengan tanto peso sobre el análisis de la información, pueden omitirse, para reducir las posibilidades de respuesta dadas por los consultados.
    separador
    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-down-left")
      h2 1.1 Tabulación
    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/imagen4.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p La tabulación es un sistema que permite organizar los datos ya recolectados haciendo uso de tablas que permitan presentar la información de forma consolidada y resumida, de tal manera que se facilite el análisis por parte de los usuarios.
        br
        br
        p Su principal objetivo es presentar cuadros de fácil manejo, ahorrando tiempo y mostrándolos de una forma en la que se pueda obtener nueva información útil, identificando tendencias o las características más populares de los hechos investigados.
    p.my-5(data-aos="fade-down-right") Si bien la tabulación cuenta con una mecánica establecida, la naturaleza de la información puede llevar a aplicar estrategias diferenciadas. A continuación, se presentan una serie de instrucciones para tabular la información cuantitativa y cualitativa.
    .row.my-4.align-items-center(data-aos="fade-down-right")
      .col-xxl-1.col-xl-1.col-lg-1.col-md-1.col-sm-1.col-2(data-aos="fade-down-right")
        .row
          .col-xxl-5.col-xl-5.col-lg-6.col-md-8.col-sm-10.col-7
            img(src="@/assets/curso/tema1/fondo2.jpg")
      .col-xxl-6.col-xl-6.col-lg-6.col-md-7.col-sm-10.col-10.ps-0(data-aos="fade-down-left")
        h4.mb-0.ms-0.margentitulo2 Tabulación cuantitativa
    p(data-aos="fade-down-left") Consolida la información cuantificable o medible, por lo que, por norma general, se subclasifican las opciones por tipo de variable de respuesta. 
    p(data-aos="fade-down-right") Si estas son pocas 
      span.text-bold.resaltado (menos de 30, según diversos autores)
      span , se listan en la columna izquierda de la tabla, mientras a la derecha se presentan las frecuencias absolutas y relativas. La frecuencia absoluta consiste en el conteo de las respuestas según la variable, es decir, el número de veces que las personas consultadas dieron una misma respuesta; mientras que la relativa presenta la proporción en función del total de respuestas obtenidas.
    .row.mb-5.justify-content-center
      .col-xxl-4.col-xl-4.col-lg-4.col-md-6.col-sm-12(data-aos="fade-down-left")
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/10.svg')
          .tarjeta.fondo-3.anchotarjetaavatar
            .p-4
              p.text-bold.text-center Frecuencias absolutas
              p.mb-0.text-center Conteo según la variable.
              p.text-center Número.

      .col-xxl-4.col-xl-4.col-lg-4.col-md-6.col-sm-12(data-aos="fade-down-right")
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/porcentaje.svg')
          .tarjeta.fondo-3.anchotarjetaavatar
            .p-4
              p.text-bold.text-center Frecuencias relativas
              p.text-center Proporción en función del total de respuestas optenidas.
              p.text-center Porcentaje.
    .row.justify-content-center.mb-4
      .col-xxl-7.col-xl-7.col-lg-7.col-md-12.mb-4(data-aos="fade-down-left")
        p En los casos en los que las 
          span.resaltado.text-bold variables ascienden a números mayores
          span , su análisis de forma individual puede resultar muy complejo, por lo que se recomienda reducir las posibilidades haciendo uso de 
          span.resaltado.text-bold intervalos que comprendan un grupo de variables.
        p.mb-0 La definición de la magnitud de los intervalos está sometida a juicio del investigador, pero se debe respetar el cumplimiento de dos normas esenciales: 
        .row.justify-content-center.align-items-center.mt-4(data-aos="fade-down-left")
          .col-2.p-sm-4
            img(src='@/assets/curso/tema1/lista.svg')
          .col-10
            span.text-bold.resaltado Norma 1: 
            span Que los intervalos sean excluyentes entre sí, es decir, que una respuesta solo pueda estar en uno de los intervalos, y no en dos o más a la vez.
        .row.justify-content-center.align-items-center(data-aos="fade-down-right")
          .col-2.px-sm-4.pt-0
            img.mt-0(src='@/assets/curso/tema1/lista.svg')
          .col-10
            span.text-bold.resaltado Norma 2: 
            span.mb-0 Que todos los datos puedan encajar en alguno de los intervalos propuestos, de tal forma que ninguna variable quede huérfana.
      .col-xxl-5.col-xl-5.col-lg-5.col-md-12(data-aos="fade-down-right")
        img(src='@/assets/curso/tema1/imagen5.jpg')
    p.p-5.mb-0.fondo-4(data-aos="fade-down-left") Como se acaba de mencionar, los intervalos son 
      span.text-bold definidos de forma arbitraria por parte del investigador
      span , sin embargo, es recomendable que su amplitud sea equivalente entre sí. Esto significa que cada intervalo contenga, en lo posible, la misma cantidad de variables posibles. 
    p.my-5(data-aos="fade-down-right") La situación anterior no es una exigencia ni es obligatoria, y esto se debe a que, en ocasiones, diseñar intervalos desiguales puede resultar de especial utilidad; por ejemplo, si se busca determinar el rango de edades que componen a una población determinada, puede resultar más útil separarlos entre menores de edad, adultos, y ancianos. La siguiente tabla ejemplifica la respuesta brindada por cien encuestados respecto a su edad en los intervalos mencionados:
    .row.justify-content-center
      .col-xxl-10.col-xl-10.col-lg-10.col-md-12(data-aos="fade-down-left")
        .titulo-sexto.color-acento-contenido
          h5 Tabla 1.
          span Tabulación de datos cuantitativos
        .tabla-a.color-primario.mb-5
          table
            thead.fondo-5
              tr
                th.bordederecha Variable
                th.bordederecha Frecuencia absoluta
                th Frecuencia relativa
            tbody.text-center
              tr
                td.bordederecha.bordeabajo.fondo-6 Menores de 18 años
                td.bordederecha.bordeabajo 27
                td.bordeabajo 27 %
              tr
                td.bordederecha.bordeabajo.fondo-6 Mayores de 18 y menores de 60 años
                td.bordederecha.bordeabajo 53
                td.bordeabajo 53 %
              tr
                td.bordederecha.bordeabajo.fondo-6 Mayores de 60 años
                td.bordederecha.bordeabajo.fondo-7 20
                td.bordeabajo.fondo-7 20 %
              tr
                td.bordederecha.bordeabajo.fondo-6 Total encuestados
                td.bordederecha.bordeabajo 100
                td.bordeabajo
    p.mb-4(data-aos="fade-down-left") Por otro lado, como 
      span.text-bold sistema de comprobación adicional
      span , la suma de las frecuencias absolutas debe ser igual al número de personas consultadas, pues, de lo contrario, habría respuestas que fueron sumadas en más de una ocasión, o que no se tuvieron presentes en la tabulación. Además, la suma de las frecuencias relativas también debe ser equivalente al 100 %, puesto que se contemplaron todas las respuestas posibles.
    .row.my-4.align-items-center(data-aos="fade-down-right")
      .col-xxl-1.col-xl-1.col-lg-1.col-md-1.col-sm-1.col-2
        .row
          .col-xxl-5.col-xl-5.col-lg-6.col-md-8.col-sm-10.col-7
            img(src="@/assets/curso/tema1/fondo2.jpg")
      .col-xxl-6.col-xl-6.col-lg-6.col-md-7.col-sm-10.col-10.ps-0
        h4.mb-0.ms-0.margentitulo2 Tabulación cuanlitativa
    .row.justify-content-center
      .col-xxl-6.col-xl-6.col-lg-6.col-md-12.mb-4(data-aos="fade-down-left")
        p En este caso, la 
          span.text-bold.resaltado información es descriptiva
          span , puesto que presenta detalles frente a un fenómeno específico, pero los datos no pueden cuantificarse. Debido a las limitaciones de la información recolectada, la tabulación suele limitarse al 
          span.text-bold conteo de las respuestas coincidentes y su participación frente a la totalidad de respuestas obtenidas.
        p Su mecánica es similar a las variables cuantitativas, sin embargo, resulta más complejo diseñar intervalos que comprendan más de una variable. En esos casos, los investigadores pueden buscar elementos coincidentes según el tipo de respuestas y así reducir las opciones a presentar en la tabla. 
        p A continuación, se presenta una tabla que comprende las respuestas dadas por diez personas, en una escuela secundaria, respecto a la pregunta: ¿cuál es su materia favorita?
      .col-xxl-6.col-xl-6.col-lg-6.col-md-12(data-aos="fade-down-right")
        img(src="@/assets/curso/tema1/imagen6.jpg")
    .row.justify-content-center.mt-4
      .col-xxl-10.col-xl-10.col-lg-10.col-md-12(data-aos="fade-down-left")
        .titulo-sexto.color-acento-contenido
          h5 Tabla 2
          span Tabulación de datos cuanlitativos
        .tabla-a.color-primario.mb-5(data-aos="fade-down-right")
          table
            thead.fondo-5
              tr
                th.bordederecha Variable
                th.bordederecha Frecuencia absoluta
                th Frecuencia relativa
            tbody.text-center
              tr
                td.bordederecha.bordeabajo.fondo-6 Matemáticas
                td.bordederecha.bordeabajo 2
                td.bordeabajo 20 %
              tr
                td.bordederecha.bordeabajo.fondo-6 Inglés
                td.bordederecha.bordeabajo 3
                td.bordeabajo 30 %
              tr
                td.bordederecha.bordeabajo.fondo-6 Educación física
                td.bordederecha.bordeabajo.fondo-7 5
                td.bordeabajo.fondo-7 50 %
              tr
                td.bordederecha.bordeabajo.fondo-6 Total encuestados
                td.bordederecha.bordeabajo 10
                td.bordeabajo
    p.mb-5(data-aos="fade-down-right") Si se extrapola la consulta a cientos de estudiantes, las opciones de respuesta pueden crecer exponencialmente, por lo que una forma de consolidar los datos en menos variables consiste en la agrupación de materias por área del conocimiento. Así, en lugar de materias, se tabularían intervalos como 
      span.text-bold.resaltado “materias de humanidades”, “materias de ciencias exactas”, “materias de idiomas”
      span , entre otras.
    .row.justify-content-center
      .col-lg-10.col-md-12(data-aos="fade-down-left")
        .tarjeta.color-acento-contenido.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema1/camara.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p Como parte de su aprendizaje autónomo, le invitamos a revisar el video de 
                    span.text-bold Math2me 
                    span sobre Tabulación de datos cualitativos, que le permitirá analizar y reforzar el tema, el cual se encuentra en la sección de material complementario. 
                .col-sm-auto
                  a.boton.color-acento-botones(href="https://google.com/" target="_blank")
                    span.text-dark Ver video
                    i.fas.fa-play-circle
    separador
    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="fade-down-right")
      h2 1.2 Gráficos
    .row.ampliar.px-5.fondo-9
      .col-12
        .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5(data-aos="fade-down-left")
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema1/imagen7.jpg')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 La tabulación funciona como un sistema de  
              span.resaltado.text-bold organización de la información 
              span  para ser presentada de una forma más 
              span.resaltado.text-bold concisa 
              span y que permita entender de forma más 
              span.resaltado.text-bold clara 
              span los valores obtenidos en el proceso de recolección. No obstante, esta sigue siendo plana y discreta, por lo que se requiere de un nivel de conocimiento intermedio para obtener conclusiones de la misma.
        .row.justify-content-center.my-5
          .col-xxl-6.col-xl-6.col-lg-6.col-md-12.mb-4(data-aos="fade-down-left")
            img(src="@/assets/curso/tema1/figura1.svg")
          .col-xxl-6.col-xl-6.col-lg-6.col-md-12(data-aos="fade-down-right")
            p La representación gráfica de la información se ofrece como la alternativa de mayor accesibilidad y más fácil entendimiento, pues no solo traslada las cifras más relevantes, sino que entrega apoyos adicionales a través de líneas de 
              span.text-bold.resaltado tendencia o códigos de colores 
              span que incrementan significativamente la comprensibilidad de los resultados de cualquier estudio.
            p No es para nada raro que las reuniones entre miembros directivos de una empresa suelan nutrirse con informes de las áreas partícipes que se adornan con tablas y gráficas que les permiten a los propietarios o gerentes empaparse de las situaciones de una forma pragmática. Al final, estos resultan un compendio de secciones escritas complementadas con gráficos de fácil entendimiento, donde se busca, en pocas páginas, resumir la compleja situación de la organización.
            p Con los gráficos estadísticos se busca la representación de series de datos que han sido obtenidos previamente, y que, por norma general, ya han sido tabulados. Con ellos, se presenta de forma visual la evolución o tendencias que experimenta cada una de las variables estudiadas, comparándolas entre sí y en forma global. De esta manera, se desarrolla un lenguaje más comprensible para los usuarios, que no siempre están lo suficientemente preparados para comprender la información bajo los demás sistemas.
        .cajon.color-acento-contenido.p-4.my-4.fondo-3(data-aos="fade-down-right")
          p La variedad de gráficos es tan amplia como la imaginación. Actualmente, se utilizan muchas clases en función de la naturaleza de los estudios y lo que se espera transmitir o dar a entender a través de ellos. A continuación, se describen algunos de los más utilizados en el ámbito empresarial.
        .row.my-4.align-items-center(data-aos="fade-down-right")
          .col-xxl-1.col-xl-1.col-lg-1.col-md-1.col-sm-1.col-2
            .row
              .col-xxl-5.col-xl-5.col-lg-6.col-md-8.col-sm-10.col-7
                img(src="@/assets/curso/tema1/fondo2.jpg")
          .col-xxl-6.col-xl-6.col-lg-6.col-md-7.col-sm-10.col-10.ps-0
            h4.mb-0.ms-0.margentitulo2 Gráfico de barras
        p.my-5(data-aos="fade-down-left") Como se mencionó previamente, lo más natural es que la información recolectada ya se haya tabulado, lo que facilita su representación gráfica. La mecánica aplicable consiste en la utilización de un 
          span.resaltado.text-bold plano cartesiano 
          span donde, por lo general, se hace uso de los ejes de la siguiente forma:
        .row.justify-content-center(data-aos="fade-down-right")
          .col-12.fondo-8.p-3
            .row.justify-content-center.align-items-center
              .col-lg-1.col-2(data-aos="fade-down-right")
                img(src="@/assets/curso/tema1/figura2.svg")
              .col-lg-11.col-10(data-aos="fade-down-left")
                p.text-bold.mb-0 Para tener en cuenta:
                p En el eje horizontal (X), se ubican las variables a observar, mientras que en el eje vertical (Y), se asignan los valores de las frecuencias absolutas.  
        .row.justify-content-center.my-5
          .col-lg-7.col-md-12.mb-4(data-aos="fade-down-right")
            p Este estilo de gráficos es recomendable para:
            ul.lista-ul
              li 
                i.fas.fa-angle-right
                | Comparar magnitudes o cantidades, y para 
              li 
                i.fas.fa-angle-right
                | Evaluar las variaciones en el tiempo de algún indicador o resultado.
            p En los casos anteriores, se hace uso del eje horizontal para ubicar las fechas en las que se hace el estudio.
            p El siguiente ejemplo permite ilustrar el uso de los gráficos de barras. Supóngase que se consulta a 50 personas por su color favorito, obteniendo estos resultados:
          .col-lg-3.col-md-6.col-sm-6.col-8(data-aos="fade-down-left")
            img(src="@/assets/curso/tema1/figura3.svg")
    .row.justify-content-center.mt-5
      .col-lg-6.col-md-12(data-aos="fade-down-right")
        .titulo-sexto.color-acento-contenido
          h5 Tabla 3.
          span Tabulación de datos cualitativos
    .row.ampliar.px-5.fondo-10.justify-content-center
      .col-lg-6.col-12(data-aos="fade-down-right")
        .tabla-a.color-primario.mb-5
          table
            thead.fondo-5
              tr
                th.bordederecha Color favorito
                th Frecuencia absoluta
            tbody.text-center
              tr
                td.bordederecha.bordeabajo.fondo-6 Blanco
                td.bordeabajo 8
              tr
                td.bordederecha.bordeabajo.fondo-6 Negro
                td.bordeabajo 7
              tr
                td.bordederecha.bordeabajo.fondo-6 Rojo
                td.bordeabajo.fondo-7 15
              tr
                td.bordederecha.bordeabajo.fondo-6 azul
                td.bordeabajo 20
              tr
                td.bordederecha.bordeabajo.fondo-6 Total
                td.bordeabajo.fondo-7 50
    .row.justify-content-center.my-5
      .col-lg-10.col-md-12(data-aos="fade-down-right")
        .titulo-sexto.color-acento-contenido
          h5 Figura 1.
          span Gráficos de barras horizontal y vertical
        .row.justify-content-center.align-items-center.my-4
          .col-lg-6.col-md-12.mb-4(data-aos="fade-down-right")
            img(src="@/assets/curso/tema1/grafico1.svg")
          .col-lg-6.col-md-12(data-aos="fade-down-left")
            img(src="@/assets/curso/tema1/grafico2.svg")
    p.mb-5(data-aos="fade-down-left") Como puede verse, su 
      span.resaltado.text-bold disposición vertical u horizontal 
      span depende del preparador de la información; más allá de eso, la información contenida sigue siendo la misma y el análisis se puede hacer con cualquiera de ellas. Ahora bien, aunque para este caso solo se trabajó con una variable, es posible hacer uso de este tipo de gráficos en estudios que involucren 
      span.resaltado.text-bold más variables y sujetos
      span ; en tal caso, las barras pueden presentarse 
      span.resaltado.text-bold agrupadas o apiladas, según la investigación.
    p.p-4.mb-0.fondo-4(data-aos="fade-down-right") Por ejemplo, si en una universidad se consulta a los estudiantes matriculados por la carrera que van a cursar, los resultados pueden presentarse de forma separada o agrupados por facultad; mientras que si se indaga por el número de estudiantes hombres o mujeres, puede ser más apropiado apilar los resultados.
    .row.justify-content-center.my-5
      .col-lg-10.col-md-12
        .row.justify-content-center.align-items-center
          .col-lg-6.col-md-12(data-aos="fade-down-right")
            .titulo-sexto.color-acento-contenido.mb-4
              h5 Figura 2.
              span Gráfico de barras agrupadas
            img(src="@/assets/curso/tema1/grafico3.svg")
          .col-lg-6.col-md-12(data-aos="fade-down-left")
            .titulo-sexto.color-acento-contenido.mb-4
              h5 Figura 3.
              span Gráfico de barras apiladas
            img(src="@/assets/curso/tema1/grafico4.svg")
    p.mb-5(data-aos="fade-down-left") El uso de los gráficos de barras está ampliamente expandido en toda clase de estudios estadísticos, bien sea para 
      span.text-bold.resaltado investigación académica o análisis empresarial
      span . Su utilidad está más que comprobada y sobran los ejemplos para evidenciar su efectividad. Por esto, dependerá de cada expositor cómo explotar este tipo de herramientas para la presentación de su trabajo.
    .row.my-4.align-items-center(data-aos="fade-down-right")
      .col-xxl-1.col-xl-1.col-lg-1.col-md-1.col-sm-1.col-2
        .row
          .col-xxl-5.col-xl-5.col-lg-6.col-md-8.col-sm-10.col-7
            img(src="@/assets/curso/tema1/fondo2.jpg")
      .col-xxl-6.col-xl-6.col-lg-6.col-md-7.col-sm-10.col-10.ps-0
        h4.mb-0.ms-0.margentitulo2 Gráfico de líneas
    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5.my-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/imagen8.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 La metodología de este tipo de gráficas es muy similar a la anterior, puesto que nuevamente hacen uso del plano cartesiano para ubicar variables en un eje y magnitudes en el otro. La principal diferencia respecto al gráfico de barras es que las líneas son especialmente útiles para identificar 
          span.text-bold.resaltado tendencias o medir la evolución de las variables en el tiempo.
    p.mb-5(data-aos="fade-down-left") También es viable incluir más de una variable para el análisis, así se facilitan las 
      span.text-bold.resaltado comparaciones o las mediciones con una línea de referencia
      span . La figura presentada a continuación ofrece un acercamiento a este tipo de gráficos, en el que se muestra la inflación del país año a año teniendo como referencia el incremento del salario mínimo.
    .row.justify-content-center.mt-5
      .col-lg-6.col-md-12(data-aos="fade-down-right")
        .titulo-sexto.color-acento-contenido
          h5 Figura 4.
          span Gráfico de líneas
    .row.ampliar.px-5.fondo-10.justify-content-center
      .col-lg-6.col-12(data-aos="fade-down-left")
        img(src="@/assets/curso/tema1/figura4.svg")
    .row.my-4.align-items-center(data-aos="fade-down-right")
      .col-xxl-1.col-xl-1.col-lg-1.col-md-1.col-sm-1.col-2(data-aos="fade-down-right")
        .row
          .col-xxl-5.col-xl-5.col-lg-6.col-md-8.col-sm-10.col-7
            img(src="@/assets/curso/tema1/fondo2.jpg")
      .col-xxl-6.col-xl-6.col-lg-6.col-md-7.col-sm-10.col-10.ps-0(data-aos="fade-down-left")
        h4.mb-0.ms-0.margentitulo2 Gráfico de sectores
    .cajon.color-acento-contenido.p-4.my-5.fondo-8(data-aos="fade-down-right")
      p.mb-0 Su disposición difiere de los tipos de gráficos anteriores, puesto que se visualiza como una 
        span.text-bold.resaltado representación circular 
        span de las frecuencias relativas de un elemento. Debido a su mecánica, cada variable se gráfica como una porción que junto a las demás conforman un todo.
    .row.justify-content-center
      .col-lg-6.col-md-12(data-aos="fade-down-left")
        p El círculo representa la totalidad de los datos obtenidos, mientras que cada sección independiente corresponde a una variable.
        p Debido a que, por lo general, involucra frecuencias relativas, se recomienda presentarlo incluyendo las cifras en 
          span.text-bold.resaltado términos porcentuales
          span . Es conocido como 
          span.text-bold.resaltado Diagrama de torta
          span , debido a su semejanza con un pastel porcionado para sus comensales. 
        p Este tipo de gráfico se recomienda cuando se evalúan pocos elementos o algunos de ellos destacan sobre los demás.Además, tiene mayor usabilidad si las variables asociadas corresponden a un número no tan grande, puesto que así son más apreciables las diferencias observadas.
        p A continuación, se presenta una figura que ejemplifica un gráfico de sectores utilizado en una compañía para conocer la composición de los gastos en los que incurrió para mantener su operación en marcha:
      .col-lg-6.col-md-12(data-aos="fade-down-right")
        .titulo-sexto.color-acento-contenido
          h5 Figura 5.
          span Gráfico de sectores
        img(src="@/assets/curso/tema1/figura5.svg")
    separador
    #t_1_3.titulo-segundo.color-acento-contenido(data-aos="fade-down-left")
      h2 1.3 Análisis comparativos
    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/imagen9.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 La forma de afrontar la revisión de la información recolectada puede tener distintos enfoques; cada intérprete podrá abordarla de la forma que considere más eficiente en términos de 
          span.text-bold.resaltado tiempo y recursos utilizados
          span ; sin embargo, 
          span.text-bold.resaltado el contraste entre la información 
          span obtenida y otros datos que funcionen como referencia es una de las prácticas más útiles y de mayor aceptación en cualquier disciplina.
    p.my-5(data-aos="fade-down-right") El análisis comparativo resulta ser una estrategia conveniente cuando se quiere analizar un elemento o fenómeno en un medio en el que no se da por primera vez. Así, las empresas diseñan estrategias y las comparan con las aplicadas en otras empresas, estimando su posición en el mercado a través de la evaluación de la competencia.
    .row.justify-content-center.align-items-center
      .col-lg-6.col-md-12.mb-4(data-aos="fade-down-right")
        img(src="@/assets/curso/tema1/imagen10.jpg")
      .col-lg-6.col-md-12(data-aos="fade-down-left")
        p Por otra parte, la información puede presentarse comparativa con otros periodos, determinando así la evolución de una entidad con el paso del tiempo. Sin ir muy lejos, los estados financieros de las empresas colombianas deben cumplir con el 
          span.text-bold.resaltado principio de comparabilidad
          span , de tal forma que no se pueden presentar de forma aislada, sino, junto a los del periodo anterior, para otorgarle un mayor contexto a la información y permitir visualizar las tendencias ocurridas en el tiempo estudiado.
        p La información a comparar puede ser de naturaleza 
          span.text-bold.resaltado  cuantitativa o cualitativa
          span . Generalmente, con los datos 
          span.text-bold.resaltado cuantitativos existe una mayor objetividad 
          span en cuanto a la evidencia, ya que las cifras, en sí mismas, permiten determinar variaciones positivas o negativas sin mayor trabajo. Caso contrario sucede con la información cualitativa, puesto que, al tratarse de 
          span.text-bold.resaltado  datos descriptivos 
          span y, por tanto, 
          span.text-bold.resaltado abiertos a una interpretación
          span , el criterio del analista puede diferir de los juicios que emitiría otro.
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-6.col-md-12.mb-4(data-aos="fade-down-right")
        p Este mismo tipo de situaciones se pueden presentar cuando la información a evaluar comprende datos de ambas naturalezas. Por ejemplo, evaluar las estrategias comerciales implementadas por la competencia, para determinar si son más efectivas que las propias, puede resultar en distintas conclusiones. 
        p Así, el análisis cuantitativo puede revelar que el volumen de ventas creció en mayor proporción para uno u otro, pero, al adentrarse en el análisis cualitativo, podría resultar casi imposible determinar con plena certeza cuál acción, tarea o actitud fue la que desencadenó en esos mejores resultados.
        p Por lo anterior, la correcta aplicación del 
          span.text-bold.resaltado análisis comparativo 
          span permite obtener 
          span.text-bold.resaltado información relevante 
          span respecto al medio en el que se desenvuelve una compañía, o bien, respecto a su versión de periodos anteriores. Su utilidad resalta frente a otras metodologías y puede funcionar de manera complementaria con otros sistemas de análisis.
      .col-lg-6.col-md-12(data-aos="fade-down-left")
        img(src="@/assets/curso/tema1/imagen11.jpg")
    p.mb-5.text-center(data-aos="fade-down-right") Para lograr mejores resultados, se recomienda la aplicación de los siguientes pasos:
    .row.justify-content-center
      .col-10
        PasosA.color-acento-botones.mb-5(tipo="n")
          .row.justify-content-around.align-items-center(data-aos="fade-down-right")
            .col-md-8.mb-4.mb-md-0
              p.text-bold Definir los elementos clave del estudio. 
              p Es decir, los datos que serán objeto de análisis y cuya medición será la que afecte más las conclusiones alcanzadas.
            .col-md-2.col-sm-5.col-5
              figure
                img(src='@/assets/curso/tema1/paso1.svg')

          .row.justify-content-around.align-items-center(data-aos="fade-down-left")
            .col-md-2.mb-4.mb-md-0.col-sm-5.col-5
              figure
                img(src='@/assets/curso/tema1/paso2.svg')
            .col-md-8
              p.text-bold Recopilar la información
              p Por un lado, los datos obtenidos para el elemento que será estudiado, por otro, la información que funcionará como comparativa. Deben obedecer a un mismo contexto, esto significa que las empresas a comparar deben pertenecer al mismo sector, o, en términos de tiempo, a periodos equivalentes.
              

          .row.justify-content-around.align-items-center(data-aos="fade-down-right")
            .col-md-8.mb-4.mb-md-0
              p.text-bold Estudiar o medir las diferencias.
              p Una vez se cuenta con los datos de la empresa y su comparativa, se deben realizar los cálculos de las cifras comparables, es decir, las que comprendan las mismas características objeto de análisis, por ejemplo: volumen de ventas de la empresa 1 con volumen de ventas de la empresa 2. 
              p En el caso de los 
                span.text-bold datos cualitativos
                span , es recomendable diseñar indicadores o estimar las variaciones en función de los resultados finales obtenidos. 
          
            .col-md-2.col-sm-5.col-5
              figure
                img(src='@/assets/curso/tema1/paso3.svg')

          .row.justify-content-center.align-items-center
            .col-md-2.mb-4.mb-md-0.col-sm-5.col-5.me-md-5(data-aos="fade-down-left")
              figure
                img(src='@/assets/curso/tema1/paso4.svg')
            .col-md-8.mb-4.mb-md-0(data-aos="fade-down-left")
              p.text-bold Identificar tendencias. 
              p En el análisis de la información, debe determinarse si existen tendencias que permitan establecer 
                span.text-bold patrones 
                span e identificar relaciones entre unos indicadores y otros. 
              p Por ejemplo: que la mayor inversión en publicidad redunda en nuevos clientes, o que la disminución en gastos de transporte tiene un impacto sobre el rendimiento de los canales de distribución.

          .row.justify-content-around.align-items-center
            .col-md-8.mb-4.mb-md-0(data-aos="fade-down-right")
              p.text-bold Presentar conclusiones.
              p La evaluación de las diferencias debe conllevar a la elaboración de una serie de 
                span.text-bold conclusiones respaldadas por el estudio
                span . Identificar el lugar dentro del mercado, estrategias a mejorar u objetivos a alcanzar en función de la empresa a la que se compara son algunos de los resultados esperados.
          
            .col-md-2.col-sm-5.col-5(data-aos="fade-down-left")
              figure
                img(src='@/assets/curso/tema1/paso5.svg')
    separador
    #t_1_4.titulo-segundo.color-acento-contenido(data-aos="fade-down-left")
      h2 1.4 Cálculo de indicadores
    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/imagen12.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Los indicadores funcionan como un elemento adicional para complementar el 
          span.text-bold.resaltado análisis de la información
          span , puesto que permiten medir los niveles de cumplimiento alcanzados en cualquier actividad ejecutada. Con ellos se puede calificar la gestión de un administrador y asignarle una valoración en función de qué tan cerca estuvo de cumplir las expectativas.
    p.my-5 Por lo anterior, definir metas u objetivos suele ser útil a la hora de definir las estrategias, puesto que otorga un norte al cual la empresa puede encaminar sus esfuerzos. Así, teniendo un camino trazado, es posible asignarle un valor al avance, para determinar la efectividad de las tareas o procesos aplicados.
    .row.justify-content-center(data-aos="fade-down-right")
      .col-12.fondo-8.p-3
        .row.justify-content-center.align-items-center
          .col-lg-1.col-2(data-aos="fade-down-right")
            img(src="@/assets/curso/tema1/figura2.svg")
          .col-lg-11.col-10(data-aos="fade-down-left")
            p.text-bold.mb-0 Para tener en cuenta:
            p Los indicadores de cumplimiento funcionan como herramienta de monitoreo en tiempo real, pues se miden los valores alcanzados en un momento presente, comparándolos con las cifras estimadas previamente. Esta metodología puede complementarse con análisis estadísticos, para ofrecer una visión más clara de los resultados esperados y su coherencia con los datos que ofrece el mercado con empresas que se dedican al mismo sector productivo.
    p.my-5 Según el tipo de indicador, la forma de calcularlo puede variar. A continuación, se presentan los sistemas más utilizados en un ambiente organizacional:
    .row.my-4.align-items-center
      .col-xxl-1.col-xl-1.col-lg-1.col-md-1.col-sm-1.col-2(data-aos="fade-down-right")
        .row
          .col-xxl-5.col-xl-5.col-lg-6.col-md-8.col-sm-10.col-7
            img(src="@/assets/curso/tema1/fondo2.jpg")
      .col-xxl-6.col-xl-6.col-lg-6.col-md-7.col-sm-10.col-10.ps-0(data-aos="fade-down-left")
        h4.mb-0.ms-0.margentitulo2 De flujo
    p.mb-5(data-aos="fade-down-right") Estiman el nivel de cumplimiento de aquellas actividades que se ejecutan de forma constante durante un periodo determinado. En este sentido, cada periodo ofrece una meta y, por lo tanto, una medición independiente. La fórmula para calcular este indicador es la siguiente:
    .row.justify-content-center
      .col-lg-6.col-md-12(data-aos="fade-down-left")
        img(src="@/assets/curso/tema1/figura6.svg")
    p.my-5(data-aos="fade-down-right") A continuación, se ofrece un ejemplo propio de un ambiente empresarial, donde se estima el volumen de ventas para cada año de ejercicio en la organización. Como se indicó previamente, cada una resulta independiente de las demás, por lo que la gestión de un año no afecta el rendimiento de los subsiguientes:
    .row.justify-content-center.mt-5
      .col-lg-10.col-md-12(data-aos="fade-down-right")
        .titulo-sexto.color-acento-contenido
          h5 Tabla 4.
          span Ejemplo indicadores de flujo
    .row.justify-content-center(data-aos="fade-down-left")
      .col-lg-10.col-12
        .tabla-a.color-primario.mb-5
          table
            thead.fondo-5
              tr
                <th class="text-center" colspan="4"> 
                  p.text-bold VENTAS
                </th>
            tbody.text-center
              tr.fondo-6.text-bold
                td.bordederecha.bordeabajo Periodos
                td.bordeabajo.bordederecha Proyectadas
                td.bordeabajo.bordederecha Ejecutadas
                td.bordeabajo Indicador
              tr.fondo-11
                td.bordederecha.bordeabajo 20x0
                td.bordederecha.bordeabajo 100
                td.bordederecha.bordeabajo 120
                td.bordeabajo 120%
              tr.fondo-7
                td.bordederecha.bordeabajo 20x1
                td.bordederecha.bordeabajo 120%
                td.bordederecha.bordeabajo 100%
                td.bordeabajo 83%
              tr.fondo-11
                td.bordederecha.bordeabajo 20x2
                td.bordederecha.bordeabajo 150
                td.bordederecha.bordeabajo 150
                td.bordeabajo 100%
              tr.fondo-7
                td.bordederecha 20x3
                td.bordederecha 170
                td.bordederecha 160
                td 94% 
    .row.justify-content-center(data-aos="fade-down-right")
      .col-12.fondo-8.p-3
        .row.justify-content-center.align-items-center
          .col-lg-1.col-2(data-aos="fade-down-right")
            img(src="@/assets/curso/tema1/figura2.svg")
          .col-lg-11.col-10(data-aos="fade-down-left")
            p.text-bold.mb-0 Para tener en cuenta:
            p Para el cálculo de los indicadores, se dividen las ventas ejecutadas sobre las proyectadas; posteriormente, y para presentarlo en forma porcentual, el resultado es multiplicado por 100. Como puede verse, en aquellas ocasiones donde el indicador supera el 100%, se entiende que se debe a que los resultados fueron superiores a los estimados inicialmente.
    .row.my-4.align-items-center(data-aos="fade-down-right")
      .col-xxl-1.col-xl-1.col-lg-1.col-md-1.col-sm-1.col-2
        .row
          .col-xxl-5.col-xl-5.col-lg-6.col-md-8.col-sm-10.col-7
            img(src="@/assets/curso/tema1/fondo2.jpg")
      .col-xxl-6.col-xl-6.col-lg-6.col-md-7.col-sm-10.col-10.ps-0
        h4.mb-0.ms-0.margentitulo2 Acumulados
    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5(data-aos="fade-down-left")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/imagen13.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Las metas estimadas para este tipo de indicadores se 
        span.text-bold.resaltado acumulan durante el tiempo
        span , de tal forma que, entre mayor sea la distancia del horizonte de tiempo, más alto será el valor objetivo. A diferencia del anterior, la gestión de cada año tiene una implicación directa en los posteriores, por lo que tienden a ser especialmente útiles cuando se hacen mediciones mensuales hasta alcanzar el periodo anual.
    p.my-5(data-aos="fade-down-right") Para dar continuidad al ejemplo anterior, puede detallarse aún más el volumen de ventas esperado para cada periodo presentando un indicador de ventas a alcanzar cada trimestre o de forma anual. En la siguiente tabla, se presenta la situación descrita:
    .row.justify-content-center.mt-5
      .col-lg-10.col-md-12(data-aos="fade-down-right")
        .titulo-sexto.color-acento-contenido
          h5 Tabla 5.
          span Ejemplo indicadores de acumulación
    .row.justify-content-center
      .col-lg-10.col-12
        .tabla-a.color-primario.mb-5(data-aos="fade-down-right")
          table
            thead.fondo-5
              tr
                <th class="text-center" colspan="5"> 
                  p.text-bold VENTAS
                </th>
            tbody.text-center
              tr.fondo-6.text-bold.bordeabajo.bordeizq
                td.bordederecha Periodos
                td.bordederecha Mensuales
                td.bordederecha Cuatrimestrales
                td.bordederecha Proyectadas
                td.bordederecha  Indicador
              tr.fondo-11.bordeabajo.bordeizq
                td.bordederecha Enero
                td.bordederecha 5
                <td class="bordederecha" rowspan="4">31</td>
                <td class="bordederecha" rowspan="4">5</td>
                <td class="bordederecha" rowspan="4">48%</td>
              tr.fondo-7.bordeabajo.bordeizq
                td.bordederecha Febrero
                td.bordederecha 10
              tr.fondo-11.bordeabajo.bordeizq
                td.bordederecha Marzo
                td.bordederecha 7
              tr.fondo-7.bordeabajo.bordeizq
                td.bordederecha Abril
                td.bordederecha 9
              tr.fondo-11.bordeabajo.bordeizq
                td.bordederecha Mayo
                td.bordederecha 11
                <td class="bordederecha" rowspan="4">44</td>
                <td class="bordederecha" rowspan="4">80</td>
                <td class="bordederecha" rowspan="4">55%</td>
              tr.fondo-7.bordeabajo.bordeizq
                td.bordederecha Junio
                td.bordederecha 12
              tr.fondo-11.bordeabajo.bordeizq
                td.bordederecha Julio
                td.bordederecha 11
              tr.fondo-7.bordeabajo.bordeizq
                td.bordederecha Agosto
                td.bordederecha 10
              tr.fondo-11.bordeabajo.bordeizq
                td.bordederecha Septiembre
                td.bordederecha 4
                <td class="bordederecha" rowspan="4">31</td>
                <td class="bordederecha" rowspan="4">55</td>
                <td class="bordederecha" rowspan="4">56%</td>
              tr.fondo-7.bordeabajo.bordeizq
                td.bordederecha Octubre
                td.bordederecha 8
              tr.fondo-11.bordeabajo.bordeizq
                td.bordederecha Noviembre
                td.bordederecha 9
              tr.fondo-7.bordeabajo.bordeizq
                td.bordederecha Diciembre
                td.bordederecha 10
              tr.fondo-11.bordeabajo.bordeizq
                td.bordederecha.text-bold Total
                td.bordederecha 
                td.bordederecha.text-bold 106 
                td.bordederecha.text-bold 200
                td.bordederecha.text-bold 53%
    p.my-5(data-aos="fade") En esta situación, se presenta una evaluación para cada cuatrimestre, incluyendo los valores de los meses anteriores, de la misma forma que al final se presenta un indicador que evalúa la gestión anual. Más allá de este efecto de acumulación, la forma de calcular el indicador no difiere de los de acumulación, al igual que la interpretación que de esto se deriva.
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
