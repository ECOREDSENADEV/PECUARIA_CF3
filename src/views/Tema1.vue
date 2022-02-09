<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    //- El componente "Muestras" tiene las aplicaciones de todos los componentes de la base
    //- se encuentra en src/components/Muestras.vue
    //- Una vez el componente "Muestras" no se necesite 
    //- Se debe borrar el "import Muestras from '../components/Muestras'" y en "components" en "<script"
    //- esto evitará que se compile en la carpeta final de distribución
    //- Muestras
    .titulo-principal
      .titulo-principal__numero
        img(width="50" height="45" src='@/assets/curso/RectanguloInfo.svg')       
        span.text-white 1        
      h1 Empresa
    p.mb-4 El concepto de empresa se debe dar de inicio para tener claro a qué se hace referencia con esta palabra tan comúnmente usada:
    #video.titulo-segundo.color-acento-botones
    h2 Video
    figure
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video: Leyenda del video 

    .row.mb-5.mt-5
      .col-7
        p.mb-4 La relevancia de las empresas es tan elevadas que la normatividad colombiana cuenta con diversas normas que la definen y regulan. El ejemplo más claro lo contiene el código de comercio de 1971, considerado el compendio de normas comerciales más importante en Colombia; allí se define de la siguiente forma:
      .col-5
        img(src='@/assets/curso/Recolectores.png')
      .col-lg-8
        .cajon.color-acento-contenido.p-4.mb-4
          p ARTÍCULO 25. EMPRESA - CONCEPTO. Se entenderá por empresa toda actividad económica organizada para la producción, transformación, circulación, administración o custodia de bienes, o para la prestación de servicios. Dicha actividad se realizará a través de uno o más establecimientos de comercio (Código de Comercio, 1971, Artículo 25).
</template>

<script>
import Muestras from '../components/Muestras' // borrar una vez el componente "Muestras" no se necesite
export default {
  name: 'Tema1',
  components: {
    Muestras, // borrar una vez el componente "Muestras" no se necesite
  },
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
