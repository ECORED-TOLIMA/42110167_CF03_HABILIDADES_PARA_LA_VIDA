<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    p Las competencias socioemocionales fortalecen la capacidad de las personas para comprender las situaciones que viven, relacionarse con los demás, tomar decisiones y participar en la construcción de cambios positivos en sus entornos.
    p A través del reconocimiento de las emociones, las necesidades, las relaciones y los contextos cotidianos, es posible fortalecer capacidades que aporten al bienestar personal, la convivencia, la participación y la construcción de entornos más solidarios e incluyentes.
    p.mb-4 Desde esta perspectiva, la transformación social también se construye desde las acciones cotidianas, la participación y el desarrollo de capacidades que permitan actuar frente a situaciones que afectan el bienestar individual y colectivo.

    .row.justify-content-center
      .col-lg-12.mb-5(data-aos="fade-right")
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="En la síntesis del componente formativo “Las competencias socioemocionales (CSE) y la transformación social”, se explora los contextos ciudadanos, la agencia como herramienta de cambio social, y el marco lógico como metodología para diseñar y evaluar proyectos comunitarios, ilustrado con un ejemplo práctico.")
      .col-auto(data-aos="fade-left")
        a.anexo.mb-4(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
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
