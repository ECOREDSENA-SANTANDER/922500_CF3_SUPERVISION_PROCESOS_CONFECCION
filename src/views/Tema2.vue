<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero
        span 2
      h1 Tipos de patronaje y escalado
      

    .row.tema2.align-items-center.py-4.py-md-5
      .col-lg-12.col-12.px-lg-5.px-4
      
        .row.justify-content-center.align-items-center(data-aos="zoom-in-left")
          .col-sm-12.col-lg-10
            .bloque-texto-a.color-acento-contenido.prim.p-4.p-md-5.mb-5 
              .row.m-0.align-items-center.justify-content-between
                .col-lg-4.mb-4.mb-lg-0
                  img(src="@/assets/curso/tema2/img01.svg", alt="tema2")
                .col-lg-8
                  .bloque-texto-a__texto.p-4
                    p Son diversas las técnicas empleadas que se esquematizan para la elaboración de patrones y moldes en prendas de vestir, estas técnicas son empleadas a partir de estudios antropométricos, en los que posteriormente una vez se establece la técnica pasa por pruebas de medición para determinar ergonomía y funcionalidad, una vez se realizan estas pruebas se realizan los respectivos ajustes que serán implementados en dichos patrones.
    
        p.mb-5 Se ha mencionado que se han logrado establecer metodologías y técnicas propiciando la industrialización global de los patrones, sin embargo, cada empresa, patronista, tallerista, modisto, sastre, costurero o diseñador emplean técnicas propias que consideran son necesarias para lograr una horma determinada.  Estos ajustes son evaluados por las personas encargadas, partiendo de criterios universales en patronaje o en otros casos suelen establecer un modelo de patronaje diferente, esto siempre dependerá del enfoque de la empresa, el público objetivo y el producto.
    
        .tarjeta.tarjeta--gris.bg2.p-4.mt-5.mb-5
          LineaTiempoC 
            .row.justify-content-center.align-items-start(titulo="Tipos de patronaje y líneas")
              .col-md-4
                span.text-cus #[b Tipos de patronaje y líneas]
                p.mb-5 Dentro de los tipos de patronaje encontramos dos grandes grupos: el primero es el patronaje industrializado que propicia la producción en masa de prendas. El segundo es el patronaje sobre medidas el cual es personalizado y en muchos modelos de negocio se emplea con la finalidad de brindar exclusividad a los clientes.
                p A continuación, se detallan las características de cada uno de ellos.
              .col-md-6
                figure
                  img(src='@/assets/curso/tema2/2.png', alt='tema1')      
              
            .row.justify-content-center.align-items-start(titulo="Patronaje industrial")
              .col-md-7.mb-4
                span.text-cus #[b Patronaje industrial]
                p.mb-4
                p.mb-5 El patronaje es un proceso meticuloso que implica un análisis antropométrico detallado, abarcando la figura humana en 3D. Este método se distingue por su precisión en cada paso, desde el levantamiento de los básicos hasta el desarrollo de los patrones y moldes, junto con sus correspondientes transformaciones. Se lleva a cabo tanto en formato 2D, en papel o mediante software especializado como Audaces 360, Optitex, Gerber, y Lectra, entre otros.
                p Este enfoque comienza con tablas de medidas establecidas geométricamente, adaptadas al uso final de la prenda. Estas tablas permiten implementar técnicas de escalado, evitando la necesidad de crear patrones y moldes completamente nuevos para cada talla. En su lugar, se utilizan las medidas base para calcular los incrementos entre tallas y se desarrollan fórmulas para ajustar los moldes en cada punto, facilitando así la producción masiva en entornos industriales.
              .col-md-3
                figure
                  img(src='@/assets/curso/tema2/img07.png', alt='Texto alternativo Figura 2: Se exhiben 18 piezas de telas que conforman cada uno de los cortes que debe tener la tela para obtener el patrón completo para una chaqueta.')      
              
            .row.justify-content-center.align-items-center(titulo="El patronaje industrial comprende")
              .col-md-10.mb-4
                span.text-cus #[b El patronaje industrial comprende]  
                ul.lista-ul--color.mb-5
                  li.d-flex
                    i.fas.fa-car-side
                    | Levantamiento de básicos delanteros y posteriores.
                  li.d-flex
                    i.fas.fa-car-side
                    | Levantamiento de prendas inferiores y superiores.
                  li.d-flex
                    i.fas.fa-car-side
                    | Levantamiento de patrones y moldes de las diferentes partes de las prendas comprendidas en los códigos de vestuario como: cuellos, escotes, mangas, puños, ribetes, bolsillos, charreteras y otros complementos en las prendas de vestir. 
                  li.d-flex
                    i.fas.fa-car-side
                    | Abarcan todas las líneas: infantil, en sus diferentes etapas, dama y caballero.
                  li.d-flex
                    i.fas.fa-car-side
                    | A partir de las líneas se desarrollan toda una gama comercial que comprenden universos de vestuario y ocasiones de uso.
                .titulo-sexto.color-acento-contenido
                  h5 Figura 2. 
                  | Patronaje industrial de chaqueta
                figure
                  img(src='@/assets/curso/tema2/img08.svg', alt='tema1')      
              
            .row.justify-content-center.align-items-start(titulo="Patronaje sobre medidas")
              .col-md-6.mb-4
                span.text-cus.mb-5 #[b Patronaje sobre medidas]
                p.mb-5 El patronaje también se destaca por su atención a la ergonomía y funcionalidad de las prendas. Se emplea especialmente para crear prendas completamente personalizadas para clientes exclusivos, siendo una práctica común entre marcas orientadas a un público selecto. Este proceso implica la toma de medidas antropométricas del cliente, seguida de una premuestra para ajustes preliminares antes de la confección final.
                ul.lista-ul--color.mb-5
                  li.d-flex
                    i.fas.fa-car-side
                    | El levantamiento de patrones en plano: similar al industrial, pero aquí el patronista implementa también técnicas y fórmulas que considere necesarias. 
                  li.d-flex
                    i.fas.fa-car-side
                    | Patronaje sobre maniquí: técnica que es requerida en la construcción de prendas con drapeado o la aplicación de metodologías empleados como el Moulage, que es muy similar al drapeado, sobre el maniquí suelen generarse dichos moldes dado que suelen anudarse, doblarse e incluso generar plisados y otros acabados cuyas texturas requieren de un trabajo mucho más arduo. Bajo esta técnica muchas empresas, marcas, diseñadores, patronistas, sastres o modistos suelen realizar prendas de fiesta, vestidos de matrimonio, trajes para caballero e incluso para público infantil.
            
              .col-md-3
                figure
                  img(src='@/assets/curso/tema2/img09.png', alt='tema1')      
                  
            .row.justify-content-center.align-items-start(titulo="El patronaje sobre medidas comprende")   
              .col-md-10.mb-4
                span.text-cus #[b El patronaje sobre medidas comprende]
                p.mb-5 Las mismas etapas del patronaje industrial, la diferencia entre este radica en la exclusividad que categoriza a la prenda, ofreciendo al usuario del producto la sensación de utilizar prendas que son desarrolladas y confeccionadas específicamente para su gusto y necesidad.
              .row.justify-content-center.align-items-center
                .col-lg-8
                  .titulo-sexto.color-acento-contenido
                    h5 Figura 3. 
                    | Patronaje sobre maniquí
                  img(src='@/assets/curso/tema2/img06.png', alt='Texto alternativo Figura 3.La imagen expone a una persona tomando medidas y haciendo ajustes de la tela sobre un maniquí, esto facilita la tarea de patronaje.')      
              
    
        
    p.mb-4(data-aos="fade-right") A continuación, haremos un rápido recorrido por los Universos de vestuario y las ocasiones de uso:
        
        .row.justify-content-center.align-items-center.mb-4(data-aos="zoom-in-left")
          .col-lg-6
            .fondo21.p-3.mb-2
              .row.justify-content-around.align-items-center
                .col-3.col-sm-2.col-lg-2
                  img.mx-4.d-none.d-lg-block(src="@/assets/curso/tema7/pdf.svg", alt="tema 2")
                .col
                  .row.justify-content-between.align-items-center
                    .col.mb-3.mb-sm-0          
                      p.my-2.mx-4 Anexo. Universos del vestuario y ocasiones de uso
                    .col-sm-auto
                      a.boton.color-acento-botones.mx-4(href="/downloads/Anexo_1_Universos_Vestuario_ Y_Ocasiones_Uso.pdf" target="_blank")
                        span Descargar
                        i.fas.fa-download 
        
        p.mb-4(data-aos="fade-right") Dentro de los procesos productivos en las empresas todo el trabajo es guiado por fichas técnicas, las cuales permiten a cada uno de los integrantes de la empresa comprender el proceso a realizar, así como las especificaciones y datos que deben ser acatados con rigurosidad. Se invita a visualizar el posterior contenido con los siguientes fines: el primero es facilitar un reconocimiento de las partes de las prendas y el segundo permitirá identificar las fichas técnicas y su estructura.
    
        .row
          .col-lg-4.mb-4.mb-md-0
            a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=FHhqkd0h4Kw" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-link.svg" alt="Imagen decorativa")
              .anexo__texto
                strong.or Enlace web. 
                | Reconocimientos de las prendas
          .col-lg-4.mb-4.mb-md-0
            a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=5YOLIDHLiCw&t=122s" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-link.svg" alt="Imagen decorativa")
              .anexo__texto
                strong.or Enlace web. 
                | Introducción a la ficha técnica
          .col-lg-4.mb-4.mb-md-0
            a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=ck4jApUj5ss" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-link.svg" alt="Imagen decorativa")
              .anexo__texto
                strong.or Enlace web. 
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
