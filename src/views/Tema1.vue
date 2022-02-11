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

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero              
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
        .cajon.Color-Bkg-Cajon.p-4.mb-4.Neg-Izq.position-relative
          p.color-acento-contenido <span style='color:#5F9025;'>ARTÍCULO 25. EMPRESA - CONCEPTO.</span> Se entenderá por empresa toda actividad económica organizada para la producción, transformación, circulación, administración o custodia de bienes, o para la prestación de servicios. Dicha actividad se realizará a través de uno o más establecimientos de comercio (Código de Comercio, 1971, Artículo 25).
          img.hijoHoja(src='@/assets/curso/hoja.png')
      .col-5
        img(src='@/assets/curso/Recolectores.png')
    .titulo-segundo.color-acento-contenido
      h2 1.1 Clasificación   
    .shadow.p-3.mb-5.bg-body.rounded.fondoBanner-1
      .row.align-items-center
        .col-1
        .col-3
          img(src='@/assets/curso/Verduras.svg')
        .col-1
        .col-1
          img(src='@/assets/curso/figRio.svg')
        .col-6      
          p Las empresas pueden clasificarse según diversos criterios, y así, abordar definiciones, estrategias y medidas de forma conjunta en función de las necesidades de cada usuario. La siguiente figura infográfica presenta algunos de los sistemas de clasificación más utilizados en nuestro entorno:
    ImagenInfografica.color-acento-botones.mb-5
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

      .tarjeta-avatar.color-acento-botones.p-3(x="23.4%" y="48.5%" )
        img(src='@/assets/componentes/imagenAvatar.svg' alt='AvatarTop')
        .tarjeta.color-secundario
          .text-black.p-4.text-small
            h2.text-center Pública
            p Todo el capital se obtiene a través de fuentes de recursos públicos, su destinación suele estar asociada a la satisfacción de necesidades con un fuerte componente social o a la extracción de recursos que le pertenecen a la nación. En esta categoría entran algunas empresas de servicios públicos u hospitales.

      .tarjeta-avatar.color-acento-botones.p-3(x="23.4%" y="63.5%" )
        img(src='@/assets/componentes/imagenAvatar.svg' alt='AvatarTop')
        .tarjeta.color-secundario
          .text-black.p-4.text-small
            h2.text-center Privada
            p El capital se obtiene a través de particulares; las actividades son tan variadas como las necesidades del mercado y la imaginación de sus directivos. Su propósito es la generación de utilidades para ser distribuidos como dividendos o para reinvertir en la empresa y garantizar su crecimiento en el tiempo. 

      .tarjeta-avatar.color-acento-botones.p-3(x="23.4%" y="78.5%" )
        img(src='@/assets/componentes/imagenAvatar.svg' alt='AvatarTop')
        .tarjeta.color-secundario
          .text-black.p-4.text-small
            h2.text-center Mixta
            p Su capital proviene tanto de fuentes públicas como privadas. Suelen surgir producto de la necesidad del Estado de conseguir recursos adicionales a los asignados mediante presupuesto o utilidades generadas por las empresas; ya sea para mantenerlas operativas  o para dinamizar su actividad.

      .tarjeta-avatar.color-acento-botones.p-3(x="43.6%" y="31.7%" )
        img(src='@/assets/componentes/imagenAvatar.svg' alt='AvatarTop')
        .tarjeta.color-secundario
          .text-black.p-4.text-small
            h2.text-center Según su esfera territorial
            p Este sistema clasifica las empresas según la extensión del área geográfica en el que la empresa lleva a cabo su objeto social.

      .tarjeta-avatar.color-acento-botones.p-3(x="43.6%" y="48.5%" )
        img(src='@/assets/componentes/imagenAvatar.svg' alt='AvatarTop')
        .tarjeta.color-secundario
          .text-black.p-4.text-small
            h2.text-center Local
            p Desarrolla su actividad comercial es un área de poca cobertura, bien sea una localidad o municipio, donde se encuentra su planta física.

      .tarjeta-avatar.color-acento-botones.p-3(x="43.6%" y="63.5%" )
        img(src='@/assets/componentes/imagenAvatar.svg' alt='AvatarTop')
        .tarjeta.color-secundario
          .text-black.p-4.text-small
            h2.text-center Regional
            p Involucra más de un municipio para llevar a cabo su operación, esta restringido a un departamento o región en específico.

      .tarjeta-avatar.color-acento-botones.p-3(x="43.6%" y="78.5%" )
        img(src='@/assets/componentes/imagenAvatar.svg' alt='AvatarTop')
        .tarjeta.color-secundario
          .text-black.p-4.text-small
            h2.text-center Nacional
            p La producción y/o venta de los bienes o servicios cubre más de una región en el país. Abarcan una porción significativa del territorio nacional a través de sucursales físicas distribuidas en distintas regiones, o haciendo uso de sistemas de distribución de gran envergadura.
      .tarjeta-avatar.color-acento-botones.p-3(x="43.6%" y="93.7%" )
        img(src='@/assets/componentes/imagenAvatar.svg' alt='AvatarTop')
        .tarjeta.color-secundario
          .text-black.p-4.text-small
            h2.text-center Multinacional
            p Ejecutan las actividades operativas y ofertan sus bienes y servicios en varios países. Por norma general cuentan con una sede matriz en un país, que funciona como central de operaciones a nivel global, mientras que las sucursales que operan alrededor del mundo se conocen como subsidiarias o filiales.
    .row.mb-5.mt-5
      .col-7
        p.text-small Adicionalmente se tienen las empresas por orden legal tal como se presenta a continuación: 
        h3 
          span.colorText-verde <u>Según su constitución jurídica</u>
        p.text-small Las organizaciones que cumplen con la definición de empresa pueden ser constituidas de manera unipersonal o a través de la creación de una persona jurídica en donde se unen varios inversores organizados en sociedad:
        //linea de tiempo
        .row.mb-5
          .col-md-12.mb-5.mb-md-0
            //- LineaTiempoD debe ir acompañado de una de una de estas clases => 
            //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
            LineaTiempoD.color-acento-contenido
              .row(numero="1" titulo="Societarias")
                .col-md-12.mb-4.mb-md-0
                  p.text-small <span style="color:green;">Se constituyen como un organismo independiente </span>a los socios que la crearon por lo que cuentan con un número de identificación propio y único. Gracias a su personería jurídicas, la responsabilidad frente a terceros recae sobre sí misma y sobre su representante legal. En Colombia la legislación y practica comercial contemplan varios tipos de empresas que cumplen con esta definición. La forma más rápida y sencilla de identificarlas es observando la terminación de su nombre o razón social, ver tabla 1:
                  .titulo-sexto.color-acento-contenido
                    h5 Tabla 1.
                    span Tipos societarios        
                  .tabla-a.color-primario.mb-5.ms-4.me-4 
                    table
                      caption Nota. Sena (2021).
                      thead
                        tr.bg-tabla-primario
                          th.text-white
                            h3 Tipo societario
                          th.text-white 
                            h3 Terminación
                      tbody
                        tr
                          td 
                            h4.ms-2 Sociedad en comandita simple 
                          td 
                            h4.ms-2 S en C
                        tr
                          td 
                            h4.ms-2 Sociedad en Comandita por Acciones
                          td 
                            h4.ms-2 S.C.A.
                        tr
                          td 
                            h4.ms-2 Sociedad de responsabilidad limitada.
                          td 
                            h4.ms-2 Ltda.         
                        tr
                          td 
                            h4.ms-2 Sociedad Anónima
                          td 
                            h4.ms-2 S.A.
                        tr
                          td 
                            h4.ms-2 Sociedad por acciones simplificada.
                          td 
                            h4.ms-2 S.A.S.                 

              .row(numero="2" titulo="Autónomas")
                .col-md-6
                  figure
                    img(src='@/assets/template/GrupoOficina.svg', alt='Sociedades autónomas')
                .col-md-6.mb-4.mb-md-0
                  p.text-large.align.items.center <span style="color:green;">Se constituyen por una sola persona natural</span> sin crear  otra entidad independiente. Asumen todas las responsabilidades frente a terceros. Como no cuentan con personería jurídica, no requieren de un número de identificación independiente.

      .col-5
        img(src='@/assets/curso/saludoManos.png')
      h3
        span.colorText-verde <u>Según tamaño</u>
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mt-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/Lectora.jpg')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0.text-small <span style='color:#5F9025;'>Para clasificar las empresas según su tamaño existen diversos criterios o escalas de medición.</span> Algunos se apoyan en la cantidad de activos, otros en el tamaño de su patrimonio o bien en el número de empleos que genera. La legislación colombiana ha sancionado diversos decretos y leyes que presentan unos criterios determinados. Como ejemplo de lo anterior, la ley 590 de 2000 lista las categorías y los rangos para clasificar las empresas en función de criterios como el número de trabajadores, el valor de los activos o las ventas brutas anuales; posteriormente, el decreto 957 de 2019, emitido por el Ministerio de comercio, industria y turismo, reglamenta este aspecto según el sector económico en el que la empresa lleve a cabo su actividad, ver tabla 2:
    .titulo-sexto.color-acento-contenido
      h5 Tabla 2.
      span Clasificación de las empresas según Decreto 957 

    .tabla-b.color-acento-contenido.mb-5.mt-5
      .tabla-b__header.justify-content-center
        h5.mb-0.Text-grande Ingresos en UVT (unidades de valor tributario) de actividades ordinarias según sector económico
      table.justify-content-center
        caption Nota. Decreto 957 del Ministerio de Comercio, Industria y Turismo (2019).
        thead.bg-tabla-primario.Text-grande
          tr
            th.text-white Tamaño de la empresa / sector
            th.text-white Manufactura
            th.text-white Servicios
            th.text-white Comercio
        tr.Text-grande
          th Microempresa
          td Menores o iguales a 23.563.
          td Menores o iguales a 32.988.
          td Menores o iguales a 44.769.
        tr.Text-grande
          th Pequeña
          td Mayores a 23.563 y menores o iguales a 204.995.
          td Mayores a 32.988 y menores o iguales a 131.951.
          td Mayores a 44.769 y menores o iguales a 431.196.
        tr.Text-grande
          th Mediana
          td Mayores a 204.995 y menores o iguales a 1'736.565.
          td Mayores a 131.951 y menores o iguales a 483.034.
          td Mayores a 431.196 y menores o iguales a 2.160.692.
        tr.Text-grande
          th Grande
          td Mayores a 1'736.565.
          td Mayores a 483.034.
          td Mayores a 2.160.692.
    .titulo-segundo.color-acento-contenido
      h2 1.2  Recursos
    .row.mb-5.mt-5
      .col-7
        p.mb-4 <span style='color:#5F9025;'>Según Planas (2008)</span>, las empresas funcionan como sistemas abiertos, en donde obtienen recursos del ambiente como lo son las materias primas o el capital, y que suelen ser conocidas como entradas o “inputs” por su traducción al inglés. Esto puede aterrizarse a ejemplos como la compra de leche en una productora de alimentos, como materias primas que luego son transformadas para reintegrarse al entorno en forma de salidas o “outputs”. Continuando con el ejemplo, la leche se sometería a un proceso productivo para venderse en forma de queso o mantequilla.
        .cajon.Color-Bkg-Cajon.p-4.mb-4.Neg-Izq.position-relative
          p.color-acento-contenido El ciclo debe ser supervisado de manera permanente de tal forma que se garantice el cumplimiento de las estrategias propuestas por los directivos. Al fin y al cabo, en el desarrollo operativo de la empresa, siempre se deberá velar por el cumplimiento de las expectativas de sus dueños, por lo que estos sistemas de control aportarán la retroalimentación necesaria para pulir el proceso productivo e incrementar las ganancias esperadas con el paso del tiempo, ver figura 1. 
          img.hijoHoja(src='@/assets/curso/hoja.png')
      .col-5
        img(src='@/assets/curso/Reunion.svg')
    
    .row.mb-5.mt-5
      .col-12
        .titulo-segundo.color-acento-contenido
          h5 Figura 1. Empresas como sistema
        img(src='@/assets/curso/figura1.svg')   
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
