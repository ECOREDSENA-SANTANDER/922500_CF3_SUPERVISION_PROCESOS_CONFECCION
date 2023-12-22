<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 Tipos de patronaje y escalado
    
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="flip-up")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema2/img01.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Son diversas las técnicas empleadas que se esquematizan para la elaboración de patrones y moldes en prendas de vestir, estas técnicas son empleadas a partir de estudios antropométricos, en los que posteriormente, una vez se establece la técnica, pasa por pruebas de medición para determinar ergonomía y funcionalidad; una vez se realizan estas pruebas, se llevan a cabo los respectivos ajustes que serán implementados en dichos patrones. Se ha mencionado que se han logrado establecer metodologías y técnicas propiciando la industrialización global de los patrones, sin embargo, cada empresa, patronista, tallerista, modisto, sastre, costurero o diseñador emplean técnicas propias que consideran son necesarias para lograr una horma determinada. Estos ajustes son evaluados por las personas encargadas, partiendo de criterios universales en patronaje, o en otros casos, suelen establecer un modelo de patronaje diferente, esto siempre dependerá del enfoque de la empresa, el público objetivo y el producto.

    .tarjeta.tarjeta--gris.p-4.mb-5(data-aos="zoom-in-up")
      TabsC.color-acento-botones
        .py-3.py-md-4(titulo="Tipos de patronaje y líneas")
          .row.align-items-center.justify-content-around
            .col-md-7.mb-4.mb-md-0
              p Dentro de los tipos de patronaje encontramos dos grandes grupos: el primero es el patronaje industrializado que propicia la producción en masa de prendas. El segundo es el patronaje sobre medidas, el cual es personalizado, y en muchos modelos de negocio se emplea con la finalidad de brindar exclusividad a los clientes.
              p A continuación, se detallan las características de cada uno de ellos.
            .col-md-2
              img(src='@/assets/curso/tema2/img02.svg' alt="Imagen decorativa") 
        .py-3.py-md-4(titulo="Patronaje industrial")
          .row.align-items-center.justify-content-around
            .col-md-3.mb-4.mb-md-0
              img(src='@/assets/curso/tema2/img03.svg' alt="Imagen decorativa")
            .col-md-7
              p.mb-4 Es un patronaje empleado a través de un análisis antropométrico, el cual comprende la figura humana en 3D, es preciso en cuanto al paso a paso que se debe seguir para el levantamiento de básicos, el desarrollo de patrones y moldes con sus debidas transformaciones.  Se trabaja en 2D, en plano sobre papel o en ordenador, a través de software especializados para patronaje y trazo como, por ejemplo, Audaces 360, Optitex, Gerber, Lectra entre otros. 
              p Inicia a partir de tablas de medidas establecidas geográficamente acordes al uso final de una prenda, esto permite establecer técnicas de escalado en los que no se tenga que volver a generar un patrón y molde en tallas diferentes, sino que a través de las tablas de medidas se establecen los incrementos entre tallas y se generan fórmulas de crecimiento o decrecimiento en cada uno de los puntos de los moldes, a partir de una talla base, esto permite la masificación de prendas en producción de plantas de confección industrializadas.
        .py-3.py-md-4(titulo="El patronaje industrial comprende") 
          .row.align-items-center.justify-content-around
            .col-md-10.mb-4.mb-md-0
              ul.lista-ul--color.mb-5
                li.d-flex
                  i.fas.fa-atom
                  | Levantamiento de básicos delanteros y posteriores.
                li.d-flex
                  i.fas.fa-atom
                  | Levantamiento de prendas inferiores y superiores.
                li.d-flex
                  i.fas.fa-atom
                  | Levantamiento de patrones y moldes de las diferentes partes de las prendas comprendidas en los códigos de vestuario como: cuellos, escotes, mangas, puños, ribetes, bolsillos, charreteras y otros complementos en las prendas de vestir.
                li.d-flex
                  i.fas.fa-atom
                  | Abarcan todas las líneas: infantil, en sus diferentes etapas, dama y caballero.
                li.d-flex
                  i.fas.fa-atom
                  | A partir de las líneas se desarrolla toda una gama comercial que comprende universos de vestuario y ocasiones de uso.

              .titulo-sexto.color-acento-contenido
                h5 Figura 2. 
                | Patronaje industrial de chaqueta
              img(src='@/assets/curso/tema2/img04.png' alt="Imagen decorativa")
        .py-3.py-md-4(titulo="Patronaje sobre medidas")
          .row.align-items-center.justify-content-around
            .col-md-7.mb-4.mb-md-0
              p.mb-4 Es un patronaje preciso en cuanto a la ergonomía y funcionalidad de una prenda, es empleado para obtener prendas de vestir completamente hechas a la medida de un cliente o consumidor, es exclusivo y por lo general es empleado por marcas que buscan llegar a un público exigente y acorde a perfiles de consumidor; esto conlleva el proceso de toma de medidas antropométricas del cliente, realizar premuestra para primera medición, hechas en otro material textil, y posterior a la medición se realizan los ajustes a los que haya lugar y se procede con la realización de la muestra final o prenda. Dentro del patronaje sobre medidas suelen emplearse las siguientes técnicas:
              ul.lista-ul--color
                li 
                  i.fas.fa-atom
                  | El levantamiento de patrones en plano: similar al industrial, pero aquí el patronista implementa también técnicas y fórmulas que considere necesarias.
                li 
                  i.fas.fa-atom
                  | Patronaje sobre maniquí: técnica que es requerida en la construcción de prendas con drapeado o la aplicación de metodologías empleadas, como el Moulage, que es muy similar al drapeado. Sobre el maniquí suelen generarse dichos moldes dado que suelen anudarse, doblarse e incluso generar plisados y otros acabados cuyas texturas requieren de un trabajo mucho más arduo. Bajo esta técnica, muchas empresas, marcas, diseñadores, patronistas, sastres o modistos suelen realizar prendas de fiesta, vestidos de matrimonio, trajes para caballero e incluso para público infantil.
            .col-md-4
              img(src='@/assets/curso/tema2/img05.png' alt="Imagen decorativa")
        .py-3.py-md-4(titulo="El patronaje sobre medidas comprende")
          .row.align-items-center.justify-content-around
            .col-md-10.mb-4.mb-md-0
              ul.lista-ul--color.mb-5
                li 
                  i.fas.fa-atom
                  | Las mismas etapas del patronaje industrial, la diferencia entre este radica en la exclusividad que categoriza a la prenda, ofreciendo al usuario del producto la sensación de utilizar prendas que son desarrolladas y confeccionadas específicamente para su gusto y necesidad.
              .titulo-sexto.color-acento-contenido
                h5.text-center Figura 3. 
                | Patronaje sobre maniquí.
              img(src='@/assets/curso/tema2/img06.png' alt="Imagen decorativa")
    
    p.mb-4(data-aos="fade-right") A continuación, haremos un rápido recorrido por los Universos de vestuario y las ocasiones de uso:
    
    .row.justify-content-between.mb-4(data-aos="zoom-in-up")
      .col-7
      .col-lg-5
        a.anexo.mb-4(:href="obtenerLink('/downloads/Anexo_1_Universos_Vestuario_ Y_Ocasiones_Uso.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg" alt="Imagen decorativa")
          .anexo__texto
            strong Anexo. 
            | Universos del vestuario y ocasiones de uso
    
    p.mb-4(data-aos="fade-right") Dentro de los procesos productivos en las empresas todo el trabajo es guiado por fichas técnicas, las cuales permiten a cada uno de los integrantes de la empresa comprender el proceso a realizar, así como las especificaciones y datos que deben ser acatados con rigurosidad. Se invita a visualizar el posterior contenido con los siguientes fines: el primero es facilitar un reconocimiento de las partes de las prendas y el segundo permitirá identificar las fichas técnicas y su estructura.

    .row
      .col-lg-4.mb-4.mb-md-0
        a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=FHhqkd0h4Kw" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg" alt="Imagen decorativa")
          .anexo__texto
            strong Enlace web. 
            | Reconocimientos de las prendas
      .col-lg-4.mb-4.mb-md-0
         a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=5YOLIDHLiCw&t=122s" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg" alt="Imagen decorativa")
          .anexo__texto
            strong Enlace web. 
            | Introducción a la ficha técnica
      .col-lg-4.mb-4.mb-md-0
        a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=ck4jApUj5ss" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg" alt="Imagen decorativa")
          .anexo__texto
            strong Enlace web. 
            | Diligenciamiento de ficha técnica de prenda

</template>

<script>
export default {
  name: 'Tema2',
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
