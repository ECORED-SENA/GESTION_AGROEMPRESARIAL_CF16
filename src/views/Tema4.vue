<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="fade-down-right")
      .titulo-principal__numero
        span 4
      h1 Plan de mejora
    .row.justify-content-center.mb-5
      .col-lg-6.col-md-12(data-aos="fade-down-right")
        p El ciclo administrativo se compone de los siguientes elementos:
        ul.lista-ul
          li.mb-0 
            i.fas.fa-angle-right
            | Un diagnóstico,
          li.mb-0 
            i.fas.fa-angle-right
            | Una planificación, 
          li.mb-0 
            i.fas.fa-angle-right
            | Una ejecución y 
          li.mb-0 
            i.fas.fa-angle-right
            | Una evaluación.
        p De las conclusiones obtenidas, se deben aplicar medidas de mejora que se consideren apropiadas, de tal forma que se pueda iniciar nuevamente el ciclo. Esta filosofía abre las puertas a una constante 
          span.text-bold.resaltado evolución 
          span que debe redundar en un establecimiento más robusto y con más herramientas para 
          span.text-bold.resaltado mantenerse en un mercado competitivo.
        p Una vez se establecen procedimientos de monitoreo y supervisión para evaluar la gestión de cada área organizacional, es posible medir el rendimiento del personal involucrado y la efectividad de las medidas implantadas.        
      .col-lg-6.col-md-12(data-aos="fade-down-right")
        img(src="@/assets/curso/tema4/imagen1.jpg")
    p.my-5(data-aos="fade-down-left") En ciertos casos, pueden 
      span.text-bold.resaltado identificarse falencias o errores
      span , que deben ser corregidos rápidamente para minimizar su impacto frente a la sociedad, o bien se pueden identificar 
      span.text-bold.resaltado ineficiencias o procesos susceptibles de perfeccionarse.
    .cajon.color-acento-contenido.p-4.my-5.fondo-8(data-aos="fade-down-right")
      p.mb-0 Cualquiera que sea la situación, siempre habrá un margen de mejora con el que la empresa podrá incrementar su rentabilidad o mitigar las probabilidades de ocurrencia de eventos desfavorables. 
        span.text-bold.resaltado Los planes de mejora compilan todas las acciones correctivas o de mejora que la administración aplicará para pulir los procesos de cada área.
    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema4/imagen2.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Es de resaltar que todas las dependencias de la empresa pueden aplicar planes de mejora, puesto que toda actividad que involucre el factor humano siempre será susceptible de ser mejorada. El diseño y aplicación de estos planes recae sobre jefes de área y personal directivo, comúnmente formulados por el jefe directo y la gerencia, y en adición, son supervisados por personal táctico en tiempo real. 
        p Sin embargo, usualmente su 
          span.text-bold.resaltado ejecución recae sobre todos los niveles
          span , así que desde el personal operativo hasta el directivo suele contar con tareas específicas centradas en la implementación de estos planes.
    separador
    #t_4_1.titulo-segundo.color-acento-contenido(data-aos="fade-down-right")
      h2 4.1 Hallazgos
    p.mb-5(data-aos="fade-down-right") Los hallazgos 
      span.text-bold.resaltado consisten en aquellos hechos que son identificados durante la evaluación y que son los causantes de las problemáticas o ineficiencias del proceso evaluado
      span . Estos surgen como producto del monitoreo efectuado y pueden clasificarse de la siguiente forma:
    figure(data-aos="fade")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/Q2aPOMhUiZw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    .row.justify-content-center.px-5.ampliar.fondo-13
      .col-lg-8.col-md-12.mt-5
        .row.justify-content-center
          .col-lg-6.col-md-12.mb-4(data-aos="fade-down-right")
            p Los tipos de hallazgos mencionados son elementos detonadores en la supervisión de cualquier procedimiento, con ellos se inicia el proceso de mejora centrado en:
            ul.lista-ul
              li.mb-0 
                i.fas.fa-angle-right
                | La prevención de las no conformidades potenciales,
              li.mb-0 
                i.fas.fa-angle-right
                | La corrección de las presentes y 
              li.mb-0 
                i.fas.fa-angle-right
                | El aprovechamiento de los planes de mejora para maximizar el valor de la empresa.
          .col-lg-6.col-md-12(data-aos="fade-down-left")
            img(src="@/assets/curso/tema4/figura1.svg")
    separador
    #t_4_2.titulo-segundo.color-acento-contenido(data-aos="fade-down-right")
      h2 4.2 Pasos para su implementación
    p.mb-5(data-aos="fade-down-right") El proceso de implementación de mejora puede diferir entre empresas en cuanto a nivel de detalle, sin embargo, las siguientes son las fases globales que se espera que cualquier programa de esta naturaleza incluya como mínimo:
    .row.justify-content-center.mb-5
      .col-lg-8.col-md-12(data-aos="fade-down-right")
        ImagenInfograficaB.color-acento-botones.mb-5
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/tema4/figura2.svg')

          div(x="9.5%" y="97%" tooltip="Click para leer mas..." numero="+")
            h5 Análisis de las causas
            p La administración debe determinar cuáles son las áreas que requieren la implementación de este tipo de planes, es decir, que tienen mayor campo de acción para implementar mejoras. Según sus capacidades, es posible que sea necesario priorizar unos procesos por encima de otros, en función de un análisis costo–beneficio o del potencial impacto de los riesgos identificados.

          div(x="51.6%" y="68%" tooltip="Click para leer mas..." numero="+")
            .row.justify-content-center
              .col-lg-6.col-md-12
                h5.mb-4.text-dark Propuesta de planificación: 
                p.text-dark Una vez definida el área que se espera abordar, así como la evaluación de su potencial impacto e injerencia sobre la operación, se procede a diseñar una propuesta del plan que sea viable y flexible para la implementación de acciones a futuro. Su elaboración puede contar con herramientas de planificación, como las lluvias de ideas o los diagramas de Gantt.
                p.text-dark Una vez se eligen las estrategias que resulten más efectivas, se designan responsables y tiempos para llevar a cabo el trabajo, a la vez que se determinan los objetivos que se esperan alcanzar. Para documentar lo anterior, se recomienda el diligenciamiento de formatos como el siguiente:
              .col-lg-4.col-md-12
                table.fondo-3
                  tr
                    <th class="anchocol text-center text-dark" colspan="2"> ÁREA DE MEJORA No. 1</th>
                        tr.mb-0
                          td.mb-0.anchocol 
                            p.font-12.mb-0 Descripción del problema.
                          td.mb-0.anchocol
                        tr.mb-0
                          td.mb-0.anchocol 
                            p.font-12.mb-0 Causas que lo provocan.
                          td.mb-0.anchocol 
                        tr.mb-0
                          td.mb-0.anchocol
                            p.font-12.mb-0 Objetivo a conseguir.
                          td.mb-0.anchocol
                        tr.mb-0
                          td.mb-0.anchocol 
                            p.font-12.mb-0 Acciones de mejora.
                          td.mb-0.anchocol 
                            p.mb-0.font-12 1.
                            p.mb-0.font-12 2.
                            p.mb-0.font-12 3.
                        tr.mb-0
                          td.mb-0.anchocol
                            p.font-12.mb-0 Beneficios esperados.
                          td.mb-0.anchocol 

    
          div(x="90.6%" y="32%" tooltip="Click para leer mas..." numero="+")
            h5.mb-4 Implementación y seguimiento:
            p Para esta fase, se inicia la ejecución de las tareas programadas con los responsables asignados. Estas acciones de mejora deben ser flexibles, de tal forma que, si durante el monitoreo se identifican falencias, puedan ser adaptadas para ser más efectivas. En el proceso, se debe efectuar el seguimiento apropiado a los indicadores de cumplimiento y desempeño, de tal manera que se mida la asertividad de las propuestas.
    p.mb-5(data-aos="fade-down-left") Al igual que con cualquier otro programa, los planes de mejora se benefician del monitoreo permanente; así, se pueden realizar las adecuaciones en el menor tiempo posible, alcanzando mejores resultados al final del trabajo.
    .cajon.color-acento-contenido.p-4.mt-5.fondo-8(data-aos="fade-down-right")
      p.mb-0 Una vez se acaba la implementación inicial del plan de mejora, es conveniente evaluar si las estrategias más efectivas pueden ser implementadas de forma permanente, o si, por el contrario, su naturaleza ocasional es la que les permite obtener tales resultados.
      p-mb-5 Para determinar si una medida es apropiada o no, se recomienda hacer uso de indicadores de seguimiento o cumplimiento que permitan llevar a juicios más objetivos; de esta forma, se minimiza la posibilidad de crear un sesgo que lleve a la toma de decisiones equivocadas.
    separador
    #t_4_3.titulo-segundo.color-acento-contenido(data-aos="fade-down-right")
      h2 4.3 Acciones correctivas y de mejora
    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema4/imagen3.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Aunque se ha venido utilizando su término previamente, la profundidad de las acciones correctivas y de mejora va mucho más allá de lo que se intuye de su contexto. 
          span.text-bold.resaltado Son actividades destinadas a la prevención, corrección o mejora de los procesos sobre los cuales se diseña el plan de mejora
          span . A través de su formulación y posterior aplicación, se espera que aspectos concretos de la organización muestren una evolución en cuanto a eficiencia o efectividad.
    p.my-5(data-aos="fade-down-right") El ciclo de las actividades de mejora comprende una serie de pasos que se deben seguir para que cumplan con su objetivo. A continuación, se presentan los más relevantes:
    .row.justify-content-center.mb-5
      .col-lg-6.col-md-12.mb-4(data-aos="fade-down-right")
        LineaTiempoD.color-secundario
          p(numero="1" titulo="Definir la acción") Debe detallarse la acción que se espera aplicar de forma clara y precisa, definiendo responsables y registrándolo en un documento escrito que funcione como control y evidencia para la evaluación posterior.
          
          p(numero="2" titulo="Análisis de causa") Implica describir detalladamente la problemática o ineficiencia que motiva el diseño de acciones de mejora. Entre más se profundice en ellas, mayores precisiones tendrán las posibles acciones de mejora.
          
          p(numero="3" titulo="Planificación de actividades") como cualquier otro plan o programa, resulta necesario diseñar un cronograma que describa las actividades y las fechas en las que se llevarán a cabo, así como las dificultades que surjan durante el proceso.
          
          p(numero="4" titulo="Evaluación de las acciones") En el análisis de causas, se presentan los indicadores actuales del proceso a mejorar; estos deben compararse con los nuevos indicadores una vez aplicadas las acciones de mejora.

      .col-lg-6.col-md-12(data-aos="fade")
        img(src="@/assets/curso/tema2/imagen2.jpg")
</template>

<script>
export default {
  name: 'Tema4',
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
