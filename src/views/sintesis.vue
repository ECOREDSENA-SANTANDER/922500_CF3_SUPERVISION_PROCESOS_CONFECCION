<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p.mb-5(data-aos="zoom-in-down") Para llevar a cabo la producción de prendas, en la industria, se utiliza el patronaje como un sistema organizado para dicha producción, a partir del escalado, que permite la adecuación de las prendas de vestir partiendo de una base.  El patronaje puede ser base para la confección de prendas de vestir femeninas o masculinas. Los patrones pueden ser industrializados para la producción en masa de prendas, o a la medida para lograr exclusividad para los clientes.  A continuación, se presenta un mapa conceptual que resume de manera visual estos aspectos:

    .row.justify-content-center(data-aos="zoom-in-up")
      .col-lg-10.mb-5
        figure
          img(src="@/assets/curso/sintesis.png", alt="La síntesis describe dos aspectos principales: la capacitación del personal y el perfil técnico. En cuanto a la capacitación, se mencionan diferentes procesos, como la estructura del modelo de capacitación, que incluye diagnóstico, planes y programas de capacitación, desarrollo y evaluación. También se hace referencia a la inducción y reinducción, así como a una inducción específica para el cargo. Por otro lado, para el proceso de capacitación de los administrativos, se utiliza una planeación estratégica que aborda el proceso organizacional y las estructuras organizacionales. Además, se mencionan las competencias laborales, como las corporativas, funcionales y de gestión. También se mencionan las competencias funcionales organizacionales, como el man")
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
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
