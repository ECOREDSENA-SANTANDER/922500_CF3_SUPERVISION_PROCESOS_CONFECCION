<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 5
      h1 Patronaje femenino
    
    .row.mb-4
      .col-md-6.mb-4.mb-md-0
        p.mb-4 Para el desarrollo y construcción del patronaje de prendas de vestir para la línea femenina, se trabajará una serie de conceptos y técnicas en la elaboración de bases y básicos, por medio de la aplicación de las medidas anatómicas y el manejo de incremento entre tallas, por medio del escalado.  Las bases en patronaje son el calco del cuerpo para prendas superiores e inferiores, estos patrones no pueden ser utilizados para ser cortados de forma inmediata en tela o utilizados para elaborar una prenda, ya que antes deben recibir adaptaciones (desahogos, amplitudes, cortes y otros) para proceder a ser utilizados en producción. De la calidad del mismo dependerá la estabilidad dimensional del patrón y el buen calce de la prenda una vez confeccionada.
        .cajon.color-acento-contenido.p-4
          p Los patrones bases o básicos se crean según el tipo de prenda, como se observa en la siguiente figura:
      .col-md-6.mb-4.mb-md-0
        .row.justify-content-center.mb-4
          .col-8
            .titulo-sexto.color-acento-contenido
              h5 Figura 8. 
              | División moldes según tipo de prenda
            img(src='@/assets/curso/tema5/img01.svg')
    
    separador
    #t_5_1.titulo-segundo
      .h4 5.1 Trazo de falda

    .row.justify-content-center.mb-5
      .col-lg-10.mb-4.mb-md-0
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema5/img02.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Para comenzar el proceso en construcción de moldes, se recomienda partir con patrones o levantamientos más simples; de tal manera que sea fácil comprender el sistema que se desarrollará en este esquema. La falda básica es el primer estilo, porque es la prenda más simple. A través de estas líneas, se asimila la utilización correcta de cada regla de costura, obteniendo así una mayor seguridad para manejar los siguientes estilos.
            p Medidas a utilizar para el trazo de la falda: contorno de cintura, contorno de cadera y largo de falda.
    
    .h5.mb-4 Trazado de la falda básica

    .row.justify-content-center.mb-4
      .col-lg-10.mb-4.mb-md-0
        .cajon.color-acento-contenido.p-4
          p Analizar la tipología de la falda a desarrollar es importante para determinar qué medida de largo se necesita para generar el rectángulo de inicio y luego el levantamiento del molde; para lo cual también será importante conocer los siguientes aspectos:

    .row.mb-5
      .col-lg-6.d-flex.mb-4.mb-md-0
        .tarjeta.color-secundario.p-4
          .row.justify-content-center
            .col-lg-9.mb-4.mb-md-0
              .h1.text-white.text-center.mb-5  Longitud de las faldas
              p.text-white.text-center.mb-5 La longitud de la falda puede ser variada: minifalda, maxi falda, hasta la rodilla y hasta el suelo.
              .h5.text-white.text-center.mb-4  Figura 9. Longitud de la falda
          figure.mb-4
            img(src='@/assets/curso/tema5/img03.png')
            figcaption.text-black Fuente: SENA, 2021

      .col-lg-6.mb-4.mb-md-0
        .tarjeta.color-acento-contenido.p-4
          .row.justify-content-center
            .col-lg-9.mb-4.mb-md-0
              .h1.text-white.text-center.mb-4  La circunferencia de la cintura
              p.text-white.text-center.mb-4  La circunferencia de la cintura puede ser tan baja como por debajo del ombligo y tan alta como por encima de la cintura.
              .h5.text-white.text-center.mb-4  Figura 10. Circunferencia de la cintura
          figure.mb-4
            img(src='@/assets/curso/tema5/img04.png')
            figcaption.text-black Fuente: SENA, 2021

    p.mb-4.text-white .
    .row.justify-content-center.mb-4
      .col-lg-7.mb-4.mb-md-0
        strong.mb-4 Trazado de la falda básica: 
        | como punto de partida se deben tomar las medidas anatómicas con precisión. No deben sumar centímetros de más, por ello se recomienda seguir con atención los pasos del manual de patronaje básico e interpretación de diseños que se relaciona a continuación, pues el básico inferior de falda, siempre se trabaja partiendo desde un rectángulo e identificando los siguientes puntos:
        ul.lista-ul--color
          li 
            i.fas.fa-atom 
            | Parte superior (cintura) – línea superior.
          li 
            i.fas.fa-atom 
            | Parte inferior (rodilla) – línea inferior.
          li 
            i.fas.fa-atom 
            | Parte derecha – posterior.
          li 
            i.fas.fa-atom 
            | Parte izquierda – delantero.
        p.mb-4 Para profundizar en estos aspectos será importante revisar el material:
        .row.justify-content-center.mb-4
          .col-lg-7.mb-4.mb-md-0
            a.anexo.mb-4.mb-lg-0(href="https://repositorio.sena.edu.co/bitstream/handle/11404/4725/Manual_patronaje_basico_interpretacion_disenos.PDF;jsessionid=B929C4B6338D41F855E80661E0B9A970?sequence=1" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                strong Anexo. 
                | Manual de patronaje básico e interpretación de diseños Conocimiento de los puntos de referencia para el trazado de las faldas. Leer de la página 15 a 17.
          .col-lg-5.mb-4.mb-md-0
            a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=wl5EjrLU-8Y&ab_channel=RedProducci%C3%B3ndeContenidosGrupoGesti%C3%B3nCurricularSENA" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-link.svg")
              .anexo__texto
                strong Enlace web. 
                | Video - Base inferior falda femenino
        .row.justify-content-center.mb-4
          .col-lg-7.mb-4.mb-md-0
            a.anexo.mb-4.mb-lg-0(href="https://repositorio.sena.edu.co/bitstream/handle/11404/4725/Manual_patronaje_basico_interpretacion_disenos.PDF;jsessionid=B929C4B6338D41F855E80661E0B9A970?sequence=1" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                strong Anexo. 
                | Manual de patronaje básico e interpretación de diseños Conocimientos básicos para hacer base falda a una pinza y base falda a dos pinzas en escala. Leer de la página 31 a 32.
          .col-lg-5.mb-4.mb-md-0
            a.anexo.mb-4(:href="obtenerLink('/downloads/Anexo_4_Pasos_falda_basica.pdf')" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                strong Anexo. 
                | Pasos para falda básica
      .col-lg-5.mb-4.mb-md-0
        img(src='@/assets/curso/tema5/img05.png')
    
    p.mb-4 En el siguiente repositorio de podrá encontrar información asociada a las variaciones de la falda, en donde se tienen en cuenta las diversas posibilidades de variación en los patrones de esta prenda:

    .row.justify-content-center.mb-4
      .col-lg-4.mb-4.mb-md-0
        a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=NxZQL369p9Q&t=918s&ab_channel=RedProducci%C3%B3ndeContenidosGrupoGesti%C3%B3nCurricularSENA" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg")
          .anexo__texto
            strong Enlace web. 
            | Trazo de faldas rotondas
      .col-lg-4.mb-4.mb-md-0
        a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?app=desktop&v=xtyPQh3vtuc&ab_channel=RedProducci%C3%B3ndeContenidosGrupoGesti%C3%B3nCurricularSENA" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg")
          .anexo__texto
            strong Enlace web. 
            | Modificación de básicos de falda
      .col-lg-4.mb-4.mb-md-0
        a.anexo.mb-4.mb-lg-0(href="https://repositorio.sena.edu.co/bitstream/handle/11404/4725/Manual_patronaje_basico_interpretacion_disenos.PDF;jsessionid=B929C4B6338D41F855E80661E0B9A970?sequence=1" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg")
          .anexo__texto
            strong Enlace web. 
            | Manual de interpretación de diseño/Diseños de faldas: leer páginas 33 a 38

    separador
    #t_5_2.titulo-segundo
      .h4 5.2 Trazo de base superior femenina
    
    .bloque-texto-a.color-acento-contenido.p-4.p-md-0.mb-5 
      .row.m-0.align-items-center
        .col-lg-7.mb-4.mb-lg-0
          p.mb-0 El manejo de volúmenes es uno de los principales factores diferenciadores en el desarrollo de prendas, estos se consiguen por medio de las pinzas y sistemas de ajustes, los cuales se deben tener en cuenta que, sin importar la línea que se trabaje, la metodología del manual y los pasos, siempre serán los mismos; este orden secuencial le permite tener una mayor y mejor apropiación de la metodología.
        .col-lg-5
          img(src='@/assets/curso/tema5/img06.svg')
      
    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--gris")
      .row.justify-content-center(titulo="Volumen de la prenda")
        .col-md-3.mb-4.mb-md-0
          img(src='@/assets/curso/tema5/img06.svg')
        .col-md-7
          p.mb-4 Existen prendas más grandes que el cuerpo, iguales o más pequeñas como las elaboradas en tejidos de punto o con telas licradas. La diferencia entre la prenda y el cuerpo que visten recibe el nombre de desahogo, el mayor o menor desahogo condiciona el volumen de la prenda. El desahogo de una prenda debe mantenerse constante en todas las tallas del mismo diseño.
          p.mb-4 A continuación, se muestran los valores de desahogo (en centímetros) estimados según el tipo de prenda y volumen deseado:
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
                    td.text-center Blusa
                    td.text-center 8
                    td.text-center 10
                    td.text-center 12
                    td.text-center 14
                    td.text-center 16
            p.mb-4 En función al volumen del tejido, los anteriores valores pueden ser ajustados de la siguiente manera, y son aplicados al contorno.
            .row.m-0.justify-content-center
              .col-lg-10.mb-4.mb-lg-0
                .tabla-a.color-acento-contenido.mb-5 
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

      .row.justify-content-center(titulo="Pasos para el trazo de la base superior")
        .col-lg-10.mb-4.mb-lg-0
          p.mb-4 Cuando se habla de la base superior, se hace referencia a la copia de la horma del cuerpo partiendo del cuello hasta la cintura, dicha base será la plantilla que se adecuará para convertirse en blusa, camiseta, chaqueta, chaleco, corpiño y demás prendas femeninas, incluyendo el vestido.
          p.mb-4 Conozca el paso a paso para la elaboración de estos patrones revisando los siguientes recursos:
          .row.justify-content-center.mb-5
            .col-lg-4.mb-4.mb-lg-0
              a.anexo.mb-4.mb-lg-0(href="https://repositorio.sena.edu.co/bitstream/handle/11404/4725/Manual_patronaje_basico_interpretacion_disenos.PDF;jsessionid=B929C4B6338D41F855E80661E0B9A970?sequence=1" target="_blank")
                .anexo__icono
                  img(src="@/assets/template/icono-pdf.svg")
                .anexo__texto
                  strong Anexo. 
                  | PDF - Manual de patronaje básico e interpretación de diseños Conocimiento para hace patrón base superior femenino. Leer de la página 20 a 25.
            .col-lg-4.mb-4.mb-lg-0
              a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=56vyEeZhA-I&ab_channel=RedProducci%C3%B3ndeContenidosGrupoGesti%C3%B3nCurricularSENA" target="_blank")
                .anexo__icono
                  img(src="@/assets/template/icono-link.svg")
                .anexo__texto
                  strong Enlace web. 
                  | Trazo de falda y modificación de básicos de falda Ver video explicativo sobre cómo realizar la base superior femenina.
            .col-lg-4.mb-4.mb-lg-0
              a.anexo.mb-4(:href="obtenerLink('/downloads/Anexo_5_Pasos_para_el_trazo_de_la_base_superior.pdf')" target="_blank")
                .anexo__icono
                  img(src="@/assets/template/icono-pdf.svg")
                .anexo__texto
                  strong Anexo. 
                  | Pasos para el trazo de la base superior

      .row.justify-content-center(titulo="Pinza correctiva de talle")
        .col-lg-10.mb-4.mb-lg-0
          p.mb-4 En el momento que se unen los básicos delantero y posterior por la línea de la cintura, se evidencia el desnivel anatómico entre estos, es de aquí que surge esta pinza como una marca de referencia principal, para generar volúmenes o ajustes sobre el cuerpo. Permite ser trasladada o llevada a diferentes puntos del cuerpo, permitiendo así acentuar volúmenes, generar siluetas o estructuras que permiten modificar diseños. Según la interpretación queda invisible o visible a propósito.
          ul.lista-ul--color.mb-4
            li 
              i.fas.fa-atom 
              | Las pinzas pueden ser transferidas o desviadas a cualquier dirección alrededor del punto de busto (punto giratorio) sin afectar el tamaño ni entalle del patrón.
            li 
              i.fas.fa-atom 
              | El exceso de la pinza, es decir, el espacio entre lados de la pinza puede ser utilizado como recogidos, pliegues, pinzas semi cosidas o en los cortes de diferentes estilos o diseños.
          .row.justify-content-center
            .col-lg-10.mb-4.mb-lg-0 
              .cajon.color-primario.p-4.mb-4
                .row.align-items-center
                  .col-lg-2.mb-4.mb-lg-0
                    img(src='@/assets/curso/tema5/img08.svg')
                  .col-lg-8.mb-4.mb-lg-0
                    strong Tener en cuenta: 
                    |  todas las pinzas deben terminar antes del punto de busto (punto giratorio), nunca deben traspasar dicho punto.
              
          .h5.mb-4 Técnicas de transformación
            p.mb-4 Estas técnicas hacen referencia a métodos que permiten el desplazamiento de las pinzas y su reubicación. Veamos las dos más utilizadas:
            ol.lista-ol--cuadro.lista-ol--separador
              li 
                .lista-ol--cuadro__vineta
                  span 1
                p 
                  strong Cortar y unir: 
                  | este método requiere cortar el patrón base para luego unir las partes con la reubicación de la pinza.
              li 
                .lista-ol--cuadro__vineta
                  span 2
                p
                  strong 2.	Pivoteo (girar): 
                  | este método no requiere cortar el patrón básico, sino girarlo a través del punto de busto transfiriendo de esta manera la pinza.
            .row.justify-content-center.mb-4
              .col-lg-6.mb-4.mb-lg-0 
                p.mb-4 Los puntos en que se hace posible el traslado de la pinza son los siguientes:
              .col-lg-6.mb-4.mb-lg-0 
                p.mb-4 A continuación, se observa la transformación que sufre el patrón de acuerdo a la técnica aplicada y la necesidad de la prenda.
              .col-lg-6.d-flex.mb-4.mb-lg-0 
                .cajon.color-primario.p-4
                  .titulo-sexto.color-acento-contenido
                    h5 Figura 11.
                    | Puntos de traslados de pinza
                  figure
                    img(src='@/assets/curso/tema5/img09.png')
                    figcaption Fuente: Adaptado de: SENA, 2021
              .col-lg-6.mb-4.mb-lg-0 
                .cajon.color-primario.p-4
                  .titulo-sexto.color-acento-contenido
                    h5 Figura 12.
                    | Traslados de pinza en base
                  .row.justify-content-center
                    .col-lg-9.mb-4.mb-lg-0 
                      figure
                        img(src='@/assets/curso/tema5/img10.png')
                        figcaption Fuente: SENA, 2021
            p.mb-4 Para comprender este proceso podrá ver el video explicativo sobre cómo se hacen traslados de pinza correcta de talles.
            .row
              .col-lg-7.mb-4.mb-lg-0 
              .col-lg-5.mb-4.mb-lg-0 
                a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=encNXGtE15Y&ab_channel=RedProducci%C3%B3ndeContenidosGrupoGesti%C3%B3nCurricularSENA" target="_blank")
                  .anexo__icono
                    img(src="@/assets/template/icono-link.svg")
                  .anexo__texto
                    strong Enlace web. 
                    | Video - Base inferior falda femenino

      .row.justify-content-center(titulo="Análisis y trazo de sistema de ajuste. (Pinzas y cortes)")
        .col-lg-10.mb-4.mb-lg-0
          p.mb-4 Dentro del desarrollo de moldes y patrones, se hace indispensable el manejo de pinzas, como sistema de ajuste o como insumo principal para el manejo de volúmenes, las pinzas en femenino son un punto de partida primordial y específico, el cual es necesario comprender desde la base funcional estructural y matemática.
          p.mb-4 Para comprender el funcionamiento de las pinzas, se trabajará únicamente la parte superior femenina, contemplando la circunferencia y el volumen del busto, de igual manera el contorno de cintura y el contorno de cadera, cada uno de estos contornos maneja características como volúmenes más protuberantes de los tops o los bottoms y punto unión o encuentro entre la división del cuerpo.
          p.mb-4 En el manejo de pinzas únicamente se trabajará con los contornos relevantes o que se toman como punto de partida para la construcción de básicos (contorno de busto – contorno de cintura – contorno de cadera).
          p.mb-4 Sin importar el tipo de prenda, los desahogos o la interpretación, las pinzas como sistema de ajuste siempre se trabajarán sobre esos contornos, debido a que son los contornos con los que se trabaja la base o el básico. Veamos un video explicativo sobre cómo se hace el trazo de sistemas de ajuste de pinzas y cortes.
          .row.justify-content-center.mb-4
            .col-lg-7.mb-4.mb-lg-0 
            .col-lg-5.mb-4.mb-lg-0 
              a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=Tq_3F32nynw&t=1759s&ab_channel=RedProducci%C3%B3ndeContenidosGrupoGesti%C3%B3nCurricularSENA" target="_blank")
                .anexo__icono
                  img(src="@/assets/template/icono-link.svg")
                .anexo__texto
                  strong Enlace web. 
                  | Análisis y trazo de sistema de ajuste pinzas y cortes
          p.mb-4 A continuación, se presentan las variaciones posibles que presenta la prenda superior femenina; para lo cual, los invitamos a revisar los siguientes contenidos:
          .row.justify-content-center
            .col-lg-11.mb-4.mb-lg-0
              .row.justify-content-center.mb-4
                .col-lg-4.mb-4.mb-lg-0
                  a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=euVdaqaTQlY&t=1523s&ab_channel=RedProducci%C3%B3ndeContenidosGrupoGesti%C3%B3nCurricularSENA" target="_blank")
                    .anexo__icono
                      img(src="@/assets/template/icono-link.svg")
                    .anexo__texto
                      strong Enlace web. 
                      | Trazo básico blusa
                .col-lg-4.mb-4.mb-lg-0
                  a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=euVdaqaTQlY&t=1523s&ab_channel=RedProducci%C3%B3ndeContenidosGrupoGesti%C3%B3nCurricularSENA" target="_blank")
                    .anexo__icono
                      img(src="@/assets/template/icono-link.svg")
                    .anexo__texto
                      strong Enlace web. 
                      | Trazo blusa con almilla y cuello camisero
                .col-lg-4.mb-4.mb-lg-0
                  a.anexo.mb-4(:href="obtenerLink('/downloads/Anexo_6_Piezas_complementarias.pdf')" target="_blank")
                    .anexo__icono
                      img(src="@/assets/template/icono-pdf.svg")
                    .anexo__texto
                      strong Anexo. 
                      | Piezas complementarias
          .row.justify-content-center.mb-4
            .col-lg-10.mb-4.mb-lg-0
              .cajon.color-primario.p-4.mb-4
                .row
                  .col-lg-2.mb-4.mb-lg-0
                    img(src='@/assets/curso/tema5/img08.svg')
                  .col-lg-8.mb-4.mb-lg-0
                    .h4.mb-4 Para tener en cuenta
                    ul.lista-ul--color
                      li 
                        i.fas.fa-atom 
                        | Después de su construcción, se aplican desahogos, traslado de pinza correctiva de talle, sistema de cierre y complementos de diseño (almillas, bolsillo de parche).
                      li 
                        i.fas.fa-atom 
                        | Para el trazo del plano desde los básicos se debe iniciar trazando una línea de referencia, en el caso de las bases superiores, se traza una línea de manera horizontal en el papel, sobre la cual quedará alineados o aplomados desde la línea base de construcción, en prendas superiores, la línea de aplome o línea base será la línea de profundidad de sisa.
          p.mb-4 A continuación, se presentan las variaciones de los patrones básicos para el vestido:
          .row.justify-content-center
            .col-lg-11.mb-4.mb-lg-0
              .row.justify-content-center.mb-4
                .col-lg-4.mb-4.mb-lg-0
                  a.anexo.mb-4.mb-lg-0(href="https://repositorio.sena.edu.co/bitstream/handle/11404/4725/Manual_patronaje_basico_interpretacion_disenos.PDF;jsessionid=33AD41E34F0FE51C537763C6774D3963?sequence=1" target="_blank")
                    .anexo__icono
                      img(src="@/assets/template/icono-pdf.svg")
                    .anexo__texto
                      strong Anexo. 
                      | Variación del vestido. Leer páginas 59 a 62
                .col-lg-4.mb-4.mb-lg-0
                  a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?app=desktop&v=JnFLa4-gUa4&t=187s&ab_channel=RedProducci%C3%B3ndeContenidosGrupoGesti%C3%B3nCurricularSENA" target="_blank")
                    .anexo__icono
                      img(src="@/assets/template/icono-link.svg")
                    .anexo__texto
                      strong Enlace web. 
                      | Trazo de la Bata o vestido
                .col-lg-4.mb-4.mb-lg-0
                  a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=xjSPGOWXJw0&t=1499s&ab_channel=RedProducci%C3%B3ndeContenidosGrupoGesti%C3%B3nCurricularSENA" target="_blank")
                    .anexo__icono
                      img(src="@/assets/template/icono-link.svg")
                    .anexo__texto
                      strong Enlace web. 
                      | Escotes, cuellos y solapas

    separador
    #t_5_3.titulo-segundo
      .h4 5.3 El pantalón femenino y sus variantes

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-8.mb-4.mb-lg-0 
        p.mb-4 Cuando se habla de una base inferior, se refiere a una copia de la horma del cuerpo que parte de la cintura hasta el suelo, dicha base, será la plantilla que se adecuará para convertirse en diferentes tipologías según modificaciones de largos, amplitudes, detalles y cortes. Se pueden obtener los básicos de short, capri, jean, bermudas, entre otros.
        .cajon.color-primario.p-4.mb-4
          .row
            .col-lg-2.mb-4.mb-lg-0
              img(src='@/assets/curso/tema5/img08.svg')
            .col-lg-8.mb-4.mb-lg-0
              .h4.mb-4 Tener en cuenta
              p La base del pantalón sale en plano montado trazando primero la parte delantera y sobre el delantero trazando el posterior. Esto se debe a que varias de las medidas curvas y demás son tomadas de la referencia del trazo del delantero.
        p La base de pantalón para la línea femenina sale con margen de costura. En este caso, aunque es un básico se trabaja con margen de costura, con el fin de manejar los desniveles de medida para la horma, el caso está en diferenciar y entender por qué y cómo del margen de costura. Para lograr identificar o entender el margen de costura, es necesario identificar los contornos por los que va pasando el pantalón (contorno de cintura, contorno de cadera, contorno de rodilla y contorno de bota).
      .col-lg-4.mb-4.mb-lg-0
        img(src='@/assets/curso/tema5/img12.png')
    
    .row.justify-content-center.align-items-center.mb-4
      .col-lg-4.mb-4.mb-lg-0
        img(src='@/assets/curso/tema5/img13.svg')
      .col-lg-8.mb-4.mb-lg-0
        p.mb-4 Al identificar cada uno de los contornos, se podrían categorizar como contornos completos, cintura y cadera, contornos que deben repetirse o marcarse dos veces sobre el cuerpo, rodilla y bota, esto se debe a la división del cuerpo en las extremidades inferiores. Teniendo en cuenta la introducción anterior, es importante aclarar que en los contornos se identifica aumento de costura por:
        ul.lista-ul--color
          li 
            i.fas.fa-atom 
            | Cintura y cadera.
          li 
            i.fas.fa-atom 
            | Centro frente, centro atrás, costado delantero y costado posterior.
          li 
            i.fas.fa-atom 
            | Rodilla y bota.
          li 
            i.fas.fa-atom 
            | Costado delantero, costado posterior, entrepierna delantera y entrepierna posterior.
        p En este caso, para poder trabajar el margen de costura de manera lineal se elabora únicamente con una de las extremidades inferiores, es decir, la mitad del cuerpo, para lograr cubrir el contorno de la pierna sin inconvenientes.

    p.mb-4 La sumatoria de los márgenes de costura depende del tipo de maquinaría y operación que se trabaje en la empresa, sin embargo, el común denominador del margen de costura se asigna de 1 cm, es decir que, si se trabaja cada uno de los puntos de referencia, para asignar margen de costura, quedaría de la siguiente manera:

    .row.justify-content-center.mb-4
      .col-lg-10.mb-4.mb-lg-0
        .row.justify-content-between
          .col-lg-5.mb-4.mb-lg-0
            .cajon.color-acento-contenido.p-4
              .row
                .h4.text-center.mb-4 Cintura y Cadera
                .col-6
                  p Centro frente:
                  p + Centro atrás:
                  p + Costado delantero:
                  p + Costado posterior:
                  p = La sumatoria:
                .col-6
                  p 1 cm
                  p 1 cm
                  p 1 cm
                  p 1 cm
                  p 4 cm de margen de costura por cintura y cadera
          .col-lg-5.mb-4.mb-lg-0
            .cajon.color-acento-contenido.p-4
              .row
                .h4.text-center.mb-4 Rodilla y Bota
                .col-6
                  p Costado delantero:
                  p + Costado posterior:
                  p + Entrepierna delantera:
                  p + Entrepierna posterior:
                  p = La sumatoria:
                .col-6
                  p 1 cm
                  p 1 cm
                  p 1 cm
                  p 1 cm
                  p 4 cm de margen de costura por rodilla y bota
    
    p.mb-4 Ya teniendo claro cómo funciona cada uno de los puntos, márgenes de costura y plano del pantalón, lo primero que se debe hacer es el trazo del rectángulo base. Para este rectángulo, se debe trabajar el contorno más protuberante y el largo más largo de las partes que se va a cubrir o en este caso, la intersección entre extremidades inferiores y contornos generales del cuerpo.
    p.mb-5 En los 
      strong  patrones de pantalón femenino 
      | dependiendo de la tipología se adecuan ampliaciones, largos y cortes donde dan lugar a la creación de otros básicos que pueden ser utilizados para ser cortados en la tela. Para introducirnos en la comprensión de este tema se recomienda revisar el siguiente material:
    
    .row.justify-content-center.mb-4
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
    
    .row.mb-4
      .col-lg-2
      .col-lg-4.mb-4.mb-lg-0
        a.anexo.mb-4.mb-lg-0(href="https://repositorio.sena.edu.co/bitstream/handle/11404/4725/Manual_patronaje_basico_interpretacion_disenos.PDF;jsessionid=CDC8FDE9468D98E37FFD127332113A29?sequence=1" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            strong Anexo. 
            | Manual de patronaje básico para interpretación de diseños. Leer de la página 28 a la 30.

    p.mb-4 También será importante visualizar el siguiente video explicativo, sobre cómo realizar la base inferior del pantalón femenino.

    .row.mb-5
      .col-lg-8
      .col-lg-4
         a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?app=desktop&v=7XPqP_3v0L0&ab_channel=RedProducci%C3%B3ndeContenidosGrupoGesti%C3%B3nCurricularSENA" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg")
          .anexo__texto
            strong Enlace web. 
            | Video – Base inferior de pantalón femenino
    
    .row.mb-4
      .col-lg-6.d-flex.mb-4.mb-lg-0
        .cajon.color-acento-contenido.p-4
          .h4.mb-4 Variantes de pantalón femenino
          p.mb-4 Según modificaciones de largos, amplitudes, detalles y cortes, se pueden obtener los básicos inferiores. Las medidas de largo se deben tomar desde la cintura hasta el punto de la pierna que lo sugiera el diseño.
          p.mb-4 En los siguientes recursos podremos apreciar las diferentes variantes del pantalón femenino.
          .row.justify-content-center
            .col-lg-10.mb-4.mb-lg-0
              a.anexo.mb-4(href="https://www.youtube.com/watch?app=desktop&v=K2SbwvDv7eA&ab_channel=RedProducci%C3%B3ndeContenidosGrupoGesti%C3%B3nCurricularSENA" target="_blank")
                .anexo__icono
                  img(src="@/assets/template/icono-link.svg")
                .anexo__texto
                  strong Enlace web. 
                  | Video - Interpretación de prendas de vestir
              a.anexo.mb-4(href="https://www.youtube.com/watch?app=desktop&v=xcUi9S-ZqzI&ab_channel=RedProducci%C3%B3ndeContenidosGrupoGesti%C3%B3nCurricularSENA" target="_blank")
                .anexo__icono
                  img(src="@/assets/template/icono-link.svg")
                .anexo__texto
                  strong Enlace web. 
                  | Video - Análisis e interpretación de pantalón y sudadera
      .col-lg-1.mb-4.mb-lg-0
      .col-lg-3.mb-4.mb-lg-0
        .h5.mb-4  Figura 13. Tipologías de pantalón según largo
        figure.mb-4
          img(src='@/assets/curso/tema5/img14.png')
          figcaption.text-black Fuente: SENA, 2021

    separador
    #t_5_4.titulo-segundo
      .h4 5.4 Mangas
    
    .row.align-items-center.mb-4
      .col-lg-6.mb-4.mb-lg-0
        p.mb-4 En el patronaje, las mangas van conectadas no solo al tamaño de los brazos sino también a la postura de la persona, estos son factores que se deben tener en cuenta desde el análisis antropométrico.
        p.mb-4 Cuando se habla de manga, básicamente se entiende o identifica como una pieza circular que cubre el brazo, sin embargo, existen diferentes tipos de puntos a tener en cuenta:
        ul.lista-ul--color
          li 
            i.fas.fa-atom 
            p
              strong Largo de manga: 
              | el largo de manga anatómico es aquel que va desde el punto de acromio hasta la muñeca, se debe tener en cuenta que, sin importar el diseño, largo o forma del cuerpo de la manga, siempre se debe partir desde el largo anatómico.
          li 
            i.fas.fa-atom 
            p
              strong Altura o cabeza de manga: 
              | cuando se habla de cabeza de manga, se identifican diferentes tipos de medidas, se puede trabajar con medida de cuadro de tallas, medida deducida o estandarizada.
      .col-lg-6.mb-4.mb-lg-0
        img(src='@/assets/curso/tema5/img15.png')
    
    .row.mb-4
      .col-lg-4.mb-4.mb-lg-0
        img(src='@/assets/curso/tema5/img16.svg')
      .col-lg-8.mb-4.mb-lg-0
        .cajon.color-primario.p-4.mb-4
          .row.align-items-center
            .col-lg-2.mb-4.mb-lg-0
              img(src='@/assets/curso/tema5/img08.svg')
            .col-lg-8.mb-4.mb-lg-0
              p
                strong Tener en cuenta: 
                | que el largo de manga siempre será el mismo, sin importar que tipo de prenda o cabeza de manga se implemente.
        p.mb-4 En el desarrollo de curvas y trazos en las cabezas de manga existen varias formas de trazarlas, las implementadas y guiadas en el vídeo que se presenta a continuación, hace referencia a un acercamiento general de todos los trazos del manual.
        .h4.mb-4 Medidas:
        ul.lista-ul--color
          li 
            i.fas.fa-atom 
            | Recorrido sisa delantera (medidas que salen del plano)
          li 
            i.fas.fa-atom 
            | Recorrido sisa posterior (medidas que salen del plano)
          li 
            i.fas.fa-atom 
            | Tipo de cabeza de manga
          li 
            i.fas.fa-atom 
            | Largo de manga.

    .row.justify-content-between.mb-4
      .col-lg-5.d-flex.mb-4.mb-lg-0
        .cajon.color-acento-contenido.p-4
          p.mb-4 Apreciemos el paso a paso para conocer el trazo de manga y cabezas de manga.
          a.anexo.mb-4(href="https://www.youtube.com/watch?v=EAl_FBfkYUE&ab_channel=RedProducci%C3%B3ndeContenidosGrupoGesti%C3%B3nCurricularSENA" target="_blank")
            .anexo__icono
              img(src="@/assets/template/icono-link.svg")
            .anexo__texto
              strong Enlace web. 
              | Video - Trazo de manga y cabezas de manga
          p.mb-4 Otras formas para sacar o deducir la altura de cabeza de manga, se pueden estudiar en el documento:
          a.anexo.mb-4.mb-lg-0(href="https://repositorio.sena.edu.co/bitstream/handle/11404/4725/Manual_patronaje_basico_interpretacion_disenos.PDF;jsessionid=CDC8FDE9468D98E37FFD127332113A29?sequence=1" target="_blank")
            .anexo__icono
              img(src="@/assets/template/icono-pdf.svg")
            .anexo__texto
              strong Anexo. 
              | Manual de patronaje básico para interpretación de diseños. Leer páginas 26 a la 44.
      .col-lg-5.mb-4.mb-lg-0
        .cajon.color-acento-contenido.p-4
          p.mb-4 También será muy importante conocer y comprender la diversidad asociada a la interpretación de las mangas, de tal manera que se puedan implementar las variaciones de acuerdo a las necesidades de cada prenda a confeccionar:
          a.anexo.mb-4(href="https://www.youtube.com/watch?app=desktop&v=2a81MoVG6Dg&ab_channel=RedProducci%C3%B3ndeContenidosGrupoGesti%C3%B3nCurricularSENA" target="_blank")
            .anexo__icono
              img(src="@/assets/template/icono-link.svg")
            .anexo__texto
              strong Enlace web. 
              | Video - Interpretación de mangas
          a.anexo.mb-4(href="https://repositorio.sena.edu.co/bitstream/handle/11404/4725/Manual_patronaje_basico_interpretacion_disenos.PDF;jsessionid=CDC8FDE9468D98E37FFD127332113A29?sequence=1" target="_blank")
            .anexo__icono
              img(src="@/assets/template/icono-pdf.svg")
            .anexo__texto
              strong Anexo. 
              | Manga Kimono. Leer página 48 y manga ranglan formal e informal. Leer páginas 49 y 50.
          a.anexo.mb-4(href="https://www.youtube.com/watch?app=desktop&v=tJWzjpSmkps&ab_channel=RedProducci%C3%B3ndeContenidosGrupoGesti%C3%B3nCurricularSENA" target="_blank")
            .anexo__icono
              img(src="@/assets/template/icono-link.svg")
            .anexo__texto
              strong Enlace web. 
              | Video - Generalidades de la manga kimono y ranglan

    p.mb-4 Para finalizar este tema abordaremos la interpretación de prendas, con la finalidad de cerrar el análisis de la composición del patronaje básico para la línea femenina. En los siguientes 4 videos mostraremos los aspectos más importantes a tener en cuenta en este proceso:

    .row.justify-content-between.mb-4
      .col-lg-3.mb-4.mb-lg-0
        a.anexo.mb-4(href="https://www.youtube.com/watch?app=desktop&v=ZbGipLzdDTY&ab_channel=RedProducci%C3%B3ndeContenidosGrupoGesti%C3%B3nCurricularSENA" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg")
          .anexo__texto
            strong Enlace web. 
            | Video - Análisis e interpretación de capas
      .col-lg-3.mb-4.mb-lg-0
        a.anexo.mb-4(href="https://www.youtube.com/watch?app=desktop&v=-t2RPXBUsLA&ab_channel=RedProducci%C3%B3ndeContenidosGrupoGesti%C3%B3nCurricularSENA" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg")
          .anexo__texto
            strong Enlace web. 
            | Video - Abrigo asimétrico
      .col-lg-3.mb-4.mb-lg-0
        a.anexo.mb-4(href="https://www.youtube.com/watch?app=desktop&v=8d20OBO4tHI&ab_channel=RedProducci%C3%B3ndeContenidosGrupoGesti%C3%B3nCurricularSENA" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg")
          .anexo__texto
            strong Enlace web. 
            | Video - Interpretación de pantalón sastre femenino
      .col-lg-3.mb-4.mb-lg-0
        a.anexo.mb-4(href="https://www.youtube.com/watch?v=xcUi9S-ZqzI&t=236s&ab_channel=RedProducci%C3%B3ndeContenidosGrupoGesti%C3%B3nCurricularSENA" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg")
          .anexo__texto
            strong Enlace web. 
            | Video - Análisis e interpretación de pantalón sudadera

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
