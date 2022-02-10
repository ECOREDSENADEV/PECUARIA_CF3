<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    //- El componente "Muestras" tiene las aplicaciones de todos los componentes de la base
    //- se encuentra en src/components/Muestras.vue
    //- Una vez el componente "Muestras" no se necesite 
    //- Se debe borrar el "import Muestras from '../components/Muestras'" y en "components" en "<script"
    //- esto evitará que se compile en la carpeta final de distribución
    Muestras
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
    
      h2.titulo-segundo 1.1 Clasificación
      img(src='@/assets/curso/fondoVerduras.svg')

    ImagenInfografica.color-primario.mb-5
      template(v-slot:imagen)
        figure
          img(src='@/assets/template/infografiaClaseEmpresa.svg', alt='Clasificación de las empresas')

      .tarjeta-avatar.color-acento-botones.p-3(x="2.8%" y="31.5%" )
        img(src='@/assets/componentes/imagenAvatar.svg' alt='AvatarTop')
        .tarjeta.color-secundario
          .text-black.p-4.text-small
            h2.text-center Según el sector económico
            p Bajo este criterio la empresa se clasifica según el sector productivo al que pertenece su actividad principal, mediante este sistema también se suele determinar el tipo de actividad a desarrollar: de extracción, producción o comercialización.

      .tarjeta-avatar.color-acento-botones.p-3(x="2.8%" y="48.5%" )
        img(src='@/assets/componentes/imagenAvatar.svg' alt='AvatarTop')
        .tarjeta.color-secundario
          .text-black.p-4.text-small
            h2.text-center Sector primario
            p agrupa a los organismos que llevan a cabo tareas relacionadas con la explotación de recursos naturales. Este sector usualmente no involucra actividades de transformación, por lo que el cliente suele comprar los recursos tal cual fueron extraídos. Uno de los ejemplos más comunes son las empresas mineras, que extraen bienes naturales como carbón o minerales de la tierra.

      .tarjeta-avatar.color-acento-botones.p-3(x="2.8%" y="63.5%" )
        img(src='@/assets/componentes/imagenAvatar.svg' alt='AvatarTop')
        .tarjeta.color-secundario
          .text-black.p-4.text-small
            h2.text-center Sector secundario
            p incluye las empresas que desarrollan actividades manufacturares, esto significa, que adquieren materias primas de terceros para transformarlos en productos terminados con características esencialmente diferentes. Por ejemplo, una zapatería que compra insumos como madera o cuero y los transforma para producir y vender zapatos.

      .tarjeta-avatar.color-acento-botones.p-3(x="2.8%" y="78.5%" )
        img(src='@/assets/componentes/imagenAvatar.svg' alt='AvatarTop')
        .tarjeta.color-secundario
          .text-black.p-4.text-small
            h2.text-center Sector terciario
            p comprende aquellas empresas dedicadas a la intermediación de bienes sin ningún tipo de proceso o valor agregado, así como las que se dedican a la prestación de servicios. Aquí pueden incluirse empresas como las comercializadoras o supermercados que compran insumos al por mayor para luego ser vendidos por unidades. 

      .tarjeta-avatar.color-acento-botones.p-3(x="23.4%" y="31.7%" )
        img(src='@/assets/componentes/imagenAvatar.svg' alt='AvatarTop')
        //- .tarjeta debe ir acompañado de una de una de estas clases => 
        //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
        //- estas clases tambien tienen un modificador --borde
        .tarjeta.color-secundario
          .text-black.p-4.text-small
            h2.text-center según el control de recursos
            p Según este criterio, las empresas se clasifican según la procedencia del capital; este último entendido como la inversión efectuada por parte de sus accionistas o propietarios, para que la empresa opere. En principio existen dos fuentes principales de recursos, la proveniente del sector público, bajo la figura del Estado, y el sector privado.
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
