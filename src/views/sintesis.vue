<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p.my-5 Las empresas hoy por hoy deben estar tan estructuradas para su correcto funcionamiento en un mundo globalizado que realmente requieren cumplir con dos factores claves en su gestión, estos elementos son: el análisis de datos y la elaboración de informes que, al ser presentados a las personas que jerárquicamente estén en capacidad de tomar decisiones que impacten la empresa a futuro, les permitan tomar decisiones que la hagan más competitiva.
    .row.justify-content-center
      .col-lg-10.mb-5
        figure
          img(src="@/assets/curso/sintesis/sintesis.svg", alt="Síntesis")
      .col-auto
        a.anexo.mb-4(:href="obtenerLink('/downloads/sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
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
