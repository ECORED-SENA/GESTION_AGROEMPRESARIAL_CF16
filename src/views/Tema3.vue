<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="fade-down-left")
      .titulo-principal__numero
        span 3
      h1 Informes
    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema3/imagen1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 De entre todos los tipos de documentación que tienen cabida en el desarrollo de la operación de las empresas, los informes tienen especial importancia, pues suelen 
          span.text-bold.resaltado recopilar toda la información relevante 
          span respecto a cualquier elemento que amerite la socialización de los 
          span.text-bold.resaltado resultados y la evaluación de la efectividad de las medidas implementadas.
    .row.justify-content-center.mt-5
      .col-lg-6.col-md-12.mb-4(data-aos="fade-down-right")
        img(src="@/assets/curso/tema3/imagen2.jpg")
      .col-lg-6.col-md-12(data-aos="fade-down-left")
        p Los informes son documentos formales elaborados con el objetivo de ser suministrados a las personas involucradas en la operación. Resulta común que se haga uso de 
          span.text-bold.resaltado lenguaje técnico 
          span y cumpla con una 
          span.text-bold.resaltado estructura estandarizada 
          span que permita acceder a la información siguiendo un orden lógico.
        p En el contenido del informe, es habitual encontrarse con:
        ul.lista-ul
          li.mb-0 
            i.fas.fa-angle-right
            | Una recopilación de las actividades desarrolladas.
          li.mb-0
            i.fas.fa-angle-right
            | La justificación de su elección.
          li.mb-0 
            i.fas.fa-angle-right
            | Las estimaciones iniciales.
          li.mb-0 
            i.fas.fa-angle-right
            | Los resultados alcanzados.
        p Gracias a su forma pragmática de comunicar la información, funciona como una herramienta efectiva para divulgar y facilitar la toma de decisiones.
    separador
    #t_3_1.titulo-segundo.color-acento-contenido(data-aos="fade-down-right")
      h2 3.1 Tipos
    p.my-5(data-aos="fade-down-right") Los informes pueden ser clasificados de diferentes formas, según el criterio que se evalúe. A continuación, se presentan dos de los más utilizados:
    .row.justify-content-center
      .col-lg-6.col-md-12.mb-4(data-aos="fade-down-right")
        LineaTiempoD.cambiocolor
          p(numero="1" titulo="Ejecutivo") Es un informe con una extensión máxima de 10 páginas, se presenta como un documento que resume un trabajo mucho más extenso, por lo que la información suele ser concreta y directa a lo verdaderamente relevante.
          
          p(numero="2" titulo="Largo") Cuenta con 10 o más páginas de contenido, lo que le otorga el espacio necesario al autor para extenderse cuanto crea necesario en el desarrollo de sus observaciones. Es el informe más apropiado cuando se abordan temáticas complejas o enrevesadas, puesto que brinda la oportunidad de extenderse o justificar cada decisión de forma más detallada. Por otra parte, los informes pueden clasificarse de acuerdo con la naturaleza de su contenido, así, es posible clasificarlo en las siguientes categorías:
          
          p(numero="3" titulo="Divulgativo") Su propósito es llegar a la mayor cantidad de gente, sin hacer ningún tipo de clasificación o segmentación previa. Debido a esto, resulta conveniente que haga uso de un lenguaje accesible a mayorías, de tal forma que su lectura no resulte demasiado compleja para los usuarios de esta información.
          
          p(numero="4" titulo="Científico") Es un informe técnico y, por lo tanto, hace uso de términos mucho más complejos y propios de profesiones asociadas con la investigación. Suele usarse en ámbitos académicos y en etapas de investigación y desarrollo.

          p(numero="5" titulo="Técnico") Su principal característica resulta ser el enfoque específico a una temática concreta. Es uno de los más útiles en el campo empresarial, puesto que facilita la segmentación en función de las áreas organizacionales involucradas.

          p(numero="6" titulo="Mixto") Resulta un punto intermedio entre el informe divulgativo y el técnico, lo que significa que puede requerir lenguaje técnico en menor medida y apuntar a un amplio grupo de interesados, abordando problemáticas específicas, pero sin profundizar en la disciplina de donde proviene.

      .col-lg-6.col-md-12(data-aos="fade-down-left")
        img(src="@/assets/curso/tema3/imagen3.jpg")    
    separador
    #t_3_2.titulo-segundo.color-acento-contenido(data-aos="fade-down-right")
      h2 3.2 Estructura
    p(data-aos="fade-down-left") Si bien existen diversos tipos de informes, que abordan todo tipo de temáticas, desde diferentes perspectivas, la estructura de estos suele 
      span.text-bold.resaltado seguir un patrón
      span , lo que permite presentar un esquema general que cumple con las condiciones o requerimientos mínimos propios de este tipo de documentación.
    p.mb-5(data-aos="fade-down-right") Los tres grandes elementos que hacen parte de la estructura de un informe son: la introducción, su desarrollo y las conclusiones, los cuales se describen a continuación:
    AcordionA(data-aos="fade-down-left").mb-5(tipo="a" clase-tarjeta="tarjeta fondo-12")
      .row.ps-5(titulo="Introducción")
        .col-lg-5.col-md-12.mb-4.mb-md-0.ps-4
          p Aborda los aspectos que dieron origen al trabajo o la estrategia a desarrollar, por ejemplo:
          ul.lista-ul
            li.mb-0 
              i.fas.fa-angle-right
              | La evaluación de un proceso operativo. 
            li.mb-0 
              i.fas.fa-angle-right
              | La indagación sobre situaciones que pueden involucrar fraude.
            li.mb-0 
              i.fas.fa-angle-right
              | La simple intención de la administración por mejorar los indicadores de la compañía.
          p.my-5 Describe la situación inicial, así como los objetivos que se esperaban lograr en el desarrollo del trabajo.
        .col-lg-7.col-md-12
          figure
            img(src='@/assets/curso/tema3/imagen4.jpg')
      .row.ps-5(titulo="Desarrollo")
        .col-lg-5.col-md-12.mb-4.mb-md-0.ps-4
          p Recopila todas las acciones implementadas, la forma en la que se llevó a cabo la ejecución y los pormenores del proceso.
          p En esta parte, se relacionan cada una de las fases implementadas, así como los hallazgos que se identificaron durante la implementación.
        .col-lg-7.col-md-12
          figure
            img(src='@/assets/curso/tema3/imagen5.jpg')
      .row.ps-5(titulo="Conclusiones")
        .col-lg-5.col-md-12.mb-4.mb-md-0.ps-4
          p Presentan los resultados contrastados con la situación inicial o con las expectativas a alcanzar.
          p Se debe incluir un juicio de valor en el que se determine si el trabajo fue fructífero y si los beneficios obtenidos resultan mayores que la inversión necesaria para llevar a cabo la implementación de las estrategias.
        .col-lg-7.col-md-12
          figure
            img(src='@/assets/curso/tema3/imagen6.jpg')
    .row.justify-content-center.mt-5
      .col-lg-6.col-md-12.mb-4(data-aos="fade-down-right")
        img(src="@/assets/curso/tema3/imagen7.jpg")
      .col-lg-6.col-md-12(data-aos="fade-down-left")
        p De forma complementaria, se pueden agregar otras secciones que aporten robustez al informe. Estos elementos no son aplicables a todos los informes, por lo que su uso dependerá de las condiciones en las que se realizó el trabajo y el tipo de destinatarios al que se espera alcanzar con él. 
        p Algunas secciones adicionales pueden ser:
        ul.lista-ul
          li.mb-0 
            i.fas.fa-angle-right
            | La portada, que agrega información relevante respecto a la fecha, autores y temática a desarrollar.
          li.mb-0 
            i.fas.fa-angle-right
            | La bibliografía, que referencia las fuentes consultadas, en caso de que el trabajo involucre un aspecto investigativo. 
          li.mb-0 
            i.fas.fa-angle-right
            | Los anexos, que complementan el informe con papeles de trabajo, evidencias o cualquier otra documentación adicional que aporta información útil.
    separador
    #t_3_3.titulo-segundo.color-acento-contenido(data-aos="fade-down-right")
      h2 3.3 Socialización
    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5(data-aos="fade-down-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema3/imagen8.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 La socialización 
          span.text-bold.resaltado consiste en la facilitación del informe a quienes está destinado
          span , es decir, la entrega de la información de tal forma que alcance su cometido, la transmisión de un ejercicio y sus resultados. Dependiendo de la naturaleza de este, el informe puede ser socializado en distintas esferas y bajo diversas metodologías; por ejemplo, si los resultados están destinados a personal directivo, una junta o asamblea puede ser el evento en el cual tenga cabida la presentación, justificación y explicación de los resultados.
    p.mt-5(data-aos="fade-down-left") Usualmente, los informes tienen injerencia directa sobre la toma de decisiones, por lo que suelen estar dirigidos a personal de los niveles tácticos y estratégicos de las compañías. En la actualidad, se puede buscar un apoyo en los medios electrónicos para difundir la información de forma más ágil y efectiva; así, es cada vez más habitual encontrarse que la entrega de la documentación se hace en tiempo real a través de correos electrónicos, respetando la estructura y el contenido, ya que estos sistemas garantizan conservar la integralidad de la información. 
    .row.justify-content-center.mb-5
      .col-lg-6.col-md-12(data-aos="fade-down-right")
        p Si los resultados deben ser compartidos con un amplio grupo de terceros, como es el caso de los estados financieros de una compañía, estos deben ser reportados, en caso de ser obligatorios, a las entidades de supervisión designadas para tal fin, como las cámaras de comercio o las superintendencias. En estos casos, se deben revisar las exigencias plasmadas en las 
          span.text-bold.resaltado normas aplicables
          span , para que la información cumpla con todos los requerimientos del caso.
        p Las entidades públicas, por su parte, suelen divulgar la información a través de sus páginas web oficiales, de la misma forma en la que convocan a reuniones públicas para rendiciones de cuentas periódicas, con las que se busca dotar de transparencia la ejecución de las políticas implementadas durante ese tiempo. De esta forma, se incentiva al debate y se ponen en tela de juicio las decisiones tomadas.
      .col-lg-6.col-md-12(data-aos="fade-down-left")
        img(src="@/assets/curso/tema3/imagen7.jpg")
    p(data-aos="fade") En conclusión, los informes comprenden datos relevantes para la toma de decisiones, y por lo tanto, deben propender a que lleguen a los usuarios para los cuales fueron elaborados. Al fin y al cabo, tal y como su nombre lo indica, 
      span.text-bold.resaltado su propósito es aportar información a quienes la exigen, para que, a partir de ella, se alcancen nuevos conocimientos y se fortalezca el criterio de quienes deben decidir respecto a cualquier alternativa de ejecución de medidas o estrategias.
</template>

<script>
export default {
  name: 'Tema3',
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
