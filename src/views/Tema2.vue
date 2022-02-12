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
    .row.mt-5.Neg-Abajo
      .col-1
      .col-10.bg-tabla1
        p.text-white.text-center.mt-1.text-bold Para ilustrar la información anterior, se presenta la siguiente figura 4 sobre el proceso de producción de la leche en una granja pecuaria:
      .col-1
    .row.mb-5.fondoBanner-2.d-flex
      .col-4.mt-5.mb-5.fondoBanner-3
        .row
          .col-3
          .col-9
            img(src='@/assets/componentes/Vaca.png', alt='Acopio')
        p.text-bold.ms-5.Text-grande.Neg-Top Acopio
        ul.lista-ul.ms-5.mb-5.text-large
          li 
            i.lista-ul__vineta
            | Alistamiento de las vacas
          li
            i.lista-ul__vineta
            | Inspección de su condición
          li 
            i.lista-ul__vineta
            | Preparación de maquinaria de extracción
      .col-4.mt-5.mb-5.fondoBanner-3
        .row
          .col-3
          .col-9
            img(src='@/assets/componentes/Cantina.png', alt='Producción')
        p.text-bold.ms-5.Text-grande.Neg-Top Producción
        ul.lista-ul.ms-5.mb-5.text-large
          li 
            i.lista-ul__vineta
            | Ordeño
          li
            i.lista-ul__vineta
            | Filtro de impurezas
          li 
            i.lista-ul__vineta
            | Almacenamiento en contenedores
          li 
            i.lista-ul__vineta
            | Análisis físico-químicos
          li 
            i.lista-ul__vineta
            | Pasteurización
      .col-4.mt-5.mb-5.fondoBanner-3
        .row
          .col-3
          .col-9
            img(src='@/assets/componentes/ProductoLeche.png', alt='Acondicionamiento')
        p.text-bold.ms-5.Text-grande.Neg-Top Acondicionamiento
        ul.lista-ul.ms-5.mb-5.text-large
          li 
            i.lista-ul__vineta
            | Envasado
          li
            i.lista-ul__vineta
            | Embalaje
          li 
            i.lista-ul__vineta
            | Etiquetado e identificación del producto
          li 
            i.lista-ul__vineta
            | Transporte y distribución
    p.mb-5 Nota. Sena (2021).

    #producto.titulo-segundo
      .h4 2.2 Producto
    .row.mt-4
      .col-4
        img(src='@/assets/curso/Celulares.jpg', alt='Productos')
      .col-8
        .row.ms-1
          .col-1
            img(src='@/assets/curso/figRio.svg')
          .col-11
            p Un producto es el resultado del ciclo productivo previamente explicado que busca satisfacer una o varias necesidades identificadas. Funciona como un eje central del objeto social de una compañía, puesto que es el medio para obtener una rentabilidad, generando así, un mayor valor en el tiempo. 
            p.bg1 Los productos son puestos a disposición de la demanda en un mercado determinado, los potenciales compradores tendrán la posibilidad de elegir entre este y las demás alternativas ofertadas por la competencia y elegirán en función de sus preferencias o condiciones personales. Hacer atractivo un producto requiere contemplar una gran cantidad de variables como lo son su calidad, el beneficio que ofrecen respecto a su precio, su facilidad de uso, entre otros.
          .container-fluid
            .row.mt-4
              .col-6
                .mb-3
                  a.boton.me-3.color-primario.indicador__container(
                    target="_self"
                    @mouseover="mostrarIndicador = false"
                  )
                    span.text-center.Text-grande Clasificación
                    i.fas.fa-pen
                    .indicador--click(v-if="mostrarIndicador")
              .col-6
                .mb-3
                  a.boton.me-3.color-primario.indicador__container(
                    target="_self"
                    @mouseover="mostrarIndicador = false"
                  )
                    span.text-center.Text-grande Fichas Técnicas
                    i.fas.fa-book
                    .indicador--click(v-if="mostrarIndicador")
    h3.mb-4
      span.colorText-verde <u>Clasificación</u>    
    p.mb-4 Existen diversos criterios y sistemas para clasificar los productos, sin embargo, se propone la siguiente distribución en función de tres de las características de más fácil identificación en cualquier tipo de bien o servicio: 

    ImagenInfografica.color-acento-botones.mb-5
      template(v-slot:imagen)
        figure
          img(src='@/assets/template/ClaseProductos.jpg', alt='Clasificación')
      .tarjeta-avatar.color-acento-botones.p-3(x="3%" y="31.8%" )
          img(src='@/assets/componentes/consumo.svg' alt='AvatarTop')
          .tarjeta.color-secundario
            .text-black.p-4.text-small
              h2.text-center De consumo
              p Se destinan al uso personal, por lo que no se espera sean utilizados en procesos productivos posteriores de tipo comercial, se subdividen en categorías.

      .tarjeta-avatar.color-acento-botones.p-3(x="3.1%" y="48.8%" )
          img(src='@/assets/componentes/conveniencia.svg' alt='AvatarTop')
          .tarjeta.color-secundario
            .text-black.p-4.text-small
              h2.text-center De conveniencia
              p Se caracterizan por tener precios económicos, por lo que adquirirlos no suele representar un gran esfuerzo para el comprador. Ejemplo de este tipo de productos son las golosinas, frutas, leche, hojas de papel o lapiceros.

      .tarjeta-avatar.color-acento-botones.p-3(x="3.1%" y="63.8%" )
          img(src='@/assets/componentes/comparacion.svg' alt='AvatarTop')
          .tarjeta.color-secundario
            .text-black.p-4.text-small
              h2.text-center De comparación
              p Son los productos que son sujetos a comparación con otros similares, antes de ser comprados por el cliente. Usualmente se evalúa la calidad, precio, diseño, marca, por lo que puede implicar que se visiten varios establecimientos previo a la compra. En este rubro pueden incluirse bienes como vehículos, computadoras o celulares.

      .tarjeta-avatar.color-acento-botones.p-3(x="3.1%" y="78.4%" )
          img(src='@/assets/componentes/especialidad.svg' alt='AvatarTop')
          .tarjeta.color-secundario
            .text-black.p-4.text-small
              h2.text-center De especialidad
              p Son todos los productos que tienen el mercado objetivo muy estrecho y su obtención obedece a casos muy especiales en los que pocas empresas se encuentran, es normal encontrar esta categoría en empresas tecnológicas con casos como procesadores o repuestos de máquinas especiales para ciertos procesos.
      .tarjeta-avatar.color-acento-botones.p-3(x="3.1%" y="93.4%" )
          img(src='@/assets/componentes/noBuscados.svg' alt='AvatarTop')
          .tarjeta.color-secundario
            .text-black.p-4.text-small
              h2.text-center No buscados
              p Estos bienes suelen ser desconocidos por el comprador, o bien, aún conociéndolos, no son de su interés. Usualmente son productos innovadores que no se han masificado en un mercado concreto, como aspiradoras robóticas o detectores de humo, o productos de baja demanda como enciclopedias o seguros de vida.

      .tarjeta-avatar.color-acento-botones.p-3(x="49.6%" y="31.8%" )
          img(src='@/assets/componentes/negocios.svg' alt='AvatarTop')
          .tarjeta.color-secundario
            .text-black.p-4.text-small
              h2.text-center De negocios
              p Son bienes destinados a continuar en procesos productivos o reventa, esto implica que son comprados por productores o distribuidores antes de llegar al consumidor final. Se clasifican en 7 categorías.

      .tarjeta-avatar.color-acento-botones.p-3(x="28.8%" y="40.8%" )
          img(src='@/assets/componentes/equipoMayor.svg' alt='AvatarTop')
          .tarjeta.color-secundario
            .text-black.p-4.text-small
              h2.text-center Equipo mayor
              p Comprende bienes de gran escala física, como maquinaria pesada, edificios o generadores eléctricos. Tienen una incidencia directa sobre la operación de los negocios dado su alto costo y utilidad.

      .tarjeta-avatar.color-acento-botones.p-3(x="29.1%" y="55.8%" )
          img(src='@/assets/componentes/equipoMayor.svg' alt='AvatarTop')
          .tarjeta.color-secundario
            .text-black.p-4.text-small
              h2.text-center Materias primas
              p Son los insumos naturales utilizados de forma directa para ser transformados en un nuevo producto. Por ejemplo, la leche para la producción de queso, o la carne para la elaboración de embutidos.
      .tarjeta-avatar.color-acento-botones.p-3(x="28.7%" y="70.7%" )
          img(src='@/assets/componentes/materialesProcesados.svg' alt='AvatarTop')
          .tarjeta.color-secundario
            .text-black.p-4.text-small
              h2.text-center Materiales procesados
              p también son utilizados para ser transformados en un producto, pero a diferencia de la materia prima, han sido objeto de procesamiento antes de incorporarse al nuevo ciclo productivo. Como ejemplo de estos, se puede hacer mención a las láminas de acero o a los componentes químicos, así como la harina o el azúcar utilizados para producir pan.
      .tarjeta-avatar.color-acento-botones.p-3(x="28.7%" y="85.7%" )
          img(src='@/assets/componentes/serviciosNegocios.svg' alt='AvatarTop')
          .tarjeta.color-secundario
            .text-black.p-4.text-small
              h2.text-center Servicios de negocios
              p incluye aquellos servicios necesarios y derivados de la operación, su naturaleza es intangible pero su aporte es tan necesario como el de los demás productos. En esta categoría se incluyen servicios de mantenimiento y reparación, asesorías financieras o de publicidad.

      .tarjeta-avatar.color-acento-botones.p-3(x="68.9%" y="49.1%" )
          img(src='@/assets/componentes/equipoAccesorio.svg' alt='AvatarTop')
          .tarjeta.color-secundario
            .text-black.p-4.text-small
              h2.text-center Equipo accesorio
              p Incluye bienes de menor tamaño como las herramientas o equipos portátiles, no hacen parte de los productos terminados, pero aportan en su producción. Ejemplo de estos son el mobiliario, las herramientas o los computadores. Su periodo de vida suele ubicarse en un intermedio entre los inventarios y el equipo mayor.
      .tarjeta-avatar.color-acento-botones.p-3(x="68.9%" y="64.2%" )
          img(src='@/assets/componentes/componentes.svg' alt='AvatarTop')
          .tarjeta.color-secundario
            .text-black.p-4.text-small
              h2.text-center Componentes
              p Corresponden a los bienes terminados y listos para ensamblarse en la producción de un producto de mayores dimensiones. Por ejemplo, los chips para una computadora o las bujías y llantas para un automóvil.
      .tarjeta-avatar.color-acento-botones.p-3(x="68.9%" y="77.9%" )
          img(src='@/assets/componentes/suministrosOperacion.svg' alt='AvatarTop')
          .tarjeta.color-secundario
            .text-black.p-4.text-small
              h2.text-center Suministros de operación
              p Son utilizados en la operación y producción de los bienes, pero no se incorporan al mismo; usualmente son de bajo costo y tiene una duración corta. Ejemplo de estos son consumibles como la gasolina, lubricantes, pintura o tornillos.

      .tarjeta-avatar.color-acento-botones.p-3(x="82%" y="31.8%" )
          img(src='@/assets/componentes/consumo.svg' alt='AvatarTop')
          .tarjeta.color-secundario
            .text-black.p-4.text-small
              h2.text-center Según su duración
              p el criterio para clasificar los productos es la cantidad de usos que se espera obtener de ellos, el tiempo que durará siendo útil y si es tangible o intangible.

      .tarjeta-avatar.color-acento-botones.p-3(x="82.1%" y="48.8%" )
          img(src='@/assets/componentes/Local.svg' alt='AvatarTop')
          .tarjeta.color-secundario
            .text-black.p-4.text-small
              h2.text-center No duraderos
              p Son aquellos bienes tangibles de un solo uso o de consumo rápido. Por ejemplo, alimentos como las bebidas gaseosas o las frituras, productos de aseo como desodorantes o bienes no reutilizables como el papel o la cartulina.

      .tarjeta-avatar.color-acento-botones.p-3(x="82.1%" y="63.8%" )
          img(src='@/assets/componentes/Regional.svg' alt='AvatarTop')
          .tarjeta.color-secundario
            .text-black.p-4.text-small
              h2.text-center Duraderos
              p En este rubro se incluyen bienes que pueden ser reutilizados un número significativo de veces. Por ejemplo, los electrodomésticos, las herramientas de ferretería o las prendas de vestir.

      .tarjeta-avatar.color-acento-botones.p-3(x="82.1%" y="78.5%" )
          img(src='@/assets/componentes/Nacional.svg' alt='AvatarTop')
          .tarjeta.color-secundario
            .text-black.p-4.text-small
              h2.text-center Servicios
              p A diferencia de las dos subcategorías anteriores, estos productos son intangibles, es decir, carecen de materia, por lo que no pueden tocarse. Debido a la dificultad para ser medidos, suelen requerir de una mayor credibilidad para ser ofertados. Productos que pueden cumplir con estos criterios son los servicios de reparación, los cortes de cabello o el lavado de ropa.
      .tarjeta-avatar.color-acento-botones.p-3(x="82.1%" y="93.6%" )
          img(src='@/assets/componentes/Multinacional.svg' alt='AvatarTop')
          .tarjeta.color-secundario
            .text-black.p-4.text-small
              h2.text-center Multinacional
              p A diferencia de las dos subcategorías anteriores, estos productos son intangibles, es decir, carecen de materia, por lo que no pueden tocarse. Debido a la dificultad para ser medidos, suelen requerir de una mayor credibilidad para ser ofertados. Productos que pueden cumplir con estos criterios son los servicios de reparación, los cortes de cabello o el lavado de ropa.

    h3.mb-4
      span.colorText-verde <u>Fichas técnicas</u>   

    .row.mb-5.mt-5
      .col-7
        p.mb-4 La elaboración de los productos suele constituirse como una actividad altamente repetitiva, en la que se siguen una serie de lineamientos que propenden por la estandarización del proceso. <span style='color:#5F9025;'>Esto se debe a que la uniformidad en las líneas de producción permite la fabricación en serie de bienes con un nivel de calidad muy semejante entre ellos,</span> lo que garantiza satisfacción en los clientes, mientras que de forma simultánea permite prever los requerimientos de insumos necesarios para mantener la operación durante franjas de tiempo determinadas.
        .cajon.Color-Bkg-Cajon.p-4.mb-4.Neg-Izq.position-relative
          p.color-acento-contenido <span style='color:#5F9025;'>La ficha técnica se erige como un documento identificador de la composición de cualquier producto que ha requerido de algún tipo de proceso para su elaboración.</span> Usualmente incluye la descripción técnica y objetiva de los insumos utilizados en la producción del producto, por lo que es una herramienta de especial utilidad en la obtención de certificaciones de calidad.
      .col-5
        img(src='@/assets/curso/cajas.png')

    .shadow.p-3.mb-5.bg-body.rounded.fondoBanner-1
      .row.align-items-center
        .col-1
        .col-3
          img(src='@/assets/curso/cargandoCajas.png')
        .col-1
        .col-1
          img(src='@/assets/curso/figRio.svg')
        .col-6      
          p Las empresas pueden clasificarse según diversos criterios, y así, abordar definiciones, estrategias y medidas de forma conjunta en función de las necesidades de cada usuario. La siguiente figura infográfica presenta algunos de los sistemas de clasificación más utilizados en nuestro entorno:

    p Su uso resulta bastante común en la industria alimenticia, ya que le permite al consumidor un acercamiento a los ingredientes utilizados para la elaboración del alimento procesado que piensa adquirir.  Esto sin contar con los requerimientos normativos, que en muchas ocasiones exigen esta información detallada para aprobar su comercialización.

    .row.mb-5.mt-5
      .col-3
        p Si se desea diseñar una ficha técnica para propósitos de calidad de producción se recomienda que incluya por lo menos los siguientes elementos:
      .col-9
        SlyderA(tipo="b")
          .row.fondoBanner-4
            .col-md-3.mb-4.mb-md-0
              figure
                img(src='@/assets/template/icono1.svg', alt='Nombre del producto')

            .col-md-9
              p.text-bold.mt-3 Nombre del producto
              p.me-5 debe diferenciarse de cualquier otro producto elaborado en la compañía, lo que implica hacer precisiones respecto a tamaños o presentaciones, por ejemplo, diferenciar entre versiones líquidas o sólidas. 
          div
            .row.fondoBanner-4
              .col-md-3.mb-4.mb-md-0.align-items-center
                figure
                  img(src='@/assets/template/icono2.png', alt='Tiempo de preparación')
              .col-md-9
                p.text-bold.mt-3 Tiempo de preparación
                p.me-5 Si requieren someterse a procesos de cocción o enfriamiento, se puede especificar el tiempo que deben permanecer en cada etapa. Por ejemplo, la pasteurización de la leche implica someterla a bajas y altas temperaturas por periodos de tiempo determinados.
          div
            .row.fondoBanner-4
              .col-md-3.mb-4.mb-md-0
                figure
                  img(src='@/assets/template/icono3.png', alt='Mano de obra requerida')
              .col-md-9
                p.text-bold.mt-3 Mano de obra requerida
                p.me-5 Puede detallarse por cargos operativos y suele presentarse en horas de trabajo. Esto significa, el tiempo que un operario le destina para aplicar todos los procedimientos requeridos a cada unidad producida
          div
            .row.fondoBanner-4
              .col-md-3.mb-4.mb-md-0
                figure
                  img(src='@/assets/template/icono4.png', alt='Equipamiento usado')
              .col-md-9
                p.text-bold.mt-3 Equipamiento usado
                p.me-5 Algunos productos demandan el uso de una maquinaria específica. Es importante dejar esto en claro para evitar reprocesos, retrasos en las líneas de producción o la utilización errónea de maquinaria que altere la disposición del producto
          div
            .row.fondoBanner-4
              .col-md-3.mb-4.mb-md-0
                figure
                  img(src='@/assets/template/icono5.png', alt='Tamaño de porción')
              .col-md-9
                p.text-bold.mt-3 Tamaño de porción
                p.me-5 Según la presentación del producto, puede expresarse en litros, kilos, libras o gramos, entre otros.
          div
            .row.fondoBanner-4
              .col-md-3.mb-4.mb-md-0
                figure
                  img(src='@/assets/template/icono6.png', alt='Imagen del producto')
              .col-md-9
                p.text-bold.mt-3 Imagen del producto
                p.me-5 Para apoyar la identificación del bien, pueden incluirse imágenes orientativas de la presentación del producto, el logo o información relevante adicional.
          div
            .row.fondoBanner-4
              .col-3.mb-4.mb-md-0
                figure
                  img(src='@/assets/template/icono7.png', alt='Instrucciones especiales')
              .col-md-9
                p.text-bold.mt-3 Instrucciones especiales
                p.me-5 Ciertos productos pueden requerir tratamientos especiales, por ejemplo si son delicados o perecederos, o si requieren de ciertas condiciones ambientales para su conservación. Este aspecto toma vital importancia cuando los productos abandonan la fábrica de producción y son manipulados por otros agentes del canal de distribución que carecen de los conocimientos técnicos.
            
    #planmerca.titulo-segundo
      .h4 2.3 Plan de Mercadeo

      .row.mb-5.mt-5
        .col-5
          img(src='@/assets/curso/manosPC.png')      
        .col-7
          .cajon.Color-Bkg-Cajon.p-4.mb-4.mt-4.Neg-Der.position-relative
            .titulo-sexto.color-acento-contenido
              span El plan de mercadeo es un documento en el que se plasman los objetivos que espera alcanzar la empresa en materia comercial, así como las estrategias a implementar para hacerlo posible junto con el costo para ejecutarlas. Su utilidad radica en la correcta <span style='color:#5F9025;'>planeación y destinación de recursos con suficiente anticipación</span> para garantizar que los flujos de efectivo se destinen de forma correcta y para que los esfuerzos se encaminen hacia una meta clara y definida.
          p.mb-4 Comúnmente, el plan de mercadeo se formula para ser ejecutado en periodos de un año, donde al final del ejercicio, se hará una evaluación en la que se compare lo proyectado con lo efectivamente alcanzado. Para posibilitar esto último, deben cuantificarse todos los elementos que aporten a hacer un juicio por parte de los evaluadores. Lo anterior conlleva canales de comunicación efectivos y oportunos con el personal del área comercial, los proveedores y los clientes, así como con todos los demás integrantes de la cadena de distribución del producto.
    h3.mb-4
      span.colorText-verde <u>Elementos</u>   
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
