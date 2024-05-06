<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 1
      h1 Patronaje de prendas de vestir

    
    .row 
      .col-sm-12.col-lg-8
        .row 
          .col-sm-12.col-lg-12.mb-4
            p El término patronaje es empleado dentro de la industria de la moda para referirse a un sistema organizado que posibilita la construcción de prendas de vestir; estas visiones desde diversas metodologías permiten la interpretación de un diseño por partes, para posteriormente ser adaptado a la figura humana y cuya unión de estas partes se visualice en un todo que permita su funcionalidad.
          .col-sm-12.col-lg-12
            .cajon.color-acento-contenido.p-4.mb-5
              p A lo largo de la historia, el ser humano se ha vestido para suplir una necesidad básica, la cual reside en poder cubrirse con textiles que permitan su protección, por ejemplo, vestirse para cubrirse del frío y cubrirse para evitar quemaduras del sol por altas temperaturas. Antiguamente, se pueden observar en figuras rupestres, papiros y dibujos, cómo el ser humano, más que una prenda elaborada, usaba amplias telas que permitieran su cubrimiento, como lo eran los persas, griegos, romanos, egipcios entre otros, lo que más predominaba, eran amarrados que pudieran sostenerse en el cuerpo.
          
      .col-sm-12.col-lg-4
        .titulo-sexto.color-acento-contenido
          h5 Figura 1. 
          | Matriz DOFA
        img(src='@/assets/curso/tema1/img01.png' alt="Se describe paso a paso la forma como se colocaba sobre el cuerpo la túnica o manta que era utilizada como prenda de vestir en sus inicios ")
    p.mb-5 A medida que las diferentes civilizaciones fueron creciendo, el vestuario empezó a considerarse como un símbolo de distinción entre las diferentes esferas sociales, y los oficios de la producción de prendas empiezan a ser asumidos por personas a las que se les llamaba, modistos y costureros, dado el oficio del cosido de las prendas.
    
    
    .row.fondoo.align-items-center.py-4.py-md-5
      .col-sm-12.col-lg-12.px-lg-5.px-4
        
        .bg1.p-5.mb-5  
          LineaTiempoC
            .row.justify-content-center.align-items-top(titulo="Año 1589")
              .col-sm-12.col-lg-6
                h4.text-cus.mb-4.my-0 #[b Año 1589]
                p Juan de Álcega publica “Libro de geometría, práctica y patrones”, uno de los primeros libros registrados dedicados a la recreación de patrones de vestir. Este fue un paso importante para poder empezar a comprender la construcción de prendas desde un método más industrial. Otro método de reproducción de prendas y que permitía la tendencia y la moda por parte de otros grupos de personas, era descoser prendas ya hechas para tomar dichos patrones y hacerlos nuevamente (reutilizar piezas y agregar otras) en otro textil.
              .col-sm-12.col-lg-4
                figure
                  img.img-a.img-t.my-2(src='@/assets/curso/tema1/1.svg', alt='tema1')      
              
            .row.justify-content-center.align-items-top(titulo="Siglo XVIII - 1769")
              .col-sm-12.col-lg-6
                h4.text-cus.mb-4.my-0 #[b Siglo XVIII - 1769]
                p El patronaje de prendas comienza a ser más visible.  En 1769, M. Garsault publica la "Enciclopedia del corte y la confección", generando interés en la publicación y venta de patrones.
              .col-sm-12.col-lg-4
                figure
                  img.img-a.img-t.my-2(src='@/assets/curso/tema1/2.svg', alt='tema1')      
              
            .row.justify-content-center.align-items-top(titulo="1976")
              .col-sm-12.col-lg-6
                h4.text-cus.mb-4.my-0 #[b 1976]
                p En Londres, se inicia la reproducción de "The Taylor´s Complete Guide", una guía de confección y corte de vestidos que se vuelve popular en esa epoca.
              .col-sm-12.col-lg-4
                figure
                  img.img-a.img-t.my-2(src='@/assets/curso/tema1/3.svg', alt='tema1')      
              
            .row.justify-content-center.align-items-top(titulo="1822")
              .col-sm-12.col-lg-6
                h4.text-cus.mb-4.my-0 #[b 1822]
                p Los mismos autores de “The Taylor´s Complete Guide” publican “The Taylor´s Friendly Instructor”, una guía para modistas.
              .col-sm-12.col-lg-4
                figure
                  img.img-a.img-t.my-2(src='@/assets/curso/tema1/4.svg', alt='tema1')      
              
            .row.justify-content-center.align-items-top(titulo="Siglo XIX")
              .col-sm-12.col-lg-6
                h4.text-cus.mb-4.my-0 #[b Siglo XIX]
                p La publicación de patrones se vuelve más masiva a través de revistas de moda o figurines, como se llamaba para aquella época. Se destacan la Revista Vogue, Patrones Weldon y el famoso Pattern Book, entre otros.
              .col-sm-12.col-lg-4
                figure
                  img.img-a.img-t.my-2(src='@/assets/curso/tema1/5.svg', alt='tema1')      
              
    
    
        .row.justify-content-center
          .col-sm-12.col-lg-10
            .cajoni.p-4.mb-5
              p(data-aos="fade-right") Actualmente, los métodos industriales de patronaje permitieron establecer tablas de medidas universales, a partir de estudios antropométricos, dependiendo su ubicación geográfica; esto favoreció el establecer métodos de patronaje industriales universales y dadas las actualizaciones en tecnología, este oficio pasó de ser manual a digital, permitiendo la agilización de procesos de producción en la confección de prendas de vestir, en las líneas infantil, femenino y masculino, de manera masiva.
  
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
