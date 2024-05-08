<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero
        span 7
      h1  Escalado manual de prendas
    
    .row.justify-content-center.mb-4
      .col-lg-5.col-md-10.col-10(data-aos="fade-left")
        img.mb-4(src='@/assets/curso/tema7/img01.png' , alt="tema 7")
      
      .col-lg-7.mb-4.mb-md-0(data-aos="fade-right")
        p.mb-4 Cuando se inicia con el proceso de escalado, se debe tener en cuenta referencias como cuadros de tallas, metodología y lógica de construcción, pieza o molde que se va escalar, es decir, en este caso se hace referencia a una base inferior de falda, quiere decir un molde que no tiene margen de costura, ni es una prenda, se trabajará el escalado de una base en las diferentes tallas, de igual manera se debe tener en cuenta el tipo de escalado que se va a trabajar, los aumentos y disminuciones por talla.
        p.mb-3 Para realizar este proceso de manera efectiva, es necesario:
        
        ul.lista-ul--color
          li.d-flex
            i.fas.fa-car-side 
            | Realizar un análisis de las diferencias por talla e identificar la medida que se aplicará en el escalado.
          li.d-flex
            i.fas.fa-car-side
            | Analizar los puntos de escalado que se van a referenciar o modificar.
          li.d-flex
            i.fas.fa-car-side
            | Examinar detalladamente el cuadro de tallas para asegurar una correspondencia adecuada entre las medidas y las tallas escaladas.
            
    
    .row.font.align-items-center.py-4.py-md-5.mb-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.justify-content-center.mb-4(data-aos="fade-down")
    
        .row.justify-content-center.mb-4
          .col-lg-10.mb-4.mb-md-0
            .cajon.color-acento-contenido.p-4.mb-2
              p.my-2 A continuación, se presenta el escalado de las diferentes piezas presentadas en este componente formativo:
          
        .row.d-flex.justify-content-center.align-items-center.mb-5
          .col-lg-12.md-lg-10.col.lg-12
            .row.d-flex.justify-content-center.align-items-center
              .col-lg-6.col-md-10.col-12.mt-2
                .tarje.color-primario.my-4.he-4-cus.px-4.my-4.pt-4
    
                  .row.justify-content-center.align-items-center(data-aos="zoom-in-left")
                    .col-lg-12
                      .fondo21.p-3.mb-2
                        .row.justify-content-around.align-items-center
                          .col-3.col-sm-2.col-lg-2
                            img(src="@/assets/curso/tema7/pdf.svg", alt="tema 7")
                          .col
                            .row.justify-content-between.align-items-center
                              .col.mb-4.mb-sm-0          
                                p.my-2 Anexo. Escalado de falda_femenino
                              .col-sm-auto
                                a.boton.color-acento-botones(:href="obtenerLink('/downloads/Anexo_8_ESCALADO_DE_FALDA_FEMENINO.pdf')" target="_blank")
                                  span Descargar
                                  i.fas.fa-file-download 
                
                  .row.justify-content-center.align-items-center(data-aos="zoom-in-left")
                    .col-sm-12.col-lg-12
                      .fondo21.p-3.mb-2
                        .row.justify-content-center.align-items-center
                          .col-3.col-sm-2.col-lg-2
                            img(src="@/assets/curso/tema7/pdf.svg", alt="tema 7")
                          .col
                            .row.justify-content-center.align-items-center
                              .col.mb-4.mb-sm-0        
                                p.my-2 Anexo. Escalado de base con pinzas_superior
                              .col-sm-auto
                                a.boton.color-acento-botones(:href="obtenerLink('/downloads/Anexo_9_ESCALADO_DE_BASE_CON PINZAS_SUPERIOR.pdf')" target="_blank")
                                  span Descargar
                                  i.fas.fa-file-download
                  .row.justify-content-center.align-items-center(data-aos="zoom-in-left")
                    .col-lg-12
                      .fondo21.p-3.mb-2
                        .row.justify-content-around.align-items-center
                          .col-3.col-sm-2.col-lg-2
                            img(src="@/assets/curso/tema7/pdf.svg", alt="tema 7")
                          .col
                            .row.justify-content-between.align-items-center
                              .col.mb-3.mb-sm-0          
                                p.my-2 Anexo. Escalado de básico de pantalón
                              .col-sm-auto
                                a.boton.color-acento-botones.justify-content-center(:href="obtenerLink('/downloads/Anexo_10_ESCALADO_DE BASICO_DE_PANTALON.pdf')" target="_blank")
                                  span Descargar
                                  i.fas.fa-file-download 
                  .row.justify-content-center.align-items-center(data-aos="zoom-in-left")
                    .col-lg-12
                      .fondo21.p-3.mb-2
                        .row.justify-content-around.align-items-center
                          .col-3.col-sm-2.col-lg-2
                            img(src="@/assets/curso/tema7/pdf.svg", alt="tema 7")
                          .col
                            .row.justify-content-between.align-items-center
                              .col.mb-3.mb-sm-0          
                                p.my-2 Anexo. Escalado Cortes, manga, cuello
                              .col-sm-auto
                                a.boton.color-acento-botones(:href="obtenerLink('/downloads/Anexo_11_ESCALADO_CORTES_MANGA_CUELLO.pdf')" target="_blank")
                                  span Descargar
                                  i.fas.fa-file-download
                  .row.justify-content-center.align-items-center(data-aos="zoom-in-left")
                    .col-lg-12.mb-4
                      .fondo21.p-3.mb-2
                        .row.justify-content-around.align-items-center
                          .col-3.col-sm-2.col-lg-2
                            img(src="@/assets/curso/tema7/pdf.svg", alt="tema 7")
                          .col
                            .row.justify-content-between.align-items-center
                              .col.mb-3.mb-sm-0          
                                p.my-2 Anexo. Escalado Bibásico Análisis: Base superior masculina
                              .col-sm-auto
                                a.boton.color-acento-botones(:href="obtenerLink('/downloads/Anexo_12_ESCALADO_BIBASICO-ANALISIS_BASE_SUPERIOR_MASCULINA.pdf')" target="_blank")
                                  span Descargar
                                  i.fas.fa-file-download 
        
              .col-lg-6.col-md-10.col-12.mt-2
                .tarje.color-primario.my-4.he-4-cus.px-4.my-4.pt-4
                    
                  .row.justify-content-center.align-items-center(data-aos="zoom-in-left")
                    .col-lg-12
                      .fondo21.p-3.mb-2
                        .row.justify-content-around.align-items-center
                          .col-3.col-sm-2.col-lg-2
                            img(src="@/assets/curso/tema7/video.svg", alt="tema 7")
                          .col
                            .row.justify-content-between.align-items-center
                              .col.mb-3.mb-sm-0          
                                p.my-2 Anexo. Escalado de falda_femenino
                              .col-sm-auto
                                a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=ddrsedOxtKA" target="_blank")
                                  span Ir al sitio
                                  i.fas.fa-video
                
                  .row.justify-content-center.align-items-center(data-aos="zoom-in-left")
                    .col-lg-12
                      .fondo21.p-3.mb-2
                        .row.justify-content-around.align-items-center
                          .col-3.col-sm-2.col-lg-2
                            img(src="@/assets/curso/tema7/video.svg", alt="tema 7")
                          .col
                            .row.justify-content-between.align-items-center
                              .col.mb-3.mb-sm-0          
                                p.my-2 Video. Escalado de base con pinzas_superior
                              .col-sm-auto
                                a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=ui7cNs-qD1k" target="_blank")
                                  span Ir al sitio
                                  i.fas.fa-video
                  
                  .row.justify-content-center.align-items-center(data-aos="zoom-in-left")
                    .col-lg-12
                      .fondo21.p-3.mb-2
                        .row.justify-content-around.align-items-center
                          .col-3.col-sm-2.col-lg-2
                            img(src="@/assets/curso/tema7/video.svg", alt="tema 7")
                          .col
                            .row.justify-content-between.align-items-center
                              .col.mb-3.mb-sm-0          
                                p.my-2 Video. Escalado de básico de pantalón
                              .col-sm-auto
                                a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=GS5jZ-Tw9vc" target="_blank")
                                  span Ir al sitio
                                  i.fas.fa-video
                  
                  .row.justify-content-center.align-items-center(data-aos="zoom-in-left")
                    .col-lg-12
                      .fondo21.p-3.mb-2
                        .row.justify-content-around.align-items-center
                          .col-3.col-sm-2.col-lg-2
                            img(src="@/assets/curso/tema7/video.svg", alt="tema 7")
                          .col
                            .row.justify-content-between.align-items-center
                              .col.mb-3.mb-sm-0          
                                p.my-2 Video. Escalado Cortes, manga, cuello
                              .col-sm-auto
                                a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=ENCEKC4EwKU" target="_blank")
                                  span Ir al sitio
                                  i.fas.fa-video
                  
                  .row.justify-content-center.align-items-center(data-aos="zoom-in-left")
                    .col-lg-12.mb-4
                      .fondo21.p-3.mb-2
                        .row.justify-content-around.align-items-center
                          .col-3.col-sm-2.col-lg-2
                            img(src="@/assets/curso/tema7/video.svg", alt="tema 7")
                          .col
                            .row.justify-content-between.align-items-center
                              .col.mb-3.mb-sm-0          
                                p.my-2 Video. Escalado Bibásico Análisis: Base superior masculina
                              .col-sm-auto
                                a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=mN8946qBeGU&t=1177s" target="_blank")
                                  span Ir al sitio
                                  i.fas.fa-video




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
