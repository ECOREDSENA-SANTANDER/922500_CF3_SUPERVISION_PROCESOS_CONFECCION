<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero
        span 5
      h1 Patronaje femenino
    
    
    .row.align-items-center.justify-content-center.mb-5
      .col-lg-5.col-md-10.col-10
        img.mb-4(src="@/assets/curso/tema5/001.png", alt="tema 5")
      .col-lg-7.col-md-12.col-12(data-aos="fade-right")
        p.mb-4 Para el desarrollo y construcción del patronaje de prendas de vestir para la línea femenina, se trabajará una serie de conceptos y técnicas en la elaboración de bases y básicos, por medio de la aplicación de las medidas anatómicas y el manejo de incremento entre tallas, por medio del escalado.  Las bases en patronaje son el calco del cuerpo para prendas superiores e inferiores, estos patrones no pueden ser utilizados para ser cortados de forma inmediata en tela o utilizados para elaborar una prenda, ya que antes deben recibir adaptaciones (desahogos, amplitudes, cortes y otros) para proceder a ser utilizados en producción. De la calidad del mismo dependerá la estabilidad dimensional del patrón y el buen calce de la prenda una vez confeccionada.
        
    .row.align-items-center.justify-content-center.mb-4
      .col-md-8.mb-4.mb-md-0.mb-5
        .cajon.color-acento-contenido.p-4
          p.pt-3.mx-2 Los patrones bases o básicos se crean según el tipo de prenda, como se presenta en la siguiente figura:

    .row.justify-content-center.mb-4
          .col-sm-12.col-lg-8
            .titulo-sexto.color-acento-contenido
              h5 Figura 10. 
              | División moldes según tipo de prenda
            img(src='@/assets/curso/tema5/img01.svg' , alt="Considerar la imagen en donde se muestra una silueta humana con una subdivisión superior e inferior de prendas bases o básicos, para hombres y mujeres. Así mismo expone las bases o básicos las mono prendas para dama y caballero.")
    
    separador
    #t_5_1.titulo-segundo
      .h2 5.1 Trazo de falda

    .row.justify-content-center.align-items-center(data-aos="zoom-in-left")
      .col-lg-10.col-md-10.col-10
        .bloque-texto-a.color-acento-contenido.primtt.p-4.p-md-5.mb-5 
          .row.m-0.align-items-center.justify-content-between
            .col-lg-8.mb-4
              .bloque-texto-a__texto.p-3
                p.my-1 Para iniciar el proceso de construcción de moldes, es recomendable comenzar con patrones o levantamientos más simples. Esto facilitará la comprensión del sistema que se desarrollará en el esquema. La falda básica se elige como el primer estilo debido a su simplicidad. A través de este punto de partida, se logra una comprensión adecuada de cada regla de costura, lo que proporciona una mayor confianza para abordar estilos posteriores. Las medidas necesarias para trazar la falda son el contorno de cintura, el contorno de cadera y el largo de la falda.
            .col-lg-4.mb-4.mb-lg-0
              img.img-a.img-t.mb-4(src="@/assets/curso/tema5/img02.svg", alt="tema2")

    
    .mb-5.d-flex
      .d-flex.flex-wrap.align-items-center.pe-4.bg-img-blue
        h5.col.px-4.mb-0.text-white.mx-5(data-aos="fade-right") Trazado de la falda básica
        img.clase2(src='@/assets/curso/tema3/vot.svg', alt="tema 5") 
    
    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-sm-12.col-lg-12.mb-4.mb-md-0
        .cajon.color-acento-contenido.p-4
          p.my-1 Analizar la tipología de la falda a desarrollar es importante para determinar qué medida de largo se necesita para generar el rectángulo de inicio y luego el levantamiento del molde; para lo cual también será importante conocer los siguientes aspectos:

    .tarjeta--container.parr.row.mb-5
      .col-md.tarjeta.color-priimario.p-5
        
          h4.text-center.mb-4 Longitud de las faldas
          p.text-center.mb-5 La longitud de la falda puede ser variada: minifalda, maxi falda, hasta la rodilla y hasta el suelo. 
            .titulo-sexto.color-acento-contenido
              h5 Figura 11. 
              | Longitud de la falda
            img(src='@/assets/curso/tema5/img03.png' , alt="La longitud de la falda puede ser variada: minifalda, maxi falda, hasta la rodilla y hasta el suelo. ")
            figcaption.texte.text-black Fuente: SENA, 2021
        
      
      .col-md.tarjetas.color-acento-contenidot.p-5
          h4.text-center.mb-4 La circunferencia de la cintura
          p.text-center.mb-5 La circunferencia de la cintura puede ser tan baja como por debajo del ombligo y tan alta como por encima de la cintura.
            .titulo-sexto.color-acento-contenido
              h5 Figura 12. 
              | Longitud de la falda
            img(src='@/assets/curso/tema5/img04.png' , alt=" La circunferencia de la cintura puede ser tan baja como por debajo del ombligo y tan alta como por encima de la cintura.")
            figcaption.texte.text-black Fuente: SENA, 2021
        
    .row.justify-content.align-items.mt-5.mb-5
      .col-sm-12.col-lg-12
        .row.justify-content-center.mb-5
          .col-lg-5.col-md-8.col-8
            img.img-t.img-a.my-2(src='@/assets/curso/tema5/ima3.png', alt="tema 5") 
          .col-lg-7
            .boqu.p-4.my-3
              p.mb-4.mx-3.my-3 #[b Trazado de la falda basica:] Como punto de partida se deben tomar las medidas anatómicas con precisión. No deben sumar centímetros de más, por ello se recomienda seguir con atención los pasos del manual de patronaje básico e interpretación de diseños que se relaciona a continuación, pues el básico inferior de falda, siempre se trabaja partiendo desde un rectángulo e identificando los siguientes puntos:
              ul.lista-ul--color
                li.d-flex
                  i.fas.fa-car-side.mx-3.mb-4
                  | Parte superior (cintura) – línea superior.
                li.d-flex
                  i.fas.fa-car-side.mx-3.mb-4
                  | Parte inferior (rodilla) – línea inferior.
                li.d-flex
                  i.fas.fa-car-side.mx-3.mb-4
                  | Parte derecha – posterior.
                li.d-flex
                  i.fas.fa-car-side.mx-3.mb-4
                  | Parte izquierda – delantero.


        p.mb-5.text-center Para profundizar en estos aspectos será importante revisar el material:
        
        .row.justify-content-center.align-items-center
          .col-sm-12.col-lg-10
            .fondo21.p-3.mb-4
              .row.justify-content-around.align-items-center.mb-2
                .col-3.col-sm-2.col-lg-1
                  img.img-a.img-t(src="@/assets/curso/tema5/pdff.svg", alt="tema 5")
                .col
                  .row.justify-content-between.align-items-center
                    .col.mb-2.mb-sm-0          
                      h4 Manual de patronaje básico
                      p.mb-0.irr Consulte el “Manual de patronaje básico e interpretación de diseños - Conocimiento de los puntos de referencia para el trazado de las faldas”. Leer de la página 15 a 17.
                    .col-sm-auto
                      a.boton.color-acento-botones(:href="obtenerLink('/downloads/Manual_patronaje_básico_interpretacion_diseños.pdf')" target="_blank")
                        span Descargar
                        i.fas.fa-file-download
              .hr.mb-3
              .row.justify-content-around.align-items-center.mb-4
                .col-3.col-sm-2.col-lg-1
                  img.img-a.img-t(src="@/assets/curso/tema5/pdff.svg", alt="tema 5")
                .col
                  .row.justify-content-between.align-items-center
                    .col.mb-3.mb-sm-0          
                      h4 Manual de patronaje básico
                      p.mb-0.irr Consulte el “Manual de patronaje básico e interpretación de diseños - Conocimiento de los puntos de referencia para el trazado de las faldas”. Leer de la página 31 a 32.
                    .col-sm-auto
                      a.boton.color-acento-botones(:href="obtenerLink('/downloads/Manual_patronaje_básico_interpretacion_diseños.pdf')" target="_blank")
                        span Descargar
                        i.fas.fa-file-download
              .hr.mb-3
              .row.justify-content-around.align-items-center.mb-4
                .col-3.col-sm-2.col-lg-1
                  img.img-a.img-t(src="@/assets/curso/tema2/video.svg", alt="tema 5")
                .col
                  .row.justify-content-between.align-items-center
                    .col.mb-3.mb-sm-0          
                      h4 Patronaje delantero falda básica
                      p.mb-0.irr Consulte el video “Patronaje delantero falda básica”.
                    .col-sm-auto
                      a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=Zlc9gtFlJLw" target="_blank")
                        span Ir al sitio
                        i.fas.fa-video
              .hr.mb-3
              .row.justify-content-around.align-items-center.mb-1
                .col-3.col-sm-2.col-lg-1
                  img.img-a.img-t(src="@/assets/curso/tema5/vide.svg", alt="tema 5")
                .col
                  .row.justify-content-between.align-items-center
                    .col.mb-3.mb-sm-0          
                      h4 Base inferior falda femenino
                      p.mb-0.irr Consulte el video “Base inferior falda femenino”.
                    .col-sm-auto
                      a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=kw9nde2uyBs" target="_blank")
                        span Ir al sitio
                        i.fas.fa-video
    
    
    .row.justify-content-center.align-items-center
      .col-sm-12.col-lg-10
        p.mb-5 En el siguiente repositorio de podrá encontrar información asociada a las variaciones de la falda, en donde se tienen en cuenta las diversas posibilidades de variación en los patrones de esta prenda:

    
    .row.justify-content-center.align-items-center
      .col-sm-12.col-lg-10
        .fondo21.p-3.mb-4
          .row.justify-content-around.align-items-center.mb-4
            .col-3.col-sm-2.col-lg-1
              img.img-a.img-t(src="@/assets/curso/tema5/vide.svg", alt="tema 5")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-2.mb-sm-0          
                  h4 Trazo de faldas rotondas
                  p.mb-0.irr Consulte el video “Trazo de faldas rotondas”.
                .col-sm-auto
                  a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=DJIfqv1L4FA" target="_blank")
                    span Ir al sitio
                    i.fas.fa-video
          .hr.mb-3
          .row.justify-content-around.align-items-center.mb-4
            .col-3.col-sm-2.col-lg-1
              img.img-a.img-t(src="@/assets/curso/tema5/vide.svg", alt="tema 5")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0          
                  h4 Trazo de falda y modificación de básicos de falda 
                  p.mb-0.irr Consulte el video “Trazo de falda y modificación de básicos de falda”.
                .col-sm-auto
                  a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=gfHPZ8-gzwQ" target="_blank")
                    span Ir al sitio
                    i.fas.fa-video
          .hr.mb-3
          .row.justify-content-around.align-items-center.mb-1
            .col-3.col-sm-2.col-lg-1
              img.img-a.img-t(src="@/assets/curso/tema5/pdff.svg", alt="tema 5")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0          
                  h4 Manual de interpretación de diseño
                  p.mb-0.irr Consulte el “Manual de patronaje básico e interpretación de diseños - Diseño de faldas”. Leer de la página 33 a 38.
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('/downloads/Manual_patronaje_básico_interpretacion_diseños.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download
  
      
    separador
    #t_5_2.titulo-segundo
      .h2 5.2 Trazo de base superior femenina
    
    .row.fondo22.align-items-center
      .col-lg-12.col-md-12.col-12.mb-2
        .row.justify-content-center
          
          .row.justify-content-center.align-items-center.mb-5
            .col-lg-7.col-md-12.col-12.mb-0
              p.mx-4.my-5 El manejo de volúmenes es un factor crucial en el desarrollo de prendas, ya que se logran mediante el uso de pinzas y sistemas de ajuste; es importante tener en cuenta que, independientemente del diseño trabajado, la metodología y los pasos a seguir son siempre los mismos, lo que lleva a determinar que este enfoque secuencial permite una mejor asimilación de la metodología.
            .col-lg-5.col-md-9.col-9
              img.img-t.img-a.my-2.mover(src='@/assets/curso/tema5/img123.svg', alt="tema 5") 
    
    .mb-4.d-flex
      .d-flex.flex-wrap.align-items-center.pe-4.bg-img-blue
        h5.col.px-4.mb-0.text-white.mx-5(data-aos="fade-right") Volumen de la prenda 
        img.clase2(src='@/assets/curso/tema3/vot.svg', alt="tema 5") 
        
    .row.vrl.align-items-center.py-4.py-md-5.mb-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.justify-content-center(data-aos="fade-down") 
    
    
        .row.justify-content-center.align-items-center(data-aos="zoom-in-left")
          .col-sm-12.col-lg-10
            .bloque-texto-a.color-acento-contenido.prim.p-4.p-md-5.mb-5 
              .row.m-0.align-items-center.justify-content-between
                .col-lg-4.mb-4.mb-lg-0
                  img(src="@/assets/curso/tema5/grupo.svg", alt="tema5")
                .col-lg-8
                  .bloque-texto-a__texto.p-4
                    p Existen prendas más grandes que el cuerpo, iguales o más pequeñas como las elaboradas en tejidos de punto o con telas licradas. La diferencia entre la prenda y el cuerpo que visten recibe el nombre de desahogo, el mayor o menor desahogo condiciona el volumen de la prenda. El desahogo de una prenda debe mantenerse constante en todas las tallas del mismo diseño.
      
              
          p.mb-4 A continuación, se presentan los valores de desahogo (en centímetros) estimados según el tipo de prenda y volumen deseado:
          
            .row.m-0.justify-content-center
              .col-lg-10.mb-4.mb-lg-0
                .tabla-a.color-acento-contenido.mb-5 
                  table
                    thead
                      tr
                        th Prenda
                        th Estrecho
                        th Ajustada
                        th Normal
                        th Ancha
                        th Muy ancha
                    tbody.tarjeta--white
                      tr
                        td.text-center Blusa
                        td.text-center 2
                        td.text-center 4
                        td.text-center 6
                        td.text-center 8
                        td.text-center 10
                      tr
                        td.text-center Vestido
                        td.text-center 4
                        td.text-center 6
                        td.text-center 8
                        td.text-center 10
                        td.text-center 12
                      tr
                        td.text-center Falda
                        td.text-center 0
                        td.text-center 1
                        td.text-center 2
                        td.text-center 6
                        td.text-center 8
                      tr
                        td.text-center Pantalón
                        td.text-center 0
                        td.text-center 1
                        td.text-center 2
                        td.text-center 4
                        td.text-center 6
                      tr
                        td.text-center Chaqueta
                        td.text-center 4
                        td.text-center 6
                        td.text-center 8
                        td.text-center 10
                        td.text-center 12
                      tr
                        td.text-center Chaquetón
                        td.text-center 6
                        td.text-center 8
                        td.text-center 10
                        td.text-center 12
                        td.text-center 14
                      tr
                        td.text-center Abrigo
                        td.text-center 8
                        td.text-center 10
                        td.text-center 12
                        td.text-center 14
                        td.text-center 16
                p.mb-4 En función al volumen del tejido, los anteriores valores pueden ser ajustados de la siguiente manera, y son aplicados al contorno.
                .row.m-0.justify-content-center
                  .col-lg-10.mb-0.mb-lg-0
                    .tabla-a.color-acento-contenido.mb-0
                      table
                        thead
                          tr
                            th Muy fino
                            th fino
                            th Normal
                            th Grueso
                            th Muy grueso
                        tbody.tarjeta--gris
                          tr
                            td.text-center -2
                            td.text-center -1
                            td.text-center 0
                            td.text-center +2
                            td.text-center +4
    
    .mb-4.d-flex.mb-5
      .d-flex.flex-wrap.align-items-center.pe-4.bg-img-blue
        h5.col.px-4.mb-0.text-white.mx-5(data-aos="fade-right") Pasos para el trazo de la base superior
        img.clase2(src='@/assets/curso/tema3/vot.svg', alt="tema 5") 
    
    p.mb-4 Cuando se habla de la base superior, se hace referencia a la copia de la horma del cuerpo partiendo del cuello hasta la cintura, dicha base será la plantilla que se adecuará para convertirse en blusa, camiseta, chaqueta, chaleco, corpiño y demás prendas femeninas, incluyendo el vestido.
    p.mb-5 Conozca el paso a paso para la elaboración de estos patrones revisando los siguientes recursos:

    .row.justify-content-center.align-items-center.mb-5
      .col-sm-12.col-lg-10
        .fondo21.p-3.mb-4
          .row.justify-content-around.align-items-center.mb-4
            .col-3.col-sm-2.col-lg-1
              img.img-a.img-t(src="@/assets/curso/tema5/pdff.svg", alt="tema 5")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-2.mb-sm-0          
                  h4 Manual de patronaje básico e interpretación de diseños
                  p.mb-0.irr Consulte el “Manual de patronaje básico e interpretación de diseños - Conocimiento para hace patrón base superior femenino”. Leer de la página 20 a 25.
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('/downloads/Manual_patronaje_básico_interpretacion_diseños.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download
          .hr.mb-3
          .row.justify-content-around.align-items-center.mb-4
            .col-3.col-sm-2.col-lg-1
              img.img-a.img-t(src="@/assets/curso/tema5/vide.svg", alt="tema 5")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0          
                  h4 Pasos para el trazo de la base superior  
                  p.mb-0.irr Consulte el video “Trazo de la base superior femenina”.
                .col-sm-auto
                  a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=HzUZmIGpKjs" target="_blank")
                    span Ir al sitio
                    i.fas.fa-video
          .hr.mb-3
          .row.justify-content-around.align-items-center.mb-1
            .col-3.col-sm-2.col-lg-1
              img.img-a.img-t(src="@/assets/curso/tema5/vide.svg", alt="tema 5")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0          
                  h4 Trazo de falda y modificación de básicos de falda
                  p.mb-0.irr Consulte el video “Trazo de falda y modificación de básicos de falda”.
                .col-sm-auto
                  a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=gfHPZ8-gzwQ" target="_blank")
                    span Ir al sitio
                    i.fas.fa-video
  
    .mb-4.d-flex.mb-5
      .d-flex.flex-wrap.align-items-center.pe-4.bg-img-blue
        h5.col.px-4.mb-0.text-white.mx-5(data-aos="fade-right") Pinza correctiva de talle
        img.clase2(src='@/assets/curso/tema3/vot.svg' , alt="tema 5") 

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-4.col-md-8.col-8.mb-4.mb-lg-0(data-aos="fade-left")
        img.mb-4(src='@/assets/curso/tema5/pab.png' , alt="tema 5")
      .col-lg-8.mb-4.mb-lg-0(data-aos="fade-right")
        p.mb-3 En el momento que se unen por los básicos delantero y posterior por la línea de la cintura, se evidencia el desnivel anatómico entre estos, es de aquí que surge esta pinza como una marca de referencia principal, para generar volúmenes o ajustes sobre el cuerpo. Permite ser trasladada o llevada a diferentes puntos del cuerpo, permitiendo así acentuar volúmenes, generar siluetas o estructuras que permiten modificar diseños. Según la interpretación queda invisible o visible a propósito.
          ul.lista-ul--color.mb-5
          li.d-flex.mb-2
            i.fas.fa-car-side.my-1
            p.mx-4 Las pinzas pueden ser transferidas o desviadas a cualquier dirección alrededor del punto de busto (punto giratorio) sin afectar el tamaño ni entalle del patrón.
          li.d-flex.mb-3
            i.fas.fa-car-side.my-1
            p.mx-4 El exceso de la pinza, es decir, el espacio entre lados de la pinza puede ser utilizado como recogidos, pliegues, pinzas semi cosidas o en los cortes de diferentes estilos o diseños.
          .col-sm-12.col-lg-12
            .fondo211.p-3.mb-2
              .row.justify-content-center.align-items-center
                .col-lg-2
                  img.mx-4.img-a.img-t.d-none.d-lg-block(src="@/assets/curso/tema5/alertaa.svg", alt="tema 5")
                .col-lg-10.col-md-12.col-12         
                  p.my-2 #[b Tener en cuenta:] Todas las pinzas deben terminar antes del punto de busto (punto giratorio), nunca deben traspasar dicho punto. 

    
    h4.mb-4  Técnicas de transformación
    p.mb-3 Estas técnicas hacen referencia a métodos que permiten el desplazamiento de las pinzas y su reubicación. Se presentan las dos más utilizadas:
    

    .row.fonfu.align-items-center.py-4.py-md-5.mb-5 
      .col-sm-12.col-lg-12.px-lg-5.px-4
        .row.justify-content-center.mb-4(data-aos="fade-down")
          
          .row.justify-content-center.items-align-center
            .col-sm-12.col-lg-3.mb-4
              img.img-a.img-t.d-none.d-lg-block.mb-5(src='@/assets/curso/tema5/img55.svg' , alt="")
            .col-sm-12.col-lg-4
              .boika.p-4.my-4.shadow 
                p.color.my-3 1. Cortar y unir:
                p.mb-4 Este método requiere cortar el patrón base para luego unir las partes con la reubicación de la pinza.
            .col-sm-12.col-lg-4
              .boika.p-4.my-4.shadow  
                p.color.my-3 2. Pivoteo (girar):
                p.mb-4 Este método no requiere cortar el patrón básico, sino girarlo a través del punto de busto transfiriendo de esta manera la pinza.
            .col-sm-12.col-lg-1
        .row.justify-content-center.items-align-center
          .col-sm-6.col-lg-5.mb-4.mb-lg-4
            p.mb-4 Los puntos en que se hace posible el traslado de la pinza son los siguientes:
            .tarje.p-4.mb-5
              .row.justify-content-center.mb-4
                .col-lg-12.my-2
                  .titulo-sexto.color-acento-contenido
                    h5 Figura 13. 
                    | Puntos de traslado de pinza
                  .col-lg-12
                    img.mb-3.my-5(src='@/assets/curso/tema5/errr.svg' , alt="La imagen muestra los puntos de traslados  de pinza, dependiendo la amplitud que requiera la prenda por ellos se especifican en los diferentes cortes de la prenda.")
                    figcaption Fuente. Adaptado de SENA, 2021
          
          .col-sm-6.col-lg-5.mb-4.mb-lg-4
            p.mb-4 A continuación, se observa la transformación que sufre el patrón de acuerdo a la técnica aplicada y la necesidad de la prenda.
            .tarjett.p-4
              .row.justify-content-center.mb-4
                .col-lg-12.my-2
                  .titulo-sexto.color-acento-contenido
                    h5 Figura 14. 
                    | Traslados de pinza en base
                  .col-lg-12
                    img(src='@/assets/curso/tema5/aer.svg', alt="EL patrón sufre unos cambios, según los traslados de pinzas, teniendo en cuenta los cortes que se hacen a la pieza según el estilo que se le quiere dar a la prenda")
                    figcaption Fuente. Adaptado de SENA, 2021
                  
        p.mb-4.text-center Para comprender este proceso podrá explorar el video explicativo sobre cómo se hacen traslados de pinza correcta de talles.

        .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
          .col-sm-12.col-lg-10
            .fondo21.p-3.mb-4
              .row.justify-content-around.align-items-center.mb-0
                .col-3.col-sm-2.col-lg-1
                  img.img-a.img-t.mx-4(src="@/assets/curso/tema5/vide.svg", alt="tema 5")
                .col
                  .row.justify-content-between.align-items-center
                    .col.mb-2.mb-sm-0          
                      h4.mx-4 Traslados de pinza correctiva de talles
                      p.mb-0.irr.mx-4 Consulte el video “Traslados de pinza correctiva de talles”.
                    .col-sm-auto
                      a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=EpSXWyWzcPo" target="_blank")
                        span Ir al sitio
                        i.fas.fa-video

    .mb-4.d-flex.mb-5
      .d-flex.flex-wrap.align-items-center.pe-4.bg-img-blue
        h5.col.px-4.mb-0.text-white.mx-5(data-aos="fade-right") Análisis y trazo de sistema de ajuste. (Pinzas y cortes)
        img.clase2(src='@/assets/curso/tema3/vot.svg' data-aos="fade-left") 

    .row.justify-content-center.align-items-center
      .col-sm-12.col-lg-8
        p.mb-4 Dentro del desarrollo de moldes y patrones, se hace indispensable el manejo de pinzas, como sistema de ajuste o como insumo principal para el manejo de volúmenes, las pinzas en femenino son un punto de partida primordial y especifico el cual es necesario comprender desde la base funcional estructural y matemática.
        p.mb-4 Para comprender el funcionamiento de las pinzas, se trabajará únicamente la parte superior femenina, contemplando la circunferencia y el volumen del busto, de igual manera el contorno de cintura y el contorno de cadera, cada uno de estos contornos maneja características como volúmenes más protuberantes de los #[em tops] o los #[em bottoms] y punto unión o encuentro entre la división del cuerpo.
        p.mb-4 En el manejo de pinzas únicamente se trabajará con los contornos relevantes o que se toman como punto de partida para la construcción de básicos (contorno de busto – contorno de cintura – contorno de cadera).
        p.mb-4 Sin importar el tipo de prenda, los desahogos o la interpretación, las pinzas como sistema de ajuste siempre se trabajarán sobre esos contornos debido a que son los contornos con los que se trabaja la base o el básico. Consultar el siguiente video explicativo sobre cómo se hace el trazo de sistemas de ajuste de pinzas y cortes.
      .col-md-10.col-lg-4.col-10
        img.img-a.img-t.mb-5(src='@/assets/curso/tema5/imagen555.png' , alt="tema 5") 

    .row.justify-content-center.align-items-center(data-aos="zoom-in-left")
      .col-sm-12.col-lg-10
        .fondo21.p-3.mb-5
          .row.justify-content-around.align-items-center.mb-0
            .col-3.col-sm-2.col-lg-1
              img.img-a.img-t.mx-3(src="@/assets/curso/tema5/vide.svg", alt="tema 5")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-2.mb-sm-0          
                  h4.mx-4.my-1 Análisis y trazo de sistema de ajuste pinzas y cortes
                  p.mb-0.irr.mx-4 Consulte el video “Análisis y trazo de sistema de ajuste pinzas y cortes”.
                .col-sm-auto
                  a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=pb0f6QFi9Y8" target="_blank")
                    span Ir al sitio
                    i.fas.fa-video
    
    p.mb-4.text-center A continuación se exponen los siguientes contenidos, con las posibles  variaciones que presenta la prenda superior femenina:

    
    .row.justify-content-center.align-items-center.mb-4
      .col-lg-4.col-md-8.col-12.mb-4
        .fondo21e
          .row.justify-content-center.align-items-center.mb-4
            .col-lg-11.col-md-11.col-11
              img.img-a.img-t.mt-4(src='@/assets/curso/tema5/vide.svg', alt="tema 5")
              h4.text-center.mt-4 Pasos para el trazo de la base superior
              p.mb-5.my-3 Consulte el video “Base superior femenino”.
              .row.justify-content-center.align-items-center
                .col-sm-auto.mb-5
                  a.boton.color-acento-botones.my-4(href="https://www.youtube.com/watch?v=MJJln-zDjfc" target="_blank")
                    span Ir al sitio
                    i.fas.fa-video

      .col-lg-4.col-md-8.col-12.mb-4
        .fondo21e
          .row.justify-content-center.align-items-center.mb-4
            .col-lg-11.col-md-11.col-11
              img.img-a.img-t.mt-4(src='@/assets/curso/tema5/vide.svg', alt="tema 5")
              h4.text-center.mt-4 Trazo blusa con almilla y cuello camisero
              p.mb-5.my-3 Consulte el video “Trazo de blusa femenina”.
              .row.justify-content-center.align-items-center
                .col-sm-auto
                  a.boton.color-acento-botones.my-4(href="https://www.youtube.com/watch?v=DamxUrw0CZM" target="_blank")
                    span Ir al sitio
                    i.fas.fa-video

      .col-lg-4.col-md-8.col-12.mb-4
        .fondo21e
          .row.justify-content-center.align-items-center.mb-4
            .col-lg-11.col-md-11.col-11
              img.img-a.img-t.mt-4(src='@/assets/curso/tema2/video.svg', alt="tema 5")
              h4.text-center.mt-4 Trazo de prendas superiores - Camisa
              p.mb-5.my-3 Consulte el video “Trazo de prendas superiores - Camisa”.
              .row.justify-content-center.align-items-center
                .col-sm-auto
                  a.boton.color-acento-botones.my-0(href="https://www.youtube.com/watch?v=YgPcDIMHU8U" target="_blank")
                    span Ir al sitio
                    i.fas.fa-video  

    .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
      .col-lg-10
        .fondo211.p-2.mb-2
          .row.justify-content-center.align-items-center
            .col-3.col-sm-2.col-lg-2
              img.img-a.img-t.d-none.d-lg-block(src="@/assets/curso/tema5/alertaa.svg", alt="tema 5")
            .col-lg-10.col-md-12.col-12.p-4
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0         
                  p.my-2.mb-4 #[b Tener en cuenta:] 
                  ul.lista-ul--color
                    li.d-flex.mb-4
                      i.fas.fa-car-side.mb-4
                      | Después de su construcción, se aplican desahogos, traslado de pinza correctiva de talle, sistema de cierre y complementos de diseño (almillas, bolsillo de parche). 
                    li.d-flex
                      i.fas.fa-car-side.mb-4
                      | Para el trazo del plano desde los básicos se debe iniciar trazando una línea de referencia, en el caso de las bases superiores, se traza una línea de manera horizontal en el papel, sobre la cual quedará alineados o aplomados desde la línea base de construcción, en prendas superiores, la línea de aplome o línea base será la línea de profundidad de sisa.
                
    p.mb-5 A continuación, se presentan las variaciones de los patrones básicos para el vestido:

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-4.col-md-8.col-12.mb-4
        .fondo21e
          .row.justify-content-center.align-items-center.mb-4
            .col-lg-11.col-md-11.col-11
              img.img-a.img-t.mt-4(src='@/assets/curso/tema5/vide.svg', alt="tema 5")
              h4.text-center.mt-4 Trazo de la Bata o vestido
              p.mb-4.my-3 Consulte el video “Trazo de prendas - Bata o vestido”.
              .row.justify-content-center.align-items-center
                .col-sm-auto
                  a.boton.color-acento-botones.my-4(href="https://www.youtube.com/watch?v=eH7LRTKK040" target="_blank")
                    span Ir al sitio
                    i.fas.fa-video
      
      .col-lg-4.col-md-8.col-12.mb-4
        .fondo21e
          .row.justify-content-center.align-items-center.mb-4
            .col-lg-11.col-md-11.col-11
              img.img-a.img-t.mt-4(src='@/assets/curso/tema5/vide.svg', alt="tema 5")
              h4.text-center.mt-4 Cuellos y solapas
              p.mb-4.my-3 Consulte el video “Trazo de escotes y tipos de cuellos”.
              .row.justify-content-center.align-items-center
                .col-sm-auto
                  a.boton.color-acento-botones.my-4(href="https://www.youtube.com/watch?v=fMp3RRQ384s" target="_blank")
                    span Ir al sitio
                    i.fas.fa-video

      .col-lg-4.col-md-8.col-12.mb-4
        .fondo21e
          .row.justify-content-center.align-items-center.mb-4
            .col-lg-11.col-md-11.col-11
              img.img-a.img-t.mt-4(src='@/assets/curso/tema5/pdff.svg', alt="tema 5")
              h4.text-center.mt-4 Variación del vestido
              p.mb-3.my-3 Consulte el anexo “Variación del vestido”. Leer de la página 59 a 62.
              .row.justify-content-center.align-items-center
                .col-sm-auto
                  a.boton.color-acento-botones.my-4(:href="obtenerLink('/downloads/Manual_patronaje_básico_interpretacion_diseños.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download


    separador
    #t_5_3.titulo-segundo
      .h2 5.3 El pantalón femenino y sus variantes
  
    .row.justify-content-center.align-items-center.mb-4
      .col-md-8.col-lg-4.col-8
        img.mb-5(src='@/assets/curso/tema5/img12.png' , alt="tema 5")
      .col-sm-12.col-lg-8
        p.mb-5 Cuando se habla de una base inferior, se refiere a una copia de la horma del cuerpo que parte de la cintura hasta el suelo, dicha base, será la plantilla que se adecuará para convertirse en diferentes tipologías según modificaciones de largos, amplitudes, detalles y cortes. Se pueden obtener los básicos de #[em short, capri, jean, bermudas,] entre otros.
        .row.justify-content-center.align-items-center.mb-5(data-aos="zoom-in-left")
          .col-lg-12.col-md-12.col-12
            .fondo211.p-3.mb-2
              .row.justify-content-center.align-items-center
                .col-lg-2
                  img.mx-4.img-a.img-t.d-none.d-lg-block(src="@/assets/curso/tema5/alertaa.svg", alt="tema 5")
                .col-lg-10.col-md-12.col-12         
                  p.my-2 #[b Tener en cuenta:] La base de pantalón sale en plano montado, trazando primero la parte delantera y sobre el delantero, trazando el posterior. Esto se debe a que varias de las medidas curvas y demás son tomadas de la referencia del trazo del delantero.

        p.mb-5 Es importante mencionar que la base de pantalón para la línea femenina se realiza con margen de costura. Aunque es un patrón básico, se trabaja con margen de costura para manejar las variaciones de medida de la forma del cuerpo, por ello es esencial comprender por qué y cómo se aplica el margen de costura para identificar correctamente los contornos por los que pasa el pantalón (cintura, cadera, rodilla y bota).         
    
    .row.justify-content-center.align-items-center
      .col-lg-8.mb-4.mb-lg-0(data-aos="fade-left")
        p.mb-4 Al identificar cada uno de los contornos, se podrían categorizar como contornos completos, cintura y cadera, contornos que deben repetirse o marcarse dos veces sobre el cuerpo, rodilla y bota, esto se debe a la división del cuerpo en las extremidades inferiores. Teniendo en cuenta la introducción anterior, es importante aclarar que en los contornos se identifica aumento de costura por:
        ul.lista-ul--color.mb-4
          li.d-flex
            i.fas.fa-car-side
            p.mb-0.pp Cintura y cadera.
          li.d-flex
            i.fas.fa-car-side
            p.mb-0.pp Centro frente, centro atrás, costado delantero y costado posterior.
          li.d-flex
            i.fas.fa-car-side
            p.mb-0.pp Rodilla y bota.
          li.d-flex
            i.fas.fa-car-side
            p.mb-0.pp Costado delantero, costado posterior, entrepierna delantera y entrepierna posterior.
        p.mb-4 En este caso, para poder trabajar el margen de costura de manera lineal se elabora únicamente con una de las extremidades inferiores, es decir, la mitad del cuerpo, para lograr cubrir el contorno de la pierna sin inconvenientes.
        p La sumatoria de los márgenes de costura depende del tipo de maquinaría y operación que se trabaje en la empresa, sin embargo, el común denominador del margen de costura se asigna de 1 cm, es decir que, si se trabaja cada uno de los puntos de referencia, para asignar margen de costura, quedaría de la siguiente manera:
      .col-lg-4.col-md-8.col-8(data-aos="fade-right")
        img.mb-4(src='@/assets/curso/tema5/img13.png' , alt="tema 5")
    
    
    .row.pert.align-items-center.py-4.py-md-5.mb-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row.justify-content-center.mb-4(data-aos="fade-down")
    
    
        .row.justify-content-center.align-items-center.mb-4 
          .col-sm-12.col-lg-12
            .row.d-flex.justify-content-center
              .col-sm-12.col-lg-4.mt-2
                .tarje.color-primario.my-4.he-4-cus.px-4.my-4.pt-4
                  .row.justify-content-center
                    .col-lg-3
                      img.img-a.img-t.mb-4(src='@/assets/curso/tema5/pan.svg' , alt="tema 5")
                    .col-lg-12  
                      h4.text-center.mb-4 Cintura y cadera
                      p.text-center.mb-2 Centro frente: 1 cm
                      p.text-center.mb-2 +
                      p.text-center.mb-2 Centro atrás: 1 cm
                      p.text-center.mb-2 +
                      p.text-center.mb-2 Costado delantero: 1 cm
                      p.text-center.mb-2 +
                      p.text-center.mb-2 Costado posterior: 1 cm
                      p.text-center.mb-2 =
                      h4.text-center.mb-4 La sumatoria: 4 cm de margen de costura por cintura y cadera 
              .col-sm-12.col-lg-4.mt-2
                .tarjett.color-primario.my-4.he-4-cus.px-4.my-4.pt-4
                  .row.justify-content-center
                    .col-lg-3
                      img.img-a.img-t.mb-4(src='@/assets/curso/tema5/tal.svg' , alt="tema 5")
                    .col-lg-12  
                      h4.text-center.mb-4 Rodilla y bota
                      p.text-center.mb-2 Costado delantero: 1 cm
                      p.text-center.mb-2 +
                      p.text-center.mb-2 Costado posterior: 1 cm
                      p.text-center.mb-2 +
                      p.text-center.mb-2 Entrepierna delantera: 1 cm
                      p.text-center.mb-2 +
                      p.text-center.mb-2 Entrepierna posterior: 1 cm
                      p.text-center.mb-2 =
                      h4.text-center.mb-4 La sumatoria: 4 cm de margen de costura por cintura y cadera
    
    
        p.mb-4 Ya teniendo claro cómo funciona cada uno de los puntos, márgenes de costura y plano del pantalón, lo primero que se debe hacer es el trazo del rectángulo base. Para este rectángulo, se debe trabajar el contorno más protuberante y el largo más largo de las partes que se va a cubrir o en este caso, la intersección entre extremidades inferiores y contornos generales del cuerpo.
        p.mb-4 En los patrones de pantalón femenino dependiendo de la tipología se adecuan ampliaciones, largos y cortes donde dan lugar a la creación de otros básicos que pueden ser utilizados para ser cortados en la tela. Para introducirnos en la comprensión de este tema se recomienda revisar el siguiente material:
        .row.justify-content-center.mb-4(data-aos="zoom-in")
          .col-lg-8.mb-4.mb-lg-0
            .tabla-a.color-acento-contenido.mb-5 
              table
                thead
                  tr
                    th 
                    th Delantero
                    th Posterior
                    th Total
                tbody.tarjeta--gris
                  tr
                    td.text-center Cintura
                    td.text-center 2 cm
                    td.text-center 2 cm
                    td.text-center 4 cm
                  tr
                    td.text-center Cadera
                    td.text-center 1 cm
                    td.text-center 3 cm
                    td.text-center 4 cm
                  tr
                    td.text-center Rodilla Bota
                    td.text-center 0 cm
                    td.text-center 4 cm
                    td.text-center 4 cm
        
        .row.justify-content-center.align-items-center(data-aos="zoom-in-left")
          .col-sm-12.col-lg-10
            .fondo21.p-3.mb-5
              .row.justify-content-around.align-items-center.mb-0
                .col-3.col-sm-2.col-lg-1
                  img.img-a.img-t.mx-3(src="@/assets/curso/tema5/pdff.svg", alt="tema 5")
                .col
                  .row.justify-content-between.align-items-center
                    .col.mb-2.mb-sm-0          
                      h4.mx-4.my-2 Manual de patronaje básico para interpretación de diseños
                      p.mb-0.irr.mx-4 Consulte el “Manual de patronaje básico para interpretación de diseños”. Leer de la página 28 a la 30.
                    .col-sm-auto
                      a.boton.color-acento-botones(:href="obtenerLink('/downloads/Manual_patronaje_básico_interpretacion_diseños.pdf')" target="_blank")
                        span Descargar
                        i.fas.fa-file-download
        
        p.mb-5.text-center También será importante explorar el siguiente video explicativo sobre cómo realizar la base inferior del pantalón femenino.
        
        .row.justify-content-center.align-items-center(data-aos="zoom-in-left")
          .col-sm-12.col-lg-10
            .fondo21.p-3.mb-5
              .row.justify-content-around.align-items-center.mb-0
                .col-3.col-sm-2.col-lg-1
                  img.img-a.img-t.mx-3(src="@/assets/curso/tema5/vide.svg", alt="tema 5")
                .col
                  .row.justify-content-between.align-items-center
                    .col.mb-2.mb-sm-0          
                      h4.mx-4.my-2 Base inferior de pantalón femenino
                      p.mb-0.irr.mx-4 Consulte el video “Base inferior de pantalón femenino”.
                    .col-sm-auto
                      a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=k0-m6ftaKts" target="_blank")
                        span Ir al sitio
                        i.fas.fa-video
    
    .mb-4.d-flex.mb-5
      .d-flex.flex-wrap.align-items-center.pe-4.bg-img-blue
        h5.col.px-4.mb-0.text-white.mx-5(data-aos="fade-right") Variantes de pantalón femenino
        img.clase2(src='@/assets/curso/tema3/vot.svg' data-aos="fade-left") 

    p.mb-4 Según modificaciones de largos, amplitudes, detalles y cortes. Se pueden obtener los básicos inferiores. Las medidas de largos se deben tomar desde la cintura hasta el punto de la pierna que lo sugiera el diseño.
    p.mb-5 En los siguientes recursos podremos apreciar las diferentes variantes del pantalón femenino: 
    
    
    .row.fondo5.justify-content-center.align-items-center.py-0.mb-5
      .col-sm-12.col-lg-12.px-lg-5.px-4
        .row.justify-content-center.mb-0(data-aos="fade-down")
        
          .row.justify-content-center.align-items-center.mb-2
              .col-sm-12.col-lg-12
                .row.d-flex.justify-content-center
                  .col-sm-12.col-lg-5.mt-2
                    .tarje.color-primario.my-4.he-4-cus.px-4.my-4.pt-4
                      .row.justify-content-center
                        .titulo-sexto.color-acento-contenido
                          h5 Figura 15. 
                          | Tipologia de pantalon segun largo
                        img.mb-4(src='@/assets/curso/tema5/img14.png' , alt="Molde de pantalón con marcas punteadas dependiendo de estilo o diseño que se necesite según las variantes del pantalón femenino: Capri, toreador, bermuda, etc.")
                        figcaption.text-black Fuente: SENA, 2021
          
          .row.justify-content-center.align-items-center.mb-0(data-aos="fade-down")
            .col-sm-12.col-lg-3
              img.img-a.img-t.d-none.d-lg-block.mt-3(src='@/assets/curso/tema5/imgcinco.svg', alt="tema 5")
            .col-lg-4.col-md-8.col-12.mb-4.my-5
              .fondo21e
                .row.justify-content-center.align-items-center.mb-4
                  .col-lg-11.col-md-11.col-11
                    img.img-a.img-t.mt-4(src='@/assets/curso/tema5/vide.svg', alt="tema 5")
                    h4.text-center.mt-4 Interpretación de prendas de vestir
                    p.mb-5.my-4 Consulte el video “Interpretación de prendas inferiores”.
                    .row.justify-content-center.align-items-center
                      .col-sm-auto
                        a.boton.color-acento-botones.my-0(href="https://www.youtube.com/watch?v=fkHL3e5EOPI" target="_blank")
                          span Ir al sitio
                          i.fas.fa-video    
                
            .col-lg-4.col-md-8.col-12.mb-4.my-5
              .fondo21e
                .row.justify-content-center.align-items-center.mb-4
                  .col-lg-11.col-md-11.col-11
                    img.img-a.img-t.mt-4(src='@/assets/curso/tema5/vide.svg', alt="tema 5")
                    h4.text-center.mt-4 Análisis e interpretación de pantalón y sudadera
                    p.mb-3 Consulte el video “Análisis e interpretación de pantalón sudadera”.
                    .row.justify-content-center.align-items-center
                      .col-sm-auto
                        a.boton.color-acento-botones.my-4(href="https://www.youtube.com/watch?v=8vgwqHz6Qio" target="_blank")
                          span Ir al sitio
                          i.fas.fa-video
            .col-lg-1.col-md-8.col-12.mb-4.my-5
            
            

    separador
    #t_5_4.titulo-segundo
      .h2 5.4 Mangas
    
    .row.justify-content-center.align-items-center.mb-2
      .col-lg-4.col-md-10.col-10.mb-4.mb-lg-0(data-aos="fade-left")
        img.img-a.img-t.mb-4(src='@/assets/curso/tema5/5.4.png', alt="tema 5")
      .col-lg-8.mb-4.mb-lg-0(data-aos="fade-right")
        p.mb-3 En el patronaje, las mangas van conectadas no solo al tamaño de los brazos sino también a la postura de la persona, estos son factores que se deben tener en cuenta desde el análisis antropométrico.
        p.mb-3 Cuando se habla de manga, básicamente se entiende o identifica como una pieza circular que cubre el brazo, sin embargo, existen diferentes tipos de puntos a tener en cuenta:
        ul.lista-ul--color.mb-0
          li.d-flex
            i.fas.fa-car-side
            p
              strong Largo de manga: 
              | el largo de manga anatómico es aquel que va desde el punto de acromio hasta la muñeca, se debe tener en cuenta que, sin importar el diseño, largo o forma del cuerpo de la manga, siempre se debe partir desde el largo anatómico.
          li.d-flex
            i.fas.fa-car-side
            p
              strong Altura o cabeza de manga: 
              | cuando se habla de cabeza de manga, se identifican diferentes tipos de medidas, se puede trabajar con medida de cuadro de tallas, medida deducida o estandarizada.
      
    
    .row.justify-content-center.align-items-center.mb-4(data-aos="zoom-in-left")
      .col-lg-6.col-md-12.col-12
        .fondo211.p-3.mb-4
          .row.justify-content-center.align-items-center
            .col-lg-2
              img.mx-4.img-a.img-t.d-none.d-lg-block(src="@/assets/curso/tema5/alertaa.svg", alt="tema 5")
            .col-lg-10.col-md-12.col-12         
              p.my-2 #[b Tener en cuenta:] que el largo de manga siempre será el mismo, sin importar que tipo de prenda o cabeza de manga se implemente.

        p.mb-4 En el desarrollo de curvas y trazos en las cabezas de manga existen varias formas de trazarlas, las implementadas y guiadas en el vídeo que se presenta a continuación, hace referencia a un acercamiento general de todos los trazos del manual.
        p.mb-4 #[b Medidas]
        ul.lista-ul--color.mb-4
          li.d-flex
            i.fas.fa-car-side
            | Recorrido sisa delantera (medidas que salen del plano).
          li.d-flex
            i.fas.fa-car-side
            | Recorrido sisa posterior (medidas que salen del plano).
          li.d-flex
            i.fas.fa-car-side
            | Tipo de cabeza de manga.
          li.d-flex
            i.fas.fa-car-side
            | Largo de manga.
      .col-lg-4.col-md-8.col-8(data-aos="fade-right")
        img.mb-4(src='@/assets/curso/tema5/555.png' , alt="tema 5")
    
    .row.justify-content-center.align-items-center.mb-4
      .col-lg-4.col-md-8.col-12.mb-4
        p Apreciemos el paso a paso para conocer el trazo de manga y cabezas de manga. 
        .fondo21e
          .row.justify-content-center.align-items-center.mb-4
            .col-lg-11.col-md-11.col-11
              img.img-a.img-t.mt-4(src='@/assets/curso/tema5/vide.svg', alt="tema 5")
              h4.text-center.mt-4 Trazo de manga y cabezas de manga
              p.mb-5.my-3 Consulte el video “Trazo de manga y cabezas de manga”.
              .row.justify-content-center.align-items-center
                .col-sm-auto
                  a.boton.color-acento-botones.my-2(href="https://www.youtube.com/watch?v=bOKMgtgSzM4" target="_blank")
                    span Ir al sitio
                    i.fas.fa-video
      
      .col-lg-4.col-md-8.col-12.mb-4
        p Otras formas para sacar o deducir la altura de cabeza de manga, se pueden estudiar en el documento:
        .fondo21e
          .row.justify-content-center.align-items-center.mb-4
            .col-lg-11.col-md-11.col-11
              img.img-a.img-t.mt-3(src='@/assets/curso/tema5/pdff.svg', alt="tema 5")
              h4.text-center.mt-4 Manual de patronaje básico para interpretación de diseños
              p.mb-2.my-3 Consulte el anexo “Manual de patronaje básico para interpretación de diseños”. Leer de la página 26 a 44.
              .row.justify-content-center.align-items-center
                .col-sm-auto
                  a.boton.color-acento-botones.my-1(:href="obtenerLink('/downloads/Manual_patronaje_básico_interpretacion_diseños.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download

    p.mb-5.text-center También será muy importante conocer y comprender la diversidad asociada a la interpretación de las mangas, de tal manera que se puedan implementar las variaciones de acuerdo a las necesidades de cada prenda a confeccionar:
    
    .row.justify-content-center.align-items-center.mb-4
      .col-lg-4.col-md-8.col-12.mb-4
        .fondo21e
          .row.justify-content-center.align-items-center.mb-4
            .col-lg-11.col-md-11.col-11
              img.img-a.img-t.mt-4(src='@/assets/curso/tema5/vide.svg', alt="tema 5")
              h4.text-center.mt-4 Interpretación de mangas
              p.mb-5.my-3 Consulte el video “Interpretación de mangas”.
              .row.justify-content-center.align-items-center
                .col-sm-auto
                  a.boton.color-acento-botones.my-4(href="https://www.youtube.com/watch?v=jAAy_cQfRok" target="_blank")
                    span Ir al sitio
                    i.fas.fa-video
      
      .col-lg-4.col-md-8.col-12.mb-4
        .fondo21e
          .row.justify-content-center.align-items-center.mb-4
            .col-lg-11.col-md-11.col-11
              img.img-a.img-t.mt-4(src='@/assets/curso/tema5/vide.svg', alt="tema 5")
              h4.text-center.mt-3 Generalidades de la manga kimono y ranglan
              p.mb-4 Consulte el video “Generalidades de manga kimono y ranglan”.
              .row.justify-content-center.align-items-center
                .col-sm-auto
                  a.boton.color-acento-botones.my-3(href="https://www.youtube.com/watch?v=bsxn_w-kS5Y" target="_blank")
                    span Ir al sitio
                    i.fas.fa-video

      .col-lg-4.col-md-8.col-12.mb-4
        .fondo21e
          .row.justify-content-center.align-items-center.mb-4
            .col-lg-11.col-md-11.col-11
              img.img-a.img-t.mt-4(src='@/assets/curso/tema5/pdff.svg', alt="tema 5")
              h4.text-center.mt-4 Manga Kimono
              p.mb-2.my-3 Consulte el anexo “Manga Kimono”. Leer página 48 y manga ranglan formal e informal. Leer páginas 49 y 50.
              .row.justify-content-center.align-items-center
                .col-sm-auto
                  a.boton.color-acento-botones.my-2(:href="obtenerLink('/downloads/Manual_patronaje_básico_interpretacion_diseños.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download

    
    p.mb-5.text-center Para finalizar este tema abordaremos la interpretación de prendas, con la finalidad de cerrar el análisis de la composición del patronaje básico para la línea femenina. En los siguientes 4 videos mostraremos los aspectos más importantes a tener en cuenta en este proceso:
    
    .row.justify-content-center.align-items-center(data-aos="zoom-in-left")
      .col-sm-12.col-lg-10
        .fondo21.p-3.mb-4
          .row.justify-content-around.align-items-center.mb-4
            .col-3.col-sm-2.col-lg-1
              img.img-a.img-t(src="@/assets/curso/tema2/video.svg", alt="tema 5")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-2.mb-sm-0          
                  h4 Análisis e interpretación de capas
                  p.mb-0.irr Consulte el video “Análisis e interpretación de capas”.
                .col-sm-auto
                  a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=N-2DugIICpw" target="_blank")
                    span Ir al sitio
                    i.fas.fa-video
          .hr.mb-3
          .row.justify-content-around.align-items-center.mb-4
            .col-3.col-sm-2.col-lg-1
              img.img-a.img-t(src="@/assets/curso/tema2/video.svg", alt="tema 5")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0          
                  h4 Abrigo asimétrico
                  p.mb-0.irr Consulte el video “Abrigo asimétrico”.
                .col-sm-auto
                  a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=aga8T_qGAFs" target="_blank")
                    span Ir al sitio
                    i.fas.fa-video 
          .hr.mb-3
          .row.justify-content-around.align-items-center.mb-4
            .col-3.col-sm-2.col-lg-1
              img.img-a.img-t(src="@/assets/curso/tema2/video.svg", alt="tema 5")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0          
                  h4 Interpretación de pantalón sastre femenino
                  p.mb-0.irr Consulte el video “Interpretación de pantalón sastre femenino”.
                .col-sm-auto
                  a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=VZZQsjRcc7k" target="_blank")
                    span Ir al sitio
                    i.fas.fa-video
          .hr.mb-3
          .row.justify-content-around.align-items-center.mb-1
            .col-3.col-sm-2.col-lg-1
              img.img-a.img-t(src="@/assets/curso/tema5/vide.svg", alt="tema 5")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0          
                  h4 Análisis e interpretación de pantalón sudadera
                  p.mb-0.irr Consulte el video “Análisis e interpretación de pantalón sudadera”.
                .col-sm-auto
                  a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=8vgwqHz6Qio" target="_blank")
                    span Ir al sitio
                    i.fas.fa-video

</template>

<script>
export default {
  name: 'Tema5',
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
