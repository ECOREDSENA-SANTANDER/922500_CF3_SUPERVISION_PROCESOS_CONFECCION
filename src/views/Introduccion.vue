<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    figure.mb-5(data-aos="zoom-in-down")
      img(src='@/assets/curso/introduccion/img01.png' alt="Imagen decorativa")
    
    p.mb-4(data-aos="fade-right") Dentro de los procesos que se llevan a cabo en la industria de la producción de prendas, la confección es uno de los principales oficios que materializa los productos o prendas de vestir, pero este paso es posible gracias a una planeación de producción en planta que ha sido estudiada con antelación.  En esta planeación, el patronaje de las prendas de vestir es uno de los procesos más importantes, pues permite guiar dicha materialización debido a que comprende las medidas exactas de los moldes que han sido desarrollados a través de diversos métodos; emplear cuadros de tallas y deducción de tallas, que surgen del análisis de la figura humana y de estudios antropométricos, permite apuntar a públicos objetivos determinados.

    p.mb-4(data-aos="fade-left") Es por lo anterior, que se hace necesario abordar el patronaje industrial dentro de las líneas femenino y masculino, así como el escalado que se logra a través del mismo análisis en los cuadros de tallas, permitiendo agilizar el proceso de producción. Este abordaje permite comprender la estructura corporal como punto de partida para la construcción de cuadros de tallas, el patronaje, y su interpretación, posibilitando tener una visión integral en los procesos de confección en planta.

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped>
.introduccion
</style>
