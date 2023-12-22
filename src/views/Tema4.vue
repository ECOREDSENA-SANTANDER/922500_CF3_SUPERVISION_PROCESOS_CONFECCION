<template lang="pug">
.curso-main-container.pb-4
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 4
      h1 Introducción al escalado
    
    .row.justify-content-center.mb-4(data-aos="flip-up")
      .col-lg-10.mb-4.mb-md-0
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema4/img01.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 El escalado de tallas hace referencia al proceso que permite la adecuación del patronaje de prendas de vestir, partiendo de una base a cada una de las tallas y generando incremento o reducción de tamaño para un modelo determinado. El escalado es aplicado por partes, las partes o piezas separadas (moldes) que se originan en el proceso de patronaje que parte de la interpretación de un modelo o diseño, es decir, se escalan por separado las partes o piezas de una camisa, delantero, posterior, cuello, manga y puño, y demás complementos que lo compongan.

    .h4.mb-4(data-aos="fade-right")  Es indispensable tener clara la terminología que se implementa en este proceso para evitar confundirse en la aplicación de esta metodología:

    LineaTiempoD.color-secundario(data-aos="zoom-in-up")
      p.text-small(numero="1" titulo="Talla prototipo") Es la talla de la cual se parte un escalado, también llamado patrón base, por ejemplo, el básico del corpiño para dama.
      
      p.text-small(numero="2" titulo="Talla límite") Es la talla escalada y para la cual se implementaron medidas específicas para poder obtener dicha pieza incrementada o reducida.
      
      p.text-small(numero="3" titulo="Foco de proyección") Punto hallado numéricamente y donde se partirán las líneas a proyectar.
      
      p.text-small(numero="4" titulo="Constante") Punto para hallar la longitud de los moldes.

      p.text-small(numero="5" titulo="Base") Medida de la que se partirá para implementar las medidas de escalado, por ejemplo, si para una empresa la talla base es la 8, de esta partirán para hacer el escalado de las demás tallas que manejan en dicha empresa.

      p.text-small(numero="6" titulo="Proporciones") Identificadas de acuerdo al cuadro de tallas o medidas estandarizadas, estas son establecidas por cada empresa o fábrica.

      .row(numero="7" titulo="Plano cartesiano")
          .col-md-7.mb-4.mb-md-0
            p.text-small.mb-4 Formado por rectas y perpendiculares, cuyo sistema es el que guía el movimiento de cada uno de los puntos o focos así:
            p.text-small La recta horizontal es llamada eje de las abscisas o de las equis (x)
            p.text-small La recta vertical, eje de las ordenadas o de las yes, (y)
            p.text-small El punto donde se cortan recibe el nombre de origen (Punto cero o Punto muerto).
        
          .col-md-4
            .titulo-sexto.color-acento-contenido
              h5 Figura 7. 
              | Plano cartesiano
            img(src='@/assets/curso/tema4/img02.svg' alt="Imagen decorativa")

    Separador
    #t_4_1.titulo-segundo(data-aos="zoom-in-right")
      .h2 4.1 Tipos de escalado
    
    p.mb-4(data-aos="fade-right") Aunque se establece en el patronaje industrial una metodología universal para el escalado, de este se derivan varios tipos de escalado, dado que cada empresa o fábrica personaliza su cuadro de tallas o medidas a partir de las necesidades que cubren a sus públicos objetivos.

    p.mb-4(data-aos="fade-left") A continuación, se presentan los cuatro (4) tipos de escalado más utilizados en la industria de la confección:

    ImagenInfografica.color-primario.mb-5(data-aos="zoom-in-up")
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/tema4/img03.svg' alt="Imagen decorativa")
      .tarjeta.color-primario.p-3(x="19%" y="76%")
        .titulo-sexto.color-acento-contenido
          h5 Figura. 
          | Escalado monobásico
        img(src='@/assets/curso/tema4/img04.svg' alt="Imagen decorativa")
      .tarjeta.color-primario.p-3(x="44%" y="76%")
        .titulo-sexto.color-acento-contenido
          h5 Figura. 
          | Escalado relativo

        img(src='@/assets/curso/tema4/img05.svg' alt="Imagen decorativa")
    
    Separador
    #t_4_2.titulo-segundo(data-aos="zoom-in-right")
      .h2 4.2 Análisis de cuadros de tallas

    .row
      .col-md-7.mb-4.mb-md-0(data-aos="fade-right")
        p.mb-4 Los cuadros de tallas como se ha mencionado son el punto importante dentro del escalado industrial de prendas, por ello se debe tener en cuenta:
        ul.lista-ul--color
          li.d-flex
            i.fas.fa-atom
            p
              strong Los límites de las tallas:  
              |  la más grande y la más pequeña.
          li.d-flex
            i.fas.fa-atom
            p
              strong Frecuencia: 
              | esto es lo que determina el aumento de medidas de talla a talla, aquí es importante analizar si es secuencial o no y se poseen constantes y variables.
          li.d-flex
            i.fas.fa-atom
            p
              strong Incremento: 
              | el crecimiento de talla por talla en cada uno de los apartados de las medidas antropométricas.
        p Una vez esto es analizado y determinado da como resultado los valores, proporciones y rupturas de las tallas. Revisemos este proceso a profundidad:
      .col-md-5.mb-4.mb-md-0(data-aos="fade-left")
        figure.mb-4
          img(src='@/assets/curso/tema4/img06.svg' alt="Imagen decorativa")
        p.text-white.mb-4 .
        a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=q62l2sbPAaE" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg" alt="Imagen decorativa")
          .anexo__texto
            strong Enlace web. 
            | Introducción y contextualización de escalado de prendas de vestir.
    
</template>

<script>
export default {
  name: 'Tema4',
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
