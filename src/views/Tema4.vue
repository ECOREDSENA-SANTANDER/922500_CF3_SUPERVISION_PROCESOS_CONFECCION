<template lang="pug">
.curso-main-container.pb-4
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero
        span 4
      h1 Introducción al escalado
    
    .row.justify-content-center.align-items-center(data-aos="zoom-in-left")
      .col-lg-10.col-md-10.col-10
        .bloque-texto-a.color-acento-contenido.primtt.p-4.p-md-5.mb-5 
          .row.m-0.align-items-center.justify-content-between
            .col-lg-8
              .bloque-texto-a__texto.p-4
                p.my-1 El escalado de tallas hace referencia al proceso que permite la adecuación del patronaje de prendas de vestir partiendo de una base a cada una de las tallas generando incremento o reducción de tamaño para un modelo determinado. El escalado es aplicado por partes, las partes o piezas separadas (moldes) que se originan en el proceso de patronaje que parte de la interpretación de un modelo o diseño, es decir, se escalan por separado las partes o piezas de una camisa, delantero, posterior, cuello, manga y puño, y demás complementos que lo compongan.
            .col-lg-4.mb-4.mb-lg-0
              img(src="@/assets/curso/tema4/img01.svg", alt="tema2")
                

    p.mb-5 Es indispensable tener clara la terminología que se implementa en este proceso para evitar confundirse en la aplicación de esta metodología:

    .row.justify-content-center.align-items-center.mb-5
      .col-sm-12.col-lg-10
        .row.justify-content-center.align-items-center
          .col-sm-12.col-lg-5.mb-4.mb-md-0(data-aos="fade-left")
            img.mb-3(src='@/assets/curso/tema3/img35.png' alt="tema 4")
          .col-sm-12.col-lg-7
            .tarjeta.tarjeta--azul.p-4.bg111
              SlyderA(tipo="b")
                .row.justify-content-center.align-items-center
                  h4.mb-4 Talla prototipo
                  p.mb-4 Es la talla de la cual se parte un escalado, también llamado patrón base, por ejemplo, el básico del corpiño para dama.      
                .row.justify-content-center.align-items-center
                  h4.mb-4 Talla límite
                  p.mb-4 Es la talla escalada y para la cual se implementaron medidas específicas para poder obtener dicha pieza incrementada o reducida.
                .row.justify-content-center.align-items-center
                  h4.mb-4 Foco de proyección
                  p.mb-4 Punto hallado numéricamente y donde se partirán las líneas a proyectar.
                .row.justify-content-center.align-items-center
                  h4.mb-4 Constante
                  p.mb-4 Punto para hallar la longitud de los moldes.
                .row.justify-content-center.align-items-center
                  h4.mb-4 Base
                  p.mb-4 Medida de la que se partirá para implementar las medidas de escalado, por ejemplo, si para una empresa la talla base es la 8, de esta partirán para hacer el escalado de las demás tallas que manejan en dicha empresa.
                .row.justify-content-center.align-items-center
                  h4.mb-4 Proporciones
                  p.mb-4 Identificadas de acuerdo al cuadro de tallas o medidas estandarizadas, estas son establecidas por cada empresa o fábrica.
                .row.justify-content-center.align-items-center
                  .col-sm-12.col-md-8
                    h4.mb-4 Plano cartesiano
                    p.text-small.mb-4 Formado por rectas y perpendiculares, cuyo sistema es el que guía el movimiento de cada uno de los puntos o focos así:
                    p.text-small La recta horizontal es llamada eje de las abscisas o de las equis (x)
                    p.text-small La recta vertical, eje de las ordenadas o de las yes, (y)
                    p.text-small El punto donde se cortan recibe el nombre de origen (Punto cero o Punto muerto).
                  .col-md-4
                    .titulo-sexto.color-acento-contenido
                      h5 Figura 7. 
                      | Plano cartesiano
                    img(src='@/assets/curso/tema4/img02.svg' , alt="tema 4")

  
    Separador
    #t_4_1.titulo-segundo
      .h2 4.1 Tipos de escalado
    
    p.mb-4(data-aos="fade-right") Aunque se establece en el patronaje industrial una metodología universal para el escalado, de este se derivan varios tipos de escalado, dado que cada empresa o fábrica personaliza su cuadro de tallas o medidas a partir de las necesidades que cubren a sus públicos objetivos.

    p.mb-2(data-aos="fade-left") A continuación, se presentan los cuatro (4) tipos de escalado más utilizados en la industria de la confección:

    
    .row.tof.align-items-center.py-4.py-md-5
      .col-sm-12.col-lg-12.px-lg-5.px-4
        .row.justify-content-center.mb-4(data-aos="fade-down")
          .row.justify-content-center.mb-4(data-aos="fade-down") 
              .col-sm-12.col-lg-3
                p.mb-0
              .col-sm-12.col-lg-9.my-4
                .kaha.p-4.mb-4 
                  h4.color Escalado monobásico
                  p.mb-3 Se parte de tallas base para reducir o aumentar a otras tallas. Se realizan a partir de una constante de medida aplicada a toda la serie de tallas en largos y anchos, también es llamado escalado de crecimiento real y es proporcional.
                  .row
                    .col-auto
                      a.boton.color-acento-botones.indicador__container(@click="modal1 = true")
                        span Ver figura de escalado monobásico
                        .indicador--click(v-if="mostrarIndicador")
                    .col
                      p moment. Abandon the shelter of insecurity. Be bold. Greatness isn’t 
                        a.lnk(@click="modal1 = true") Abrir modal 
                        |the height of your stature, it’s the heft of your spirit.
                .kaha.p-4.mb-4 
                  h4.color Simple o relativo/diferencial
                  p.mb-3 Es implementado cuando en los cuadros de tallas se observa que los incrementos entre tallas varían dentro de la serie, por ejemplo, no hay mayor incremento en estatura (largos totales) pero si en anchos. 
                .kaha.p-4.mb-4 
                  h4.color Escalado bibásico
                  p.mb-3 Aplicado para obtener tallas intermedias a partir del análisis de medidas de dos tallas, con este se determina la talla base y la talla limite.
                .kaha.p-4.mb-4 
                  h4.color Escalado tribásico
                  p.mb-3 Similar al bibásico, aquí se toman tres tallas para obtener las tallas intermedias.  Por ejemplo: se toman las tallas 10, 14 y 18´pára obtener la talla 12 y 16 que corresponden a las intermedias.
    
    
    
    ImagenInfografica.color-primario.mb-5(data-aos="zoom-in-up")
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/tema4/img03.svg', alt="tema 4")
      .tarjeta.color-primario.p-3(x="19%" y="76%")
        .titulo-sexto.color-acento-contenido
          h5 Figura. 
          | Escalado monobásico
        img(src='@/assets/curso/tema4/img04.svg' , alt="tema 4")
      .tarjeta.color-primario.p-3(x="44%" y="76%")
        .titulo-sexto.color-acento-contenido
          h5 Figura. 
          | Escalado relativo

        img(src='@/assets/curso/tema4/img05.svg', alt="tema 4")
    
    Separador
    #t_4_2.titulo-segundo
      .h2 4.2 Análisis de cuadros de tallas

    
    .row.justify-content.align-items.mt-5
      .col-sm-12.col-lg-12
        .row
          .col-lg-3
            img.img-t.img-a(src='@/assets/curso/tema4/4.2.png', alt='Introducción') 
          .col-lg-9
            .boq.p-3
              p.mb-4.mx-3.my-3 Los cuadros de tallas como se ha mencionado son el punto importante dentro del escalado industrial de prendas, por ello se debe tener en cuenta:
              ul.lista-ul--color
                li.d-flex
                  i.fas.fa-car-side.mx-3
                  p.mb-0
                    strong Los límites de las tallas: 
                    | la más grande y la más pequeña.
                li.d-flex
                  i.fas.fa-car-side.mx-3
                  p.mb-0 
                    strong Frecuencia:  
                    | esto es lo que determina el aumento de medidas de talla a talla, aquí es importante analizar si es secuencial o no y se poseen constantes y variables.
                li.d-flex
                  i.fas.fa-car-side.mx-3
                  p.mb-0 
                    strong Incremento:  
                    | el crecimiento de talla por talla en cada uno de los apartados de las medidas antropométricas.
    
              .row.justify-content.align-items.mt-5
                .col-sm-12.col-lg-7
                  a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=q62l2sbPAaE" target="_blank")
                    .anexo__icono
                      img(src="@/assets/template/icono-link.svg" , alt="tema 4")
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
