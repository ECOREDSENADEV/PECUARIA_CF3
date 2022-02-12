<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero              
        span.text-white 1        
      h1 Producción

    .row.mb-5.mt-5
      .col-7
        p.mb-4 La producción puede definirse como el proceso mediante el cual una empresa transforma una serie de insumos en un producto terminado. Como se ha mencionado previamente, el objetivo de una organización es la generación de valor a través de la satisfacción de necesidades identificadas en el mercado objetivo, esto implica la oferta de bienes o servicios que otros agentes no están aportando a la sociedad, o no lo hacen de forma suficiente.
        .cajon.Color-Bkg-Cajon.p-4.mb-4.Neg-Izq.position-relative
          p.color-acento-contenido La mecánica organizacional puede reducirse a un flujo compuesto por tres grandes momentos: en primer lugar, la obtención de recursos materiales o técnicos del ambiente, para ello puede valerse de operaciones mercantiles como la compra de materias primas, obtención de créditos financieros, reclutamiento de personal entre otros, posteriormente la etapa de producción que involucra tomar estos recursos y dotarlos de un propósito, bien sea transformándolos en un producto tangible o diseñando un servicio concreto, y finalmente, la entrega de estos al mercado en forma de venta a los clientes. 
          img.hijoHoja1(src='@/assets/curso/hoja.png')
      .col-5
        img(src='@/assets/curso/Estudio.png')

    #etapas.titulo-segundo.color-acento-contenido
      h2  2.1 Etapas
    
    p.mb-4 El proceso productivo pasa por varias fases con funciones específicas hasta dar con la venta y entrega del producto final, el desglose de la producción puede presentarse así:
    .row.mb-5.mt-5
      .col-5
        img(src='@/assets/curso/Exposicion.png')
      .col-7.mb-5.mb-md-0
        LineaTiempoD.color-acento-contenido
          p(numero="1" titulo="Etapa analítica o de acopio") En esta fase se da inicio al ciclo productivo, y como su nombre lo indica, se caracteriza porque la organización busca conseguir la materia prima necesaria para cumplir con las metas de producción incurriendo en la menor cantidad de costos. La búsqueda de proveedores se centra en conseguir la mejor tarifa sin sacrificar calidad o cumplimiento. 
          
          p(numero="2" titulo="Etapa de síntesis o producción") Inicia el proceso de transformación de las materias primas en un nuevo producto, se involucran elementos del costo como la mano de obra y otros costos indirectos de fabricación. De manera paralela se establecen los procedimientos de supervisión y control, que buscan garantizar la calidad de los bienes producidos o servicios prestados, y aportar información utilidad para proponer las acciones de mejora a futuro.
          
          p(numero="3" titulo="Etapa de acondicionamiento o procesamiento") Finalmente, el producto recibe las modificaciones y adecuaciones necesarias para satisfacer la demanda de los clientes. Esto incluye costos de embalaje o presentación, almacenamiento, transporte y cualquier otro gasto asociado con  la entrega de los bienes o servicios.

    #producto.titulo-segundo
      .h4 2.2 Producto

    #planmerca.titulo-segundo
      .h4 2.3 Plan de Mercadeo

    #costo.titulo-segundo
      .h4 2.4 Costo

    #clase.titulo-segundo
      .h4 2.5 Clasificación

    #calculo.titulo-segundo
      .h4 2.6 Cálculo

    #ordenes.titulo-segundo
      .h4 2.7 Órdenes de Producción

    #caracteristicas.titulo-segundo
      .h4 2.7.1 Características

    #diligencia.titulo-segundo
      .h4 2.7.2 Diligenciamiento

    p.mb-4 Animación digital que crea la ilusión de movimiento mediante imágenes, fotografías, títulos, colores y diseños.

    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/E7-BaX6ox9s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    
    #t_2_3.titulo-segundo
      .h4 2.3 Motion + Presentador

    p.mb-4 Es el uso locutor + acompañamiento de imágenes como fondo, el estilo tiene una mezcla entre imagen viva y recursos gráficos vectoriales  se usa cuando un material tiene información de datos numéricos o gráficos de valores. 

    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/Ky73iaXuuTA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    #t_2_4.titulo-segundo
      .h4 2.4 Animación 2D

    p.mb-4 Es el uso locutor + acompañamiento de imágenes como fondo, el estilo tiene una mezcla entre imagen viva y recursos gráficos vectoriales  se usa cuando un material tiene información de datos numéricos o gráficos de valores. 

    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/3b8VctSm558" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    #t_2_5.titulo-segundo
      .h4 2.5 Video interactivo

    p.mb-4 Visualización de videos con diferentes tipos de preguntas o anotaciones.

    figure.mb-5
      .video
        iframe(src="https://vizia.co/videos/94d994c5fe93f1b08a60eb/embed" allowtransparency="true" frameborder="0" scrolling="no" width="640" height="390")

    #t_2_6.titulo-segundo
      .h4 2.6 Infografías

    p.mb-4 Es una herramienta de comunicación de alta precisión, el cual tiene una narrativa gráfica con un texto corto acompañada de elementos visuales que tienen como intención de captar rápidamente la atención del lector. 

    figure.mb-5
      img(src='@/assets/curso/infografia-1.jpg', alt='Infografía Fundamentos del Servicio de Interpretación')
      figcaption Fundamentos del Servicio de Interpretación

    .tarjeta.tarjeta--morada.p-3.mb-5
      .row.justify-content-around.align-items-center
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              .h5.mb-0 Fundamentos del Servicio de Interpretación
              p Formato PDF
            .col-sm-auto
              a.boton.boton--b(:href="obtenerLink('/downloads/fundamentos_del_servicio_de_Interpretacion.pdf')" target="_blank")
                span Descargar
                i.fas.fa-file-download
    
    figure.mb-5
      img(src='@/assets/curso/infografia-2.jpg', alt='Infografía Plan de Negocios')
      figcaption Plan de Negocios

    .tarjeta.tarjeta--morada.p-3.mb-5
      .row.justify-content-around.align-items-center
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              .h5.mb-0 Plan de Negocios
              p Formato PDF
            .col-sm-auto
              a.boton.boton--b(:href="obtenerLink('/downloads/plan_de_negocios.pdf')" target="_blank")
                span Descargar
                i.fas.fa-file-download
    
    figure.mb-5
      img(src='@/assets/curso/infografia-3.jpg', alt='Infografía Cobertura poblacional')
      figcaption Cobertura poblacional

    .tarjeta.tarjeta--morada.p-3.mb-5
      .row.justify-content-around.align-items-center
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              .h5.mb-0 Cobertura poblacional
              p Formato PDF
            .col-sm-auto
              a.boton.boton--b(:href="obtenerLink('/downloads/cobertura_poblacional.pdf')" target="_blank")
                span Descargar
                i.fas.fa-file-download
    
    figure.mb-5
      img(src='@/assets/curso/infografia-4.jpg', alt='Infografía Historia de las microfinanzas: Mohammad Yunus')
      figcaption Historia de las microfinanzas: Mohammad Yunus

    .tarjeta.tarjeta--morada.p-3.mb-5
      .row.justify-content-around.align-items-center
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              .h5.mb-0 Historia de las microfinanzas: Mohammad Yunus
              p Formato PDF
            .col-sm-auto
              a.boton.boton--b(:href="obtenerLink('/downloads/historia_de_las_microfinanzas_mohammad_yunus.pdf')" target="_blank")
                span Descargar
                i.fas.fa-file-download
    
    figure.mb-5
      img(src='@/assets/curso/infografia-5.jpg', alt='Infografía Psicología de la moda: sexualidad, ropa mágica, ropa malévola y ropa neurótica')
      figcaption Psicología de la moda: sexualidad, ropa mágica, ropa malévola y ropa neurótica

    .tarjeta.tarjeta--morada.p-3.mb-5
      .row.justify-content-around.align-items-center
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              .h5.mb-0 Psicología de la moda: sexualidad, ropa mágica, ropa malévola y ropa neurótica
              p Formato PDF
            .col-sm-auto
              a.boton.boton--b(:href="obtenerLink('/downloads/psicologia_de_la_moda.pdf')" target="_blank")
                span Descargar
                i.fas.fa-file-download

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

<style lang="sass"></style>
