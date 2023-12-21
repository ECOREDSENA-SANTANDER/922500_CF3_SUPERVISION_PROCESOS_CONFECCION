<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 1
      h1 Patronaje de prendas de vestir

    .row.mb-5
      .col-lg-8.mb-4.mb-lg-0
        p.mb-4 El término patronaje es empleado dentro de la industria de la moda para referirse a un sistema organizado que posibilita la construcción de prendas de vestir; estas visiones desde diversas metodologías permiten la interpretación de un diseño por partes, para posteriormente ser adaptado a la figura humana y cuya unión de estas partes se visualice en un todo que permita su funcionalidad.
        p.mb-4 A lo largo de la historia, el ser humano se ha vestido para suplir una necesidad básica, la cual reside en poder cubrirse con textiles que permitan su protección, por ejemplo, vestirse para cubrirse del frío y cubrirse para evitar quemaduras del sol por altas temperaturas. Antiguamente, se pueden observar en figuras rupestres, papiros y dibujos, cómo el ser humano, más que una prenda elaborada, usaba amplias telas que permitieran su cubrimiento, como lo eran los persas, griegos, romanos, egipcios entre otros, lo que más predominaba, eran amarrados que pudieran sostenerse en el cuerpo.
        p A medida que las diferentes civilizaciones fueron creciendo, el vestuario empezó a considerarse como un símbolo de distinción entre las diferentes esferas sociales, y los oficios de la producción de prendas empiezan a ser asumidos por personas a las que se les llamaba, modistos y costureros, dado el oficio del cosido de las prendas.
      .col-lg-4.mb-4.mb-lg-0
        .titulo-sexto.color-acento-contenido
          h5 Figura 1. 
          | Vestimenta por cubrimiento con mantas
        img(src='@/assets/curso/tema1/img01.png')
    
    .row.align-items-center.mb-4
      .col-lg-4.mb-4.mb-lg-0
        .row.align-items-center
          .col-10
            img(src='@/assets/curso/tema1/img02.svg')
      .col-lg-8.mb-4.mb-lg-0
        .cajon.color-acento-contenido.p-4
          p.mb-4 Uno de los primeros libros registrados en la historia y dedicados a la recreación de patrones de vestir, fue en 1589 por Juan de Álcega, llamado “Libro de geometría, práctica y patrones”; este fue un paso importante para poder empezar a comprender la construcción de prendas desde un método más industrial, pues antes los patrones se lograban ubicando la tela sobre los cuerpos, o con técnicas que solían ser muy reservadas para evitar la copia. Otro método de reproducción de prendas, y que permitía la tendencia y la moda por parte de otros grupos de personas, era descoser prendas ya hechas para tomar dichos patrones y hacerlos nuevamente (reutilizar piezas y agregar otras) en otro textil.
          p Para el siglo XVIII, el patronaje de prendas empieza a ser mucho más visible, obras como la Enciclopedia del corte y la confección en 1769 por M. Garsault, generó que muchos otros se dedicaran a la publicación y venta de patrones.  En 1976 en Londres, empieza a reproducirse The Taylor´s Complete Guide, guía de confección y corte de vestidos que fue muy popular en la época; para 1822,  por los mismos autores,  publican una guía para modistas llamada The Taylor´s Friendly instructor. Ya para el siglo XIX, la publicación de patrones empieza a hacerse más masiva a través de revistas de moda o figurines, como se llamaba para aquella época, un ejemplo de ello fue la Revista Vogue, Patrones Weldon y el famoso Pattern Book, entre otros.

    p Actualmente, los métodos industriales de patronaje permitieron establecer tablas de medidas universales, a partir de estudios antropométricos, dependiendo su ubicación geográfica; esto favoreció el establecer métodos de patronaje industriales universales y dadas las actualizaciones en tecnología, este oficio pasó de ser manual a digital, permitiendo la agilización de procesos de producción en la confección de prendas de vestir, en las líneas infantil, femenino y masculino, de manera masiva.
  
</template>

<script>
export default {
  name: 'Tema1',
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
