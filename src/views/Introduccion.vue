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
