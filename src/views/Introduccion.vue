<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal
      .titulo-principal__numero
        img(width="50" height="50" src='@/assets/curso/RectanguloInfo.svg')       
        span 
          i.text-white.fas.fa-info        
      h1 Introducción

    .shadow.p-3.mb-5.bg-body.rounded.fondoBanner-1
      .row.align-items-center
        .col-1
          img(src='@/assets/curso/figRio.svg')
        .col-6
          p.me-5.text-large Las empresas pecuarias son una necesidad en todos los países y por eso se trabajará en este contenido la normativa y procedimiento básico para quienes tengan o quieran tener una:
        .col-5     
          img(src='@/assets/curso/Tractor.svg')

    //p.mb-5 Las empresas pecuarias son una necesidad en todos los países y por eso se trabajará en este contenido la normativa y procedimiento básico para quienes tengan o quieran tener una:
    figure.mt-5.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video: Leyenda del video

//    figure.mb-5
      img(src="@/assets/curso/banner-intro.jpg", alt="Texto que describa la imagen")
      figcaption Imagen 1. Vacunación

    p.mb-0 La llegada de nuevas vacunas al país supone un reto para el talento humano en salud responsable de la vacunación y desarrollar habilidades para ofrecer una orientación oportuna y segura a las personas objeto de la vacuna.
      br
      br
      | En ese orden de ideas, este componente formativo guía al aprendiz hacia la identificación de los aspectos normativos, técnicos y operativos de la vacunación contra COVID19 en Colombia y de las generalidades de la infección por SARS-2 COVID 19.

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
