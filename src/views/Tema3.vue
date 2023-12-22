<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 3
      h1 Estructura corporal y cuadro de tallas

    .row.mb-5
      .col-lg-7.d-flex.mb-4.mb-md-0(data-aos="fade-right")
        .cajon.color-acento-contenido.p-4
          p.mb-4 El vestuario está diseñado para dar cobertura al cuerpo, es por ello, que analizar el cuerpo en torno a su estructura y movimiento es de suma importancia para comprender en qué se fundamenta el patronaje y las diferentes metodologías utilizadas para su realización. Para el desarrollo de prendas de vestuario sobre medidas se hace aún más taxativo comprenderlo, pues en el desempeño dentro del sector industrial, se tendrá la necesidad de enfrentarse a diversas siluetas que necesitan ser analizadas dentro de la metodología y el paso a paso que se determina para la elaboración de un patrón.
          p Teniendo en cuenta lo anterior, se hará un recorrido para lograr entender el cuerpo y su estructura, a partir de los siguientes conceptos en relación con la estructura corporal:
      .col-lg-5.mb-4.mb-md-0(data-aos="fade-left")
        img(src='@/assets/curso/tema3/img01.png' alt="Imagen decorativa")
    
    ImagenInfografica.color-acento-contenido.mb-5
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/tema3/img02.svg' data-aos="zoom-in-up" alt="Imagen decorativa")
      .tarjeta.color-acento-contenido.p-3(x="17%" y="18%")
        p.text-white Ciencia que estudia toda estructura de los seres vivos, incluido su topografía, disposición y la relación de su cuerpo y los órganos que lo integran.
      .tarjeta.color-acento-contenido.p-3(x="54%" y="18%")
        p.text-white  Es la conjunción de disciplinas que estudian la estructura, función y movimiento del cuerpo, utiliza métodos mecánicos para determinar su fuerza y desplazamiento.
      .tarjeta.color-acento-contenido.p-3(x="85%" y="18%")
        p.text-white  Concepto relacionado a la parte biológica, encargada de estudiar la forma de los seres vivos.
      .tarjeta.color-acento-contenido.p-3(x="37%" y="95%")
        p.text-white  Disciplina que estudia las interacciones del ser humano con su entorno, reúne información que permite medir el desempeño y la optimización, buscando el bienestar de las personas a través del vestuario.
      .tarjeta.color-acento-contenido.p-3(x="69%" y="95%")
        p.text-white  Estudia a nivel cuantitativo las características físicas de las personas, es decir, todo lo relacionado con medidas y proporciones del cuerpo humano.
    
    .row.justify-content-center.mb-4
      .col-lg-10.mb-4.mb-md-0(data-aos="flip-up")
        .cajon.color-acento-contenido.p-4.mb-5
          p.mb-4 División del cuerpo: conocer el cuerpo humano es sumamente importante para traducir su estructura en medidas y patronaje de prendas, por lo que, a continuación, se podrá visualizar la división a tener en cuenta para su análisis.

        .titulo-sexto.color-acento-contenido(data-aos="zoom-in-down")
          h5 Figura 4. 
          | Análisis de división de cuerpo
        
        figure.mb-4(data-aos="zoom-in-up")
          img(src='@/assets/curso/tema3/img03.svg' alt="Imagen decorativa")
          figcaption Fuente: SENA, 2020
        
    p.mb-4(data-aos="fade-right") En el siguiente video se podrá conocer la estructura corporal, anatomía, cortes y ejes del cuerpo, antropometría y ergonomía, biomecánica, somatotipos, doshas, siluetas y evaluación de plomos y posturas.
    
    .row.justify-content-between.mb-4(data-aos="zoom-in-up")
      .col-lg-8
      .col-lg-4
        a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=V81Fjuq8XWs" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg" alt="Imagen decorativa")
          .anexo__texto
            strong Enlace web. 
            | Estructura del cuerpo.
    
    Separador
    #t_3_1.titulo-segundo(data-aos="zoom-in-right")
      .h2 3.1 Análisis y clasificación de las medidas
    
    .row.mb-4(data-aos="flip-up")
      .col-lg-2
      .col-lg-9
        .bloque-texto-a.color-secundario.p-4.p-md-4.mb-5 
          .row.m-0.align-items-center.justify-content-between
            .col-lg-8.mb-4.mb-lg-0
              .bloque-texto-a__texto.p-4
                p Para traducir a medidas el cuerpo humano, se debe guiar el proceso de patronaje para la elaboración de moldes, correspondientes a diseños o propuestas de la persona en el oficio de la creación de prendas de vestir, para esto es importante establecer el sistema de medidas que, clasificadas, denotan características para su uso e implementación.
            .col-lg-4
              img(src='@/assets/curso/tema3/img04.svg' alt="Imagen decorativa")
    
    .h4(data-aos="fade-right") Las medidas

    p.mb-4(data-aos="fade-right") Son unidades numéricas que permiten representar el tamaño de las figuras, personas u objetos.  Por lo general se trabaja con un sistema de medida de manera lineal, para medir las diferentes partes del cuerpo. En Colombia la metodología implementada se basa en centímetros o pulgadas, utilizando como instrumento el metro o cinta métrica. A continuación, se relacionan algunas consideraciones importantes sobre las medidas:
      
    TabsA.color-acento-contenido.mb-5(data-aos="zoom-in")
      .tarjeta.color-primario.p-4(titulo="a) Las medidas sobre el cuerpo")
        h4 a)	Las medidas sobre el cuerpo:
        p.mb-4 por lo general se toman sobre los puntos de anclaje del cuerpo teniendo en cuenta los parámetros antropométricos y anatómicos, pasando por los volúmenes (contornos) protuberantes. Se clasifican en tres grupos:
        ol.lista-ol--cuadro.mb-5
          li.d-flex
            .lista-ol--cuadro__vineta
              span.text-white 1
            p
              strong Contornos: 
              | se toman alrededor de la parte a medir, cerrando el metro.
          li.d-flex
            .lista-ol--cuadro__vineta
              span.text-white 2
            p
              strong Largos:  
              | se toman verticalmente y corresponden a largos y talles.
          li.d-flex
            .lista-ol--cuadro__vineta
              span.text-white 3 
            p
              strong Anchos:  
              | se toman horizontalmente y corresponden a los anchos.
        .titulo-sexto.color-acento-contenido
          h5 Figura 5. 
          | Clasificación de medidas.
        figure
          img(src='@/assets/curso/tema3/img05.svg' alt="Imagen decorativa")
          figcaption Fuente: Historias hiladas, 2021

      .tarjeta.color-primario.p-4(titulo="b) Clasificación y análisis de medidas anatómicas")
        h4 b)	Clasificación y análisis de medidas anatómicas
        p.mb-4 esta clasificación está dada según la metodología que se empleará en patronaje para la construcción de prendas, por ello es importante diferenciarlas, para así saber qué medidas tomar o no, si es sobre el cliente o solo se utilizan cuadros de tallas estandarizadas.
        .row.justify-content-between.mb-4
          .col-lg-6
          .col-lg-5
            a.anexo.mb-4(:href="obtenerLink('/downloads/Anexo_2_Clasificacion_de_las_medidas.pdf')" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-pdf.svg" alt="Imagen decorativa")
              .anexo__texto
                strong Anexo. 
                | Clasificación de las medidas

    Separador
    #t_3_2.titulo-segundo(data-aos="zoom-in-right")
      .h2 3.2 Análisis de medidas y cuadros de tallas
    
    .row.justify-content-center.mb-4(data-aos="flip-up")
      .col-lg-10
        .cajon.color-acento-contenido.p-4
          p Los cuadros de tallas y medidas son usados dentro del sector para contar fácilmente con la información estandarizada de las tallas de un país o región, las cuales estarán determinadas de acuerdo a estudios antropométricos, dado que las condiciones geográficas (como el clima y la cultura, entre otras) hacen que la anatomía y estructura corporal puedan diferir.

    .row.justify-content-center.mb-5
      .col-lg-7
        .titulo-sexto.color-acento-contenido(data-aos="zoom-in-down")
          h5 Figura 6. 
          | Medidas figura humana
        figure(data-aos="zoom-in-up")
          img(src='@/assets/curso/tema3/img06.svg' alt="Imagen decorativa")
          figcaption Fuente: Special Dressing, 2021
    
    .row
      .col-lg-5.mb-4.mb-lg-0(data-aos="fade-right")
        .cajon.color-acento-contenido.p-4
          p.mb-4 A continuación, le invitamos a revisar los aspectos a tener en cuenta al realizar el análisis del cuadro de tallas.
          .row.justify-content-between.mb-4
            .col-lg-4
            .col-lg-8
              a.anexo.mb-4(:href="obtenerLink('/downloads/Anexo_3_Analisis_de_cuadros_de_tallas.pdf')" target="_blank")
                .anexo__icono
                  img(src="@/assets/template/icono-pdf.svg" alt="Imagen decorativa")
                .anexo__texto
                  strong Anexo. 
                  | sobre Análisis de cuadro de tallas.
      .col-1
      .col-lg-5.d-flex.mb-4.mb-lg-0(data-aos="fade-left")
        .cajon.color-acento-contenido.p-4
          p.mb-4 También será importante que visualice el video en donde se explica el proceso de toma de medidas.
          .row.justify-content-between.mb-4
            .col-lg-4
            .col-lg-8
              a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=7tzquX5wI-4&t=2s" target="_blank")
                .anexo__icono
                  img(src="@/assets/template/icono-link.svg" alt="Imagen decorativa")
                .anexo__texto
                  strong Enlace web. 
                  | Toma de medidas.

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

<style lang="sass" scoped></style>
