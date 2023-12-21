<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 7
      h1  Escalado manual de prendas
    
    .row.align-items-center.mb-4
      .col-lg-6.mb-4.mb-md-0
        p.mb-4 Cuando se va a iniciar con el proceso de escalado, se debe tener en cuenta referencias como cuadros de tallas, metodología y lógica de construcción, pieza o molde que se va escalar, es decir, en este caso se hace referencia a una base inferior de falda, quiere decir un molde que no tiene margen de costura, ni es una prenda, se trabajará el escalado de una base en las diferentes tallas, de igual manera se debe tener en cuenta el tipo de escalado que se va a trabajar, los aumentos y disminuciones por talla.
        ul.lista-ul--color
          li 
            i.fas.fa-atom 
            | Hacer el análisis de diferencia por talla e identificar la medida a aplicar en el escalado.
          li 
            i.fas.fa-atom 
            | Hacer el análisis de los puntos de escalado que se van a referenciar o modificar.
          li 
            i.fas.fa-atom 
            | Hacer el análisis del cuadro de tallas.
        .cajon.color-primario.p-4.mb-4
          p A continuación, se presenta el escalado de las diferentes piezas presentadas en este componente formativo:
      .col-lg-6.mb-4.mb-md-0
        img(src='@/assets/curso/tema7/img01.png')
    
    .row.justify-content-center.mb-4
      .col-lg-9.mb-4.mb-md-0
        .row.justify-content-between.mb-4
          .col-lg-5.mb-4.mb-md-0
            a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=ddrsedOxtKA" target="_blank")
                .anexo__icono
                  img(src="@/assets/template/icono-link.svg")
                .anexo__texto
                  strong Enlace web. 
                  | Video - Escalado de falda
          .col-lg-5.mb-4.mb-md-0
            a.anexo.mb-4(:href="obtenerLink('/downloads/Anexo_8_ESCALADO_DE_FALDA_FEMENINO.pdf')" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                strong Anexo. 
                | Escalado de falda_femenino
          .col-lg-5.mb-4.mb-md-0
            a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=ui7cNs-qD1k" target="_blank")
                .anexo__icono
                  img(src="@/assets/template/icono-link.svg")
                .anexo__texto
                  strong Enlace web. 
                  | Video - Escalado de base con pinzas
          .col-lg-5.mb-4.mb-md-0
            a.anexo.mb-4(:href="obtenerLink('/downloads/Anexo_9_ESCALADO_DE_BASE_CON PINZAS_SUPERIOR.pdf')" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                strong Anexo. 
                | Escalado de base con pinzas_superior
          .col-lg-5.mb-4.mb-md-0
            a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=GS5jZ-Tw9vc" target="_blank")
                .anexo__icono
                  img(src="@/assets/template/icono-link.svg")
                .anexo__texto
                  strong Enlace web. 
                  | Video - Escalado de básico de pantalón
          .col-lg-5.mb-4.mb-md-0
            a.anexo.mb-4(:href="obtenerLink('/downloads/Anexo_10_ESCALADO_DE BASICO_DE_PANTALON.pdf')" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                strong Anexo. 
                | Escalado de básico de pantalón
          .col-lg-5.mb-4.mb-md-0
            a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=ENCEKC4EwKU" target="_blank")
                .anexo__icono
                  img(src="@/assets/template/icono-link.svg")
                .anexo__texto
                  strong Enlace web. 
                  | Video - Cortes, manga, cuello
          .col-lg-5.mb-4.mb-md-0
            a.anexo.mb-4(:href="obtenerLink('/downloads/Anexo_11_ESCALADO_CORTES_MANGA_CUELLO.pdf')" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                strong Anexo. 
                | Escalado Cortes, manga, cuello
          .col-lg-5.mb-4.mb-md-0
            a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=mN8946qBeGU&t=1177s" target="_blank")
                .anexo__icono
                  img(src="@/assets/template/icono-link.svg")
                .anexo__texto
                  strong Enlace web. 
                  | Video - Base superior masculina
          .col-lg-5.mb-4.mb-md-0
            a.anexo.mb-4(:href="obtenerLink('/downloads/Anexo_12_ESCALADO_BIBASICO-ANALISIS_BASE_SUPERIOR_MASCULINA.pdf')" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                strong Anexo. 
                | Escalado Bibásico Análisis: Base superior masculina

</template>

<script>
export default {
  name: 'Tema7',
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

<style lang="sass" scoped></style>
