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

    #producto.titulo-segundo.color-acento-contenido
      h2 2.2 Producto
    //banner dos columnas imagen izquierda
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
    //banner dos columna imagen derecha
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
          p Su objetivo principal es facilitar la estandarización de los procesos en la empresa productora, puesto que le entrega a los operarios la información necesaria para la elaboración de cada producto. Además, facilita labores de acompañamiento de personal ajeno a la producción como los auditores.

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
            
    #planmerca.titulo-segundo.color-acento-contenido
      h2 2.3 Plan de Mercadeo
      //banner dos columnas imagen izquierda linea verde
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
    p Como se ha mencionado el plan de mercadeo es un documento, y por lo tanto su elaboración y formato esta sometido a juicio del personal estratégico que lo diseñe. Sin embargo, es recomendable que dentro de su estructura se incluyan por lo menos tres grandes secciones así:   

    .row.align-items-center
      .col-2.bg-tabla2.mb-4
        p.text-white.Text-mediano Marketing analítico
    .row.mb-5.mt-5
      .col-7
        p.mb-4 <span style='color:#5F9025;'>En esta primera sección se debe hacer un análisis de la empresa, el mercado objetivo y la competencia.</span> La información recolectada en esta etapa resulta de vital importancia para las medidas que se tomen posteriormente, puesto que las estrategias deben atacar aquellas amenazas o debilidades identificadas.
        .cajon.Color-Bkg-Cajon.p-4.mb-4.Neg-Izq.position-relative
          p.color-acento-contenido Es recomendable que el estudio aborde los factores internos y externos de la empresa, lo que implica evaluar al personal de ventas, la reputación del producto, los precios de los bienes sustitutos, la demografía de la población, y cualquier otro factor que pueda inferir en los resultados comerciales. Es recomendable <span style='color:#5F9025;'>aplicar una matriz FODA</span> que permita maniobrar con las fortalezas, oportunidades, debilidades y amenazas de forma efectiva.
          img.hijoHoja(src='@/assets/curso/hoja.png')
      .col-5
        img(src='@/assets/curso/ejecutivo.png')

    p La siguiente figura 5 aborda los cuatro componentes principales del marketing analítico y algunas de las actividades que pueden tenerse en cuenta para documentar el plan de mercadeo.

    .titulo-sexto.color-acento-contenido.ms-5
      span Figura 5. Componentes del Marketing analítico
    figure
      img(src='@/assets/curso/MarketingAnalitico.jpg')
      figcaption.mt-5
        p Nota. Sena (2021).

    .row
      .col-3.bg-tabla2.mb-4.mt-4
        p.text-white.Text-mediano.text-center.align-items-center Marketing estratégico
    p una vez se ha recopilado toda la información relevante para la gestión comercial, se procede a la postulación de metas que puedan ser alcanzados con los recursos disponibles. A partir de ello, se plantean las estrategias que represente una mayor relación costo – beneficio y se estructuran incluyendo los objetivos específicos y las tareas a desarrollar.

    .row.mb-5.mt-5
      .col-4
        p <span style='color:#5F9025;'>En primer lugar, se debe estimar la demanda a partir de la información recolectada,</span> por ejemplo si se espera tener una participación del 10% del mercado, y en la población abordada se venden 1.000 unidades de productos similares, la meta de ventas debe ser de 100 unidades en el periodo de tiempo definido. A partir de ello se define la fuerza de ventas que será necesaria, y la implementación de medidas adicionales asociadas a cobertura, publicidad, distribución entre otros.
        .row
          .col-9
          .col-3.mt-2
            img(src="@/assets/curso/figRio1.svg")
      .col-4
        img(src="@/assets/curso/trabajando.png")
      .col-4
        .row
          .col-3
            img(src="@/assets/curso/figRio1.svg")
          .col-9
        p.mt-4 Muchas interpretaciones pueden derivarse del análisis anterior, definir el mercado actual y el mercado meta traza un camino a seguir y un objetivo claro, pero las estrategias deben ser lo suficientemente precisas para contemplar aspectos como la segmentación del mercado, las variaciones en los precios, y las ventajas competitivas con las que se espera contar para favorecer la elección del producto propio sobre el producto de la competencia.
    p.mt-4 en esta fase se materializan las estrategias propuestas, puesto que se finaliza el diseño, y se implementan las tareas definidas. Previo y durante la etapa de ejecución se debe llevar un control de las expensas necesarias para actualizar el control presupuestal y tener claridad sobre la disponibilidad del efectivo de manera permanente. 

    .shadow.p-3.mb-5.bg-body.rounded.fondoBanner-1
      .row.align-items-center
        .col-1
        .col-3
          img(src='@/assets/curso/viendoPC.png')
        .col-1
        .col-1
          img(src='@/assets/curso/figRio.svg')
        .col-6      
          p El marketing operativo comprende 4 pasos en los que se hace uso de toda la información recolectada en el marketing analítico y estratégico:

    SlyderB.mb-5.fondoBanner-5(:datos="datosSlyder")

    h3.mb-4
      span.colorText-verde <u>Importancia en el ciclo productivo</u>

    p.mb-4 Generalmente, la demanda de los productos obedece a muchos factores sobre los cuales la empresa no siempre tiene control; condiciones económicas, políticas públicas y la competencia, son solo algunos de ellos. Debido a esto, lo más habitual a la hora de diseñar un ciclo productivo, es que el plan de mercadeo haga de punto de partida en el ciclo productivo y posteriormente se debe tener en cuenta lo siguiente:

    figure
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    #costo.titulo-segundo.color-acento-contenido.mt-4.mb-4
      h2 2.4 Elementos del costo

    .row.mt-4
      .col-4
        img(src='@/assets/curso/hombrePC.png', alt='Productos')
      .col-8
        .row.ms-1
          .col-1
            img(src='@/assets/curso/figRio.svg')
          .col-11
            p <span style="font-weight: bold;">El costo de producción es el conjunto de inversiones efectuadas por la empresa y de las cuales se espera una retribución o beneficio en el corto plazo;</span> la mecánica más habitual consiste en la compra de insumos para ser sometidos a transformación, seguidos de un almacenamiento en forma de inventario que finaliza con la venta al cliente. Por su naturaleza, <span style='color:#5F9025;'>se encuentran estrechamente relacionados con el objeto social de cualquier empresa y son un elemento protagónico en la toma de decisiones estratégicas.</span>
            .cajon.Color-Bkg-Cajon.p-4.mb-4.Neg-Izq.position-relative
              p <span style="font-weight: bold;">Los costos si bien implican erogaciones de capital, crean una expectativa de recuperación de los fondos invertidos a través de la venta de los productos transformados,</span> mientras que los gastos suelen funcionar a la inversa, su pago es la consecuencia de un beneficio pasado o presente, por lo que tras la salida de los recursos, no se espera ningún tipo de contraprestación; ejemplo de ello, es la <span style='color:#5F9025;'>comisión que reciben los vendedores por una buena gestión comercial en el mes anterior.</span>
              img.hijoHoja(src='@/assets/curso/hoja.png')
    h3.mt-4.mb-4 Materia prima

    .row.mb-5.mt-5
      .col-7
        p.mb-4 <span style="font-weight: bold;">La materia prima directa se clasifica como tal si da cumplimiento a los dos siguientes conceptos: Materialidad e importancia relativa.</span> El primero se asocia al costo de la inversión o su significancia en la elaboración, es decir, qué tanto valor económico aporta al costo total. Como ejemplo de lo anterior, se considera materia prima directa la tela en la confección de los pantalones, donde resulta evidente que no solo representa uno de los insumos que mayor valor económico atribuyen a la producción, sino también aquel que tiene mayor participación en la composición del producto terminado.
        .cajon.Color-Bkg-Cajon.p-4.mb-4.Neg-Izq.position-relative
          p.color-acento-contenido <span style='color:#5F9025;'>La importancia relativa se relaciona con lo indispensable de un material en el proceso de producción.</span> Así, continuando con el ejemplo anterior, los botones del pantalón también pueden ser considerados materia prima directa, pues si bien, no son tan costosos, son necesarios para dar por terminada su producción.
      .col-5
        img(src='@/assets/curso/materiasPrimas.png')

    p En palabras de Guarnizo y Cárdenas (2015) la materia prima no solo se compone por el valor de compra de los insumos, sino también, por todas aquellas erogaciones que se asocian a su adquisición y disposición. Por ejemplo, los costos de embalaje, el bodegaje, las pérdidas, son algunos elementos que encajarían dentro de la definición de materia prima. 
    p En la siguiente figura 6 se presentan a modo orientativo algunos de los elementos que constituyen el costo de la materia prima, separadas en función de la fase en la que esta se encuentra dentro de la producción:
    .titulo-sexto.color-acento-contenido.ms-5.mb-4.mt-4
      span Figura 6. Costos asociados a la materia prima
    figure
      img(src='@/assets/curso/costosMateriaPrima.png')
      figcaption.mt-4.mb-4 Nota. Adaptado de Guarnizo y Cárdenas (2015).
    h3.mb-4 Mano de obra
    p.mb-4 La mano de obra se constituye como el segundo elemento de los costos de producción, al cual se asigna el valor del trabajo realizado por las personas que se involucran con la producción y transformación de los insumos. Al igual que la materia prima, puede clasificarse como directa o indirecta
    .row.mb-5.mt-5
      .col-5
        img(src='@/assets/curso/mujerTrabajando.png')      
      .col-7
        .cajon.Color-Bkg-Cajon.p-4.mb-4.mt-4.Neg-Der50.position-relative
          .titulo-sexto.color-acento-contenido
            span En principio, aquellos funcionarios cuya labor es trabajar transformando los insumos, son considerados mano de obra directa, por ejemplo, el operario encargado de ordeñar las vacas en una granja pecuaria. Por otro lado, la mano de obra indirecta incluye la labor desempeñada por trabajadores de apoyo o dirección del área, pero sin participar directamente sobre la producción. Ejemplo de esto son los vigilantes o supervisores de las áreas donde se encuentra el área de producción.
        p.mb-4 Respecto a los elementos que componen el costo de la mano de obra, se deben tener presentes todas las remuneraciones asociadas a la relación con el trabajador, esto incluye las prestaciones sociales, la seguridad social, las bonificaciones y cualquier otra erogación que se de como retribución al trabajo prestado. Otros costos que podrían incluirse si la administración así lo considera son gastos accesorios como los de reclutamiento, auxilios, capacitaciones, entre otros. 

    .row.mb-5.mt-5
      .col-7
        p.mb-4 <span style="color: #5F9025;">Agrupan todas las erogaciones indirectas a la producción, incluye la materia prima y mano de obra que se catalogaron previamente como indirectas,</span> y adicionan otros conceptos que no pueden atribuirse o destinarse de forma específica a cada unidad producida.
        .cajon.Color-Bkg-Cajon.p-4.mb-4.Neg-Izq.position-relative
          p.color-acento-contenido <span style='font-weight: bold;'>Esta categoría absorbe todo valor residual que no cumpla con la clasificación de insumo directo, por lo que de su precisión en el cálculo, depende la correcta estimación de los costos de producción.</span> Ejemplo de otros rubros que encajan con esta clasificación son los mantenimientos hechos a las maquinarias, el combustible que estas requieren para producir o el arrendamiento del inmueble donde se ejecuta la producción.
      .col-5
        img(src='@/assets/curso/manosPC2.png')

    #clase.titulo-segundo.color-acento-contenido.mt-4.mb-4
      h2 2.5 Clasificación
    ImagenInfografica.color-acento-botones.mb-5
      template(v-slot:imagen)
        figure
          img(src='@/assets/template/claseCostos.png', alt='Clase de costos')
      .tarjeta-avatar.color-acento-botones.p-3(x="3.5%" y="44.8%" )
          img(src='@/assets/componentes/relacionProduccion.svg' alt='AvatarTop')
          .tarjeta.color-secundario
            .text-black.p-4.text-small
              p Bajo este modelo, los costos se discriminan en variables, que son aquellos que tienen una relación directa con las unidades producidas, por ejemplo, a mayor cantidad de camisas a producir, mayor la cantidad de tela a utilizar. Como contraparte están los costos fijos, que no se ven afectados por la producción, aquí podemos encontrarnos rubros como el salario de las aseadoras de planta de producción
      .tarjeta-avatar.color-acento-botones.p-3(x="38.8%" y="45.4%" )
          img(src='@/assets/componentes/relacionProducto.svg' alt='AvatarTop')
          .tarjeta.color-secundario
            .text-black.p-4.text-small
              p La regla aplicable a este sistema nos lleva a determinar si existe o no una relación directa entre el insumo y la generación del producto terminado. Se consideran directos los costos asignables a un producto en específico, como lo sería la materia prima objeto de transformación, o el salario pagado al operario que trabaja en una línea de producción en concreto. Los costos indirectos, por su parte, corresponden a aquellos que, aunque tienen relación con la producción, son comunes a varios tipos de productos o cuesta asignarlos de forma directa a uno en específico.
      .tarjeta-avatar.color-acento-botones.p-3(x="78%" y="45.4%" )
          img(src='@/assets/componentes/relacionPlaneacion.svg' alt='AvatarTop')
          .tarjeta.color-secundario
            .text-black.p-4.text-small
              p En primer lugar están los costos estimados, que surgen de metodologías de análisis y observación. No son exactos y su margen de error está condicionado al nivel de detalle en la que se haya efectuado los procedimientos de cálculos. Son aplicables a los insumos que no son materiales en el proceso de elaboración. En segundo lugar se ubican los costos estándar, utilizados en empresas con volúmenes de producción significativos y bajo un sistema altamente repetitivo. Analizan la información histórica disponible, y anticipan el costo de producción a partir de ello, su margen de error suele ser muy bajo dado que trabajan con variables ya conocidas. 
    #calculo.titulo-segundo.color-acento-contenido.mt-4.mb-4
      h2 2.6 Cálculo

    .row.mt-5
      .col-7
        p.mb-4 Si bien previamente se presentó una conceptualización de los elementos del costo de producción, determinar su valor es un proceso que demanda la aplicación de diversas metodologías para cada uno de ellos. A continuación se presentan los sistemas de más fácil accesibilidad para determinar el valor de cada uno de los elementos del costo
      .col-5
    .row.mb-5.mt-2.fondoBanner-2
      .col-7
        h3.mb-4.ms-4
          span.text-white <u>Materia prima</u>
          p.mt-4.text-small En este rubro se incluyen todos los insumos materiales para ser utilizados en la producción. En el ámbito financiero, este tipo de elementos se clasifican como inventarios, y los sistemas utilizados para su valoración se encuentran regulados en la normativa colombiana. En la actualidad, se puede hacer uso de los dos siguientes sistemas:
        
      .col-5  
        img.Neg-Top140(src='@/assets/curso/calculadora.png')
        .row
            .col-8
            .col-4
              img.Neg-Top(src='@/assets/curso/hoja.png')
      .row
        .col-5
          img.ms-4(src='@/assets/curso/supervisora.png')  
        .col-7
          LineaTiempoD.color-acento-contenido.ms-4
            .row(numero="1" titulo="Sistema de inventarios periódico")
              .col-12
                p.text-small Bajo este modelo, el costo de la materia prima se determina a una fecha de corte, a través del conteo físico de las unidades que no han sido utilizadas o vendida, es decir, el inventario final. La fórmula a utilizar es conocida como el juego de inventarios y se presenta así: 
                .row
                  .col-3
                  .col-6.bordeVerde
                    span  Compra de materias primas
                    span  (-) Devoluciones y descuentos
                    span  Compras Netas
                    span  (-) Inventario Final
                    span  Materias primas utilizadas
                  .col-3
                .row
                  .col-12.bg-color-grisClaro
                    p.me-4.ms-4.mt-4 Es un sistema de fácil y económica aplicación, puesto que el esfuerzo recae sobre un trabajo manual y físico, en la actualidad ha ido perdiendo relevancia debido a las facilidades tecnológicas que permiten hacer uso de herramientas más precisas. <span style="color: #5F9025;">El principal problema que surge de este modelo es que para estimar el costo es necesario realizar todo el proceso de verificación de existencias,</span> lo que implica que no se puede tener el dato exacto de manera inmediata y de forma permanente. 
                .row
                  .col-4
                    img.mt-4.justify-content-center(src='@/assets/curso/dinero.svg')  
                  .col-8
                    p.mt-4 Por ejemplo, si una empresa hace compras por $ 100 y a final del año le queda un saldo de materiales por valor de $ 20, se deduce que el costo de los insumos fue de $ 80, bien sea porque hayan sido utilizados en la producción, o se hayan deteriorado o perdido. Para calcular este costo fue necesario determinar el valor del inventario final, situación que demanda siempre un conteo físico, y por lo tanto, hace muy exigente la estimación del costo si se quiere conocer de manera frecuente. 
            .row(numero="2" titulo="Sistema de inventarios permanente")
              .col-12
                p.text-small Este modelo ofrece una medición más precisa de las materias primas, como su nombre lo indica, se tendrá claridad de la cifra en cualquier momento y por lo tanto, la oportunidad de la información es mucho mayor a la de su contraparte. Las metodologías utilizadas son las siguientes:
              .row
                .col-2
                  img.Neg-Izq140(src='@/assets/curso/circulo.svg') 
                .col-9.bg-color-grisClaro
                  h3.mb-4
                    span.colorText-verde Primeras en entrar, primeras en salir (PEPS)
                  p Las unidades utilizadas en la producción serán dispuestas en el mismo orden en el que fueron ingresadas al inventario. Así, los saldos de materia prima siempre corresponderán a las últimas unidades compradas.
              .row
                .col-2
                  img.Neg-Izq140(src='@/assets/curso/circulo.svg') 
                .col-9.bg-color-grisClaro
                  h3.mb-4
                    span.colorText-verde Últimas en entrar, primeras en salir (UEPS)
                  p Su mecánica es opuesta al anterior, puesto que la materia prima a utilizar será la última comprada, esto lleva a que los saldos del inventario final se compongan por la materia prima adquirida con mayor antigüedad, esto puede generar desfases en los precios y llevar a un sesgo en la interpretación de la información.
              .row
                .col-2
                  img.Neg-Izq140(src='@/assets/curso/circulo.svg') 
                .col-9.bg-color-grisClaro
                  h3.mb-4
                    span.colorText-verde Promedio ponderado
                  p El sistema funciona afectando el costo de la materia prima en función de todas las compras realizadas en el tiempo. Esto significa que las variaciones de los precios ajustan el valor promedio de todas las existencias disponibles en el inventario
              .row
                .col-12.me-2.ms-2.mt-4.bg-color-azulClaro
                  p En Colombia, la legislación tributaria solo permite el uso de los sistemas PEPS y promedio ponderado, dado que son los que gozan de mayor precisión a la hora de determinar el costo de los inventarios. Cualquier de los dos, hace uso de una herramienta conocida como Kárdex, que consta de una hoja de trabajo en la que se computan las compras efectuadas en orden cronológico; de esta misma forma, se reconocen las salidas cuando se utilizan en el proceso de producción. 
    p.mt-4.mt-4 <span style="color: #5F9025;">A continuación se presentan dos hojas de Kárdex,</span> una diligenciada mediante el sistema PEPS y la otra usando el modelo del promedio ponderado, para ilustrar mejor la situación se presenta por medio de un ejercicio práctico:
    .shadow.p-3.mb-5.mt-5.bg-body.rounded.fondoBanner-1
      .row.align-items-center
        .col-1
        .col-3
          img(src='@/assets/curso/calculadoraPapel.png')
        .col-1
        .col-1
          img(src='@/assets/curso/figRio.svg')
        .col-6      
          p Una empresa cuenta con 30 unidades de material a cierre de febrero, con un valor unitario de $ 10.000. El 3 de marzo compran 15 unidades a 13.000 y el 12 de marzo 25 unidades a 15.000. Posteriormente se efectúan dos pedidos para producción, la orden 11 por 20 unidades y la 12 por 18. Se determina el inventario final y el costo de la materia prima a través de los dos sistemas así, ver tablas 1 y 2:
    .titulo-sexto
      span <span style='font-weight: bold;'>Tabla 1</span> Hoja de kárdex bajo sistema PEPS
    .tabla-b.mb-5
      table.table-small.table-responsive
        thead.text-center.bg-color-verde-claro
          tr 
            <th rowspan="2"> Detalle</th>
            <th rowspan="2"> Valor Unitario</th>
            <th colspan="3"> Entradas</th>
            <th colspan="3"> Salidas</th>
            <th colspan="2"> Saldos</th>
          tr
            th cantidad
            th Vr. Unit
            th Total
            th cantidad
            th Vr. Unit
            th Total
            th cantidad
            th Vr. Unit        
        caption Nota. Sena (2021).
        tr
          td Inventario inicial
          td  10.000 
          td 30
          td 10.000
          td 300.000
          td
          td
          td
          td 30
          td 300.000 
        tr
          td Compra 3 de marzo
          td 13.000
          td 15
          td 13.000
          td 195.000
          td 
          td
          td
          td 45
          td 495.000
        tr
          td Compra 12 de marzo
          td 15.000
          td 25
          td 15.000
          td 375.000
          td
          td
          td
          td 70
          td 870.000
        tr
          <td rowspan="3">Orden de producción 11 (20 unidades)</td>
          td 10.000
          td
          td
          td
          td 20
          td 10.000
          td 200.000
          td
          td 670.000
        tr
          td 13.000
          td
          td
          td
          td 
          td 
          td 
          td 
          td 670.000
        tr
          td 15.000
          td
          td
          td
          td 
          td 
          td 
          td 
          td 670.000
        tr
          <td rowspan="3">Orden de producción 12 (18 unidades)</td>
          td 10.000
          td
          td
          td
          td 10
          td 100.000
          td
          td 570.000
        tr
          td 13.000
          td
          td
          td
          td 8 
          td 13.000
          td 104.000
          td 
          td 670.000
        tr
          td 15.000
          td
          td
          td
          td  
          td 
          td 
          td 
          td 466.000

    .titulo-sexto
      span <span style='font-weight: bold;'>Tabla 2</span> Hoja de kárdex bajo sistema promedio ponderado
    .tabla-b.mb-5
      table.table-small.table-responsive
        thead.text-center.bg-color-verde-claro
          tr 
            <th rowspan="2"> Detalle</th>
            <th rowspan="2"> Valor Unitario</th>
            <th colspan="3"> Entradas</th>
            <th colspan="3"> Salidas</th>
            <th colspan="2"> Saldos</th>
          tr
            th cantidad
            th Vr. Unit
            th Total
            th cantidad
            th Vr. Unit
            th Total
            th cantidad
            th Vr. Unit        
        caption Nota. Sena (2021).
        tr
          td Inventario inicial
          td  10.000 
          td 30
          td 10.000
          td 300.000
          td
          td
          td
          td 30
          td 300.000 
        tr
          td Compra 3 de marzo
          td 11.000
          td 15
          td 13.000
          td 195.000
          td 
          td
          td
          td 45
          td 495.000
        tr
          td Compra 12 de marzo
          td 12.429
          td 25
          td 15.000
          td 375.000
          td
          td
          td
          td 70
          td 870.000
        tr
          td Orden de producción 11 (20 unidades)
          td 12.429
          td
          td
          td
          td 20
          td 12.429
          td 248.571
          td  50
          td 621.429
        tr
          td Orden de producción 12 (18 unidades)
          td 12.429
          td
          td
          td
          td 18
          td 12.429
          td 223.714
          td 32
          td 397.714

    p.mt-5.mb-5 De la comparación de las dos hojas de Kárdex se evidencian diferencias en la valoración, pese a que la situación práctica fue la misma. Si bien la totalidad de la materia prima adquirida es la misma, la asignación a las órdenes de producción varía, lo que también afecta el valor del inventario final. La elección del sistema a utilizar dependerá del juicio del encargado del sistema de costeo, ambos modelos son adecuados y ofrecen un nivel razonable de precisión, ver tabla 3.
    .row
      .col-3
      .col-6
        .titulo-sexto
          span <span style='font-weight: bold;'>Tabla 3</span>  Comparativa sistemas de valuación de inventario 
        .tabla-a.color-acento-botones.mb-5 
          table
            caption Nota. Sena (2021).
            thead
              tr
                th 
                th PEPS
                th Promedio ponderado
            tbody
              tr
                td Costo de la materia
                td 404.000
                td 472.286
              tr
                td Inventario final
                td 466.000
                td 397.714
              tr
                td 
                td 
                td 
              tr
                td Total materia prima
                td 870.000
                td 870.000          
      .col-3

    .row
      .col-3
        h3.mb-4.ms-4
          span.colorText-verde <u>Mano de obra</u> 
      .col-9
        p.mt-5 El costo de la mano de obra en Colombia involucra las prestaciones y beneficios a los que los empleados tienen derecho. Un contrato de trabajo comprende un salario básico, unas prestaciones sociales, unos aportes parafiscales y de seguridad social, así como cualquier otra retribución asociada a las labores ejecutadas en función de su trabajo.       

    .row.mt-4.fondoBanner-2
      .col-4
        img.Neg-Top140(src='@/assets/curso/SonriePC.png', alt='Mano de obra')
      .col-8
        .row.ms-1
          .col-1
            img(src='@/assets/curso/figRio.svg')
          .col-11
            .cajon.Color-Bkg-Cajon.p-4.mb-4.Neg-Izq.position-relative
              p La normativa colombiana es muy extensa respecto a las condiciones de la contratación laboral, el código sustantivo del trabajo de 1950 presenta el compilatorio más importante en el país en este aspecto, de su interpretación se sustraen los siguientes apartados, que resultan de especial importancia para estimar el costo de la mano de obra: 

    TabsC.color-acento.contenido
      .py-3.py-md-4(titulo="Salario")
        .row
          .col-md-6.mb-4.mb-md-0
            h2 Salario
            p Constituye salario no sólo la remuneración ordinaria, fija o variable, sino todo lo que recibe el trabajador en dinero o en especie como contraprestación directa del servicio, sea cualquiera la forma o denominación que se adopte, como primas, sobresueldos, bonificaciones habituales, valor del trabajo suplementario o de las horas extras, valor del trabajo en días de descanso obligatorio, porcentajes sobre ventas y comisiones (Código Sustantivo del Trabajo, 1950, Artículo 127).        
          .col-md-6
              img(src='@/assets/template/salario.png', alt='Salario')
      .py-3.py-md-4(titulo="Horas extras")
        .row
          .col-md-6.mb-4.mb-md-0
            h2 Horas extras
            p Trabajo suplementario o de horas extras es el que excede de la jornada ordinaria, y en todo caso el que excede de la máxima legal (Código Sustantivo del Trabajo, 1950, Artículo 159).
          .col-md-6
              img(src='@/assets/template/horasExtras.png', alt='Horas extras')
        
      .py-3.py-md-4(titulo="Vacaciones")
        .row
          .col-md-6.mb-4.mb-md-0
            h2 Vacaciones
            p Los trabajadores que hubieren prestado sus servicios durante un año tienen derecho a quince (15) días hábiles consecutivos de vacaciones remuneradas (Código Sustantivo del Trabajo, 1950, Artículo 186).
          .col-md-6
              img(src='@/assets/template/vacaciones.png', alt='Vacaciones')

      .py-3.py-md-4(titulo="Cesantias")
        .row
          .col-md-6.mb-4.mb-md-0
            h2 Cesantías
            p Todo empleador está obligado a pagar a sus trabajadores, y a las demás personas que se indican en este Capítulo, al terminar el contrato de trabajo, como auxilio de cesantía, un mes de salario por cada año de servicios y proporcionalmente por fracción de año (Código Sustantivo del Trabajo, 1950, Artículo 249).
          .col-md-6
              img(src='@/assets/template/cesantias.png', alt='Cesantías')    
      
      .py-3.py-md-4(titulo="Prima")
        .row
          .col-md-6.mb-4.mb-md-0
            h2 Prima de servicios
            p El empleador está obligado a pagar a su empleado o empleados, la prestación social denominada prima de servicios que corresponderá a 30 días de salario por año, el cual se reconocerá en dos pagos, así: la mitad máximo el 30 de junio y la otra mitad a más tardar los primeros veinte días de diciembre. Su reconocimiento se hará por todo el semestre trabajado o proporcionalmente al tiempo trabajado (Código Sustantivo del Trabajo, 1950, Artículo 306).
        
          .col-md-6
              img(src='@/assets/template/prima.png', alt='Prima de servicios')
      
      .py-3.py-md-4(titulo="Intereses")
        .row
          .col-md-6.mb-4.mb-md-0
            h2 Intereses
            p Todo patrono obligado a pagar cesantía a sus trabajadores conforme al Capítulo VII Título VIII, Parte 1ª, del Código Sustantivo del Trabajo y demás disposiciones concordantes, les reconocerá y pagará intereses del 12% anual sobre los saldos que en 31 de diciembre de cada año, o en las fechas de retiro del trabajador o de liquidación parcial de cesantía, tenga este a su favor por concepto de cesantía (Ley 52, 1975, Artículo 1).
        
          .col-md-6
              img(src='@/assets/template/interesCesantias.png', alt='Intereses de cesantías')

      .py-3.py-md-4(titulo="Auxilio de transporte")
        .row
          .col-md-6.mb-4.mb-md-0
            h2 Auxilio de transporte
            p Corresponde a un elemento salarial diferente a los anteriores, puesto que su valor no depende del salario, sino que se establece un valor fijo anualmente. Como su nombre lo indica, es un auxilio para cubrir los costos de desplazamiento del empleado. Para el año 2021 su valor es de $ 106.454 según lo dispuesto en el decreto 1785 de 2020, expedido por el ministerio del trabajo, y su pago es exclusivo de los trabajadores que devenguen menos de dos salarios mínimos mensuales legales vigentes (SMMLV)
        
          .col-md-6
              img(src='@/assets/template/auxilioTransporte.png', alt='Auxilio de transporte')

    .row.mb-5.mt-5
      .col-5
        img(src='@/assets/curso/mirarGraficas.png', alt='Factores prestacionales')      
      .col-7
        .cajon.Color-Bkg-Cajon.p-4.mb-4.mt-4.Neg-Der.position-relative
          .titulo-sexto.color-acento-contenido
            span Para determinar el costo de prestaciones como las cesantías o la prima de servicios, debe calcularse la proporcionalidad en relación con el salario. La norma indica que por 12 meses trabajados se hacer acreedor a un mes por cada uno de estos conceptos. Así, la ratio 1/12 es equivalente al 8,33 % de tal forma que ese porcentaje, al pasar un año será del 100 %. En el caso de las vacaciones el trabajador tiene derecho a 15 días por año trabajado, por lo que la proporción se reduce al 4,17 %. 
        p.mb-4 La siguiente tabla 4 relaciona todos los factores prestacionales a tener presentes a la hora de calcular el costo de la mano de obra:
        .titulo-sexto.color-acento-contenido.ms-5
          span <span style='font-weight: bold;'>Tabla 4</span> Factores prestacionales
        table.ms-4.me-4.table-sm
          caption Nota. Sena (2021).
          thead.bg-color-verde-claro
            tr
              th.text-center.Text-grande.text-bold Prestación
              th.text-center.Text-grande.text-bold Empleador/a
          tbody
            tr
              td Vacaciones
              td 4.17%
            tr
              td Cesantías
              td 8.33%
            tr
              td Prima de servicios
              td 8.33%  
            tr
              td Intereses a las cesantías
              td 1%
            tr
              td.text-bold Total
              td.text-bold 21.83% 

    p.mt-4.mb-4 Por otra parte, de forma adicional a lo mencionado previamente, los contratos laborales también obligan a los empleadores a asumir costos por la seguridad social del empleado, el artículo “Cotización a la Seguridad Social – Aportes” publicado por el ministerio de trabajo aporta la siguiente tabla: 
    .row.mb-4
      .col-2
      .col-8
        .titulo-sexto.color-acento-contenido.ms-5
            span <span style='font-weight: bold;'>Tabla 5</span> Aportes obligatorios a la seguridad social
        table.ms-4.me-4.table-small.Text-mediano
          caption Nota. Ministerio del trabajo (2019). 
          thead.bg-color-verde-claro
            tr
              th
              th.text-center.text-bold Empleador/a
              th.text-center.text-bold Trabajador/a
              th.text-center.text-bold Total
          tbody
            tr
              td Pensiones
              td 12%
              td 4%
              td 16%
            tr
              td Salud
              td 8.5%
              td 4%
              td 12,5%
            tr
              td Riesgos laborales - Nivel I
              td 0,5%
              td
              td 0,5% 
            tr
              td Cajas de compensación
              td 4%
              td
              td 4%
            tr
              td.text-bold Total
              td.text-bold 25%
              td.text-bold 8%
              td.text-bold 33%
      .col-2
    .row.mt-5.mb-4
      .col-7
        p.mb-4 La estimación de todos los costos asociados a un trabajador, suelen llevarse a una hoja de trabajo conocida como nómina. Allí, se detallan todos los rubros que comprenden los pagos y prestaciones de cada trabajador, de tal forma que tenga claridad sobre los costos totales asociados a la relación laboral. <span style="color: #5F9025;">Una vez se cuenta con esta información, es posible asignarle un valor a cada hora trabajada, en función de las horas totales del mes.</span> Para ejemplificar lo anterior se presenta el siguiente caso, ver tabla 6: 
        p.mb-4 Calcular el costo de mano de obra de un producto que requiere 1 hora de trabajo de los siguientes dos operarios: 
        .row
          .col-3
          .col-6.bordeVerde
            p Operario 1:  Salario Básico de 1.000.000
            p Operario 2:  Salario Básico de 1.500.000
          .col-3

      .col-5
        img(src='@/assets/curso/hombreLeyendo.png')

    .row.mb-5
      .col-6
        .titulo-sexto.color-acento-contenido.ms-4
          span <span style='font-weight: bold;'>Tabla 6</span> Liquidación costo mensual empleado
        table.table-responsive.table-bordered.ms-4.me-2
          caption Nota. Sena (2021).
          thead
            th Concepto
            th Operario 1
            th Operario 2
          tr
            td Salario
            td 1.000.000
            td 1.500.000
          tr
            td Aux. de transporte
            td 106.454
            td 106.454
          tr
            td Subtotal salario
            td 1.106.454
            td 1.606.454
          tr
            td 
            td
            td
          tr
            td Prestaciones
            td
            td
          tr
            td Vacaciones
            td 41.667
            td 62.500
          tr
            td Cesantías
            td 92.205
            td 133.871
          tr
            td Prima de servicio
            td 92.205
            td 133.871
          tr
            td Intereses a las cesantías
            td 11.065
            td 16.065
          tr
            td.text-bold Subtotal prestaciones 
            td.text-bold 237.140
            td.text-bold 346.307
          tr
            td 
            td
            td
          tr
            td Seguridad social
            td 
            td
          tr
            td Salud
            td.text-center -
            td.text-center -
          tr
            td Pensión
            td 132.774
            td 192.774
          tr
            td ARL
            td 5.754
            td 8.354
          tr
            td.text-bold Subtotal seguridad social
            td.text-bold 138.528
            td.text-bold 201.128
          tr
            td 
            td
            td
          tr
            td Aportes parafiscales
            td
            td
          tr
            td Caja de compensación
            td 44.258
            td 64.258
          tr
            td SENA
            td.text-center -
            td.text-center -
          tr
            td ICBF
            td.text-center -
            td.text-center -
          tr
            td.text-bold Subtotal parafiscales
            td.text-bold 44.258
            td.text-bold 64.258
          tr
            td
            td
            td
          tr
            td.text-bold Total costo empleado
            td.text-bold 1.343.594 
            td.text-bold 1.952.761 
      .col-6    
        p.ms-5 Es importante precisar que la base de las prestaciones sociales es equivalente a la suma del salario básico, más el auxilio de transporte, las comisiones y las horas extra, entre otros. Sin embargo, en el caso de las vacaciones, el auxilio de transporte no se incluye puesto que se asume que en ese periodo el empleado no deberá asumir costos de movilización, pues no se desplazará a su lugar de trabajo.
        p.ms-5 <span style="color: #5F9025;">Una vez calculado el costo mensual de cada empleado, se debe continuar con la estimación del tiempo destinado a la elaboración de cada unidad producida.</span> Por ejemplo, si cada empleado tarda una hora de su trabajo en el proceso de transformación, y debe trabajar 24 días al mes en jornadas fijas de 8 horas, el costo de la mano de obra unitario se calcularía así, ver tabla 7:
        .titulo-sexto.color-acento-contenido.ms-4
          span <span style='font-weight: bold;'>Tabla 7</span> Costo de mano de obra por hora        
        table.table-responsive.table-bordered.ms-4.me-2.table-small
          caption Nota. Sena (2021).
          thead
            th 
            th.Text-mediano Operario 1
            th.Text-mediano Operario 2
          tr
            td Costo mensual
            td 1.343.594
            td 1.952.761 
          tr
            td Horas diarias de trabajo
            td 8
            td 8
          tr
            td Días trabajados al mes
            td 24
            td 24
          tr
            td 
            td
            td
          tr
            td Horas de trabajo mensual
            td 192
            td 192
          tr
            td
            td
            td
          tr
            td.text-bold Costo por hora (salario/total horas):
            td.text-bold 6.998
            td.text-bold 10.171 

        .cajon.bg2.p-4.mb-4.mt-5.ms-4
          .titulo-sexto.color-acento-contenido
            span.Text-mediano Los cálculos de nómina suelen obedecer siempre a los mismos criterios, por lo que las hojas de cálculo electrónicas pueden agilizar el proceso con la aplicación de fórmulas matemáticas. Allí, se pueden agregar tantos empleados como sea necesario, siempre y cuando se respeten las tarifas y se tenga cuidado con su parametrización. Actualmente existen softwares gerenciales que agregan módulos de nómina y se encargan de automatizar aún más el proceso, sin embargo suelen tener costos elevados, por lo que solo son opciones viables para empresas con cierta robustez financiera

    .shadow.p-3.mb-5.mt-5.bg-body.rounded.fondoBanner-1
      .row.align-items-center
        .col-1
        .col-3
          img(src='@/assets/curso/calculadoraPapel.png')
        .col-1
        .col-1
          img(src='@/assets/curso/figRio.svg')
        .col-6      
          p Para profundizar acerca de la automatización de la nómina de forma gratuita, se recomienda al aprendiz observar tutoriales como el siguiente Oliveros (2016). Ms Excel 5 Fórmulas nómina completa.
          .row
            .col-8
            .col-4
              a.boton.me-3.indicador__container(
                href="https://www.youtube.com/watch?v=KdZLNPyLGmk"
                target="_blank"
                @mouseover="mostrarIndicador = false"
              )
                span Ver video
                .indicador--click(v-if="mostrarIndicador")
    h3.mb-4
      span.colorText-verde <u>Costos indirectos de fabricación</u> 
    .row.mb-5.mt-5
      .col-5
        img(src='@/assets/curso/estudiando.png')      
      .col-7
        .cajon.Color-Bkg-Cajon.p-4.mb-4.mt-4.Neg-Der.position-relative
          .titulo-sexto.color-acento-contenido
            span La distribución y asignación de los costos indirectos de fabricación aporta más complejidad al cálculo del costo de producción de lo que se podría pensar, lo anterior debido a que existen limitaciones significativas para determinar la porción de un costo indirecto a una unidad producida. Por ejemplo, si se debe reparar una maquina de ordeño, en cuánto se debe incrementar el costo de producción de cada litro de leche. 
        p.mb-4 <span style="color: #5F9025;">Este tipo de situaciones implica que la asignación de los costos indirectos obedezca a la cantidad de unidades producidas en un periodo concreto.</span> Existen diversos elementos de juicio pero suelen converger en una apreciación, la asignación del costo estará supeditada a los niveles de producción de la planta.
    .row.mb-4
      .col-7
        p.mb-4 <span style="color: #5F9025;">Si se producen varios productos en diversas líneas de producción, por ejemplo, en una granja pecuaria donde se produce leche y al mismo tiempo se vende la carne del ganado, la situación puede resultar más complejo.</span> Retomando el ejemplo anterior, el daño de una maquina de ordeño debe asignarse a la línea productiva de la leche, pero qué sucede entonces en casos como el salario del administrador, donde su trabajo es indistinto entre las dos líneas de producción. 
        .row
          .col-1
            img(src='@/assets/curso/figRio.svg') 
          .col-11
            p El criterio del encargado del cálculo de los costos deberá aplicar la distribución en base a su criterio, algunas de las opciones más utilizadas son las unidades producidas, o las horas de trabajo destinadas a cada tipo de producto. El siguiente ejemplo, ver tabla 8, ilustra una situación de este estilo: 
            .titulo-sexto.color-acento-contenido.ms-4
              span <span style='font-weight: bold;'>Tabla 8</span> Costos indirectos de fabricación mensuales
        table.me-4.table-small
          caption Nota. Sena (2021).
          thead.bg-color-verde-claro
            tr
              th.text-center.Text-mediano.text-bold Costos indirectos
              th.text-center.Text-mediano.text-bold Valor
          tbody
            tr
              td Depreciación
              td.text-center 1.200.000
            tr
              td Servicios públicos
              td.text-center 250.000
            tr
              td Vigilancia
              td.text-center 1.500.000 
            tr
              td.text-bold Total CIF
              td.text-bold.text-center 2.950.000
      .col-5
        img(src='@/assets/curso/vacunacion.png')  
    p.mt-4 Las unidades producidas requirieron de diferente cantidad de tiempo de trabajo por los dos operarios que se presentaron en el caso de la mano de obra así, ver tabla 9:
    .row.mb-4.mt-4
      .col-5
        img(src='@/assets/curso/revisor.png')  
      .col-7
        .titulo-sexto.color-acento-contenido.ms-4
          span <span style='font-weight: bold;'>Tabla 9</span> Hoja de producción con horas de trabajo
        table.me-4.table-small
          caption Nota. Sena (2021).
          thead.bg-color-verde-claro
            tr
              th
              th.text-center.Text-mediano.text-bold Horas de trabajo
              th.text-center.Text-mediano.text-bold Unidades producidas
          tbody
            tr
              td Producto A
              td 250
              td 200
            tr
              td Producto B
              td 134
              td 100
            tr
              td Total
              td 384
              td 300  
        p.mt-4.mb-4 <span style="color: #5F9025;">Para definir los costos indirectos de fabricación de cada línea, será necesario prorratear en base a las horas de trabajo destinadas a cada línea de producto,</span> posteriormente, y en función de las unidades elaboradas, se podrá definir el costo indirecto de fabricación unitario para cada tipo de producto, ver tabla 10.
        table.me-4.table-small
          caption Nota. Sena (2021).
          thead.bg-color-verde-claro
            tr
              th
              th.text-center.Text-mediano.text-bold Costo indirecto asignado
              th.text-center.Text-mediano.text-bold Unidades producidas
              th.text-center.Text-mediano.text-bold Costo indirecto Unitario 
          tbody
            tr
              td Producto A
              td 1.920.573 
              td 200
              td 9.603 
            tr
              td Producto B
              td 1.029.427 
              td 100
              td 10.294 
            tr
              td Total
              td 2.950.000 
              td 300
              td

    #ordenes.titulo-segundo   
      .h4 2.7 Órdenes de Producción

      .row.mt-4
        .col-4
        .col-8
          p Las órdenes de producción, también conocidas como órdenes de pedido, suelen ser utilizadas en empresas en las que la línea de producción no opera de manera permanente. <span style="color: #5F9025;">Bajo este sistema, la determinación del coste de un lote de producto terminado se estima de forma independiente a otros, por lo que pueden existir variaciones en el costo de venta unitario entre una y otra orden.</span>
      .row.ms-1.fondoBanner-2
        .col-5
            img.Neg-Top140(src='@/assets/curso/mujerPC.png', alt='Ordenes de producción')
        .col-7
          .cajon.Color-Bkg-Cajon.p-4.mb-4.Neg-Der
            .row  
              .col-1
                img(src='@/assets/curso/figRio.svg')
              .col-11
                p <span style="font-weight: bold;">Este sistema ofrece una gran utilidad en unidades productivas que trabajan por encargo, puesto que las mediciones varían en función de la situación actual.</span>  El siguiente formato propone un esquema para utilizar bajo esta metodología; su diligenciamiento suele ser precedido por una solicitud comercial, es decir, el área de ventas indica la unidad de productos vendidos, y de cara a esto, el departamento de producción determina el costo unitario de cara a las exigencias presentadas, ver tabla 11.
      .titulo-sexto.color-acento-contenido.ms-4.mt-4
         span <span style='font-weight: bold;'>Tabla 11</span> Ejemplo de orden de producción
      .row
        .col-1
        .col-10.justify-content-center
          table.table-small.table-responsive.mt-5
            thead
              tr.text-center
                <th colspan="8"> Orden de producción</th>
              tr
                <th colspan="7"> Unidades</th>
                <th> Nro. Orden</th>
              tr
                <th colspan="8"> Estado</th>
              tr
                <th colspan="8"> Producto:</th>
              tr.text-center
                <th colspan="3"> Materiales</th>
                <th colspan="3"> Mano de obra directa</th>
                <th colspan="2"> Costos indirectos</th>
              tr.text-center
                th
                th Cantidad
                th Costos
                th
                th Cantidad
                th Costos
                th
                th Costos            
              tr.text-center
                th cantidad
                th Vr. Unit
                th Total
                th cantidad
                th Vr. Unit
                th Total
                th cantidad
                th Vr. Unit        
            caption Nota. Guarnizo Cuellar y Cárdenas (2015). 
            tr
              td
              td
              td
              td
              td
              td
              td
              td
            tr
              td
              td
              td
              td
              td
              td
              td
              td
            tr
              td
              td
              td
              td
              td
              td
              td
              td
            tr
              td Total
              td
              td
              td Total
              td
              td
              td Total
              td
            tr
              td
              td
              td
              td
              td
              td
              td
              td
            tr
              <td colspan="2">Total costo orden</td>
              td Costo unitario
              td
              td
              td
              td
              td
        .col-1
    #caracteristicas.titulo-segundo
      .row.mt-4.fondoBanner-3
        .col-4
          .h4.mb-5.ms-4.mt-4 2.7.1 Características
          img(src='@/assets/curso/mujerHombre.png', alt='Características')
        .col-8
          p.mb-5.me-4.mt-4.Text-mediano <span style='font-weight: bold;'>Las ordenes de producción preceden el inicio del ciclo productivo, por lo que su emisión resulta un requisito previo.</span> En ellas se consigna información relevante como las unidades a producir, su identificación y el número consecutivo de la orden con el fin de establecer prioridades. Las siguientes son algunas de las características más importantes de estas:
          .row.mb-5
            .col-sm.mb-5.mb-sm-0
              ol.lista-ol--cuadro.Text-mediano.color-primario
                li.me-5.ms-4.text-mediano 
                  .lista-ol--cuadro__vineta
                    span a
                  | Se espera estimar un costo de producción distinto para cada pedido, por lo que es común ver la aplicación de este tipo de metodologías en unidades productivas que no mantienen una línea de producción estandarizada o permanente. 
                li.me-5.ms-4
                  .lista-ol--cuadro__vineta
                    span b
                  | Se hace necesaria una planificación previo inicio de la producción, puesto que el alistamiento del material y el diligenciamiento de la orden de producción varía de acuerdo con las unidades que se esperan producir
      .row.fondoBanner-3
        .col-12.ms-4.mt-4
          .col-sm.mb-5.mb-sm-0
            ol.lista-ol--cuadro
              li.Text-mediano.ms-4
                .lista-ol--cuadro__vineta
                  span c
                | La producción requiere de un pedido previo, lo que implica, que si no se efectúan ventas, los niveles de producción se reducirán al mínimo. El trabajo por encargo suele optimizar en costos de bodegaje o almacenamiento, pero los costos se pueden ver castigados por la capacidad ociosa de la planta.

    
      #diligencia.titulo-segundo
        .h4.mt-5 2.7.2 Diligenciamiento
      .row.mb-5.mt-5
        .col-7            
          p.mb-4mt-4.Text-mediano Al diligenciar la orden de producción, se espera que los insumos estimados sean los suficientes para dar cumplimiento con la demanda del cliente. Gracias a esto, se minimizan los costos de almacenaje, caducidad u obsolescencia. Una vez definidos los insumos, se les asigna un valor para calcular el costo total de la orden de producción, y de forma derivada, obtener el costo unitario.
          .row
            .col-1
              img(src='@/assets/curso/figRio.svg')
            .col-11
              p.mb-4.Text-mediano <span style="color: #5F9025;">Para ilustrar el diligenciamiento de una orden de producción, se presenta la siguiente situación: se solicita por medio de la orden de producción 53, 4.000 litros de leche en una granja pecuaria para cumplir con los pedidos semanales producto de las ventas efectuadas por el área comercial. Para efectos prácticos, se cuenta con un solo operario y las ordenes son de periodicidad semanal. La siguiente es la discriminación de los costos:</span>             
        .col-5
          img(src='@/assets/curso/manosRevisor.png') 
      .row.mb-5.mt-5
        .col-2
        .col-1
          img(src='@/assets/curso/circulo.svg')
        .col-8
          h3.mb-4
            span.colorText-verde Materia prima
            p.mt-4.mb-4 Se estima que las vacas consumen 3 Kilogramos de concentrado diario y producen 10 litros de leche en ese mismo periodo de tiempo. la compra se efectúa de forma mensual a un proveedor que la ofrece a un valor de $1.500 por Kilogramo, incluida la entrega en la granja. Si cada vaca puede producir 70 litros semanales, se requerirá de la producción de 58 animales para cubrir este pedido, y por lo tanto, de 1.218 kg de concentrado. Además del pastoreo y el concentrado, las vacas requieren de una suplementación en sales minerales con alto contenido nutricional. Así, la unidad productiva suministra 1 kilogramo de sales minerales semanales a cada vaca productora. El proveedor ofrece este producto a un valor de $ 2.000 por cada kilogramo.
        .col-1
      .row.mb-5.mt-5
        .col-2
        .col-1
          img(src='@/assets/curso/circulo.svg')
        .col-8
          h3.mb-4
            span.colorText-verde Mano de obra
            p.mt-4.mb-4 La granja cuenta con un solo operario cuyo salario básico es de $ 1.000.000, adicionalmente cuenta con las prestaciones de ley equivalentes a un 30 % del ingreso básico, también se debe cancelar la seguridad social a las entidades correspondientes por un valor equivalente al 20% del salario. Dado que la orden de producción se lleva a cabo en una semana, el costo del empleado debe tomarse de manera proporcional (una cuarta parte del salario)
        .col-1
      .row.mb-5.mt-5
        .col-2
        .col-1
          img(src='@/assets/curso/circulo.svg')
        .col-8
          h3.mb-4
            span.colorText-verde Costos indirectos
            p.mt-4.mb-4 Los costos indirectos mensuales de la granja son los siguientes: por concepto de aseo y desinfección de la granja: $ 1.500.000, el pago de servicios públicos (agua y luz) es en promedio de 400.000 y por último, el costo de la medicación y tratamiento veterinario asciende a $ 800.000. Al igual que con la mano de obra, se debe practicar la proporción para una sola semana de producción, ver tabla 12.
        .col-1

    .titulo-sexto.color-acento-contenido.ms-4.mt-4
      span <span style='font-weight: bold;'>Tabla 11</span> Ejemplo de orden de producción
    .row
      .col-1
      .col-10.justify-content-center
        table.table-small.table-responsive.mt-5.Text-mediano
          thead.text-bold
            tr.text-center
              <th colspan="8"> Orden de producción</th>
            tr
              th Unidades
              <th colspan="5"> 4.000</th>
              th Nro. Orden
              th.text-center 53
            tr
              th Estado
              <th colspan="7"> En proceso</th>
            tr
              th Producto
              <th colspan="7"> Litro de leche</th>
            tr.text-center
              <th colspan="3"> Materiales</th>
              <th colspan="3"> Mano de obra directa</th>
              <th colspan="2"> Costos indirectos</th>
            tr.text-center
              th
              th Cantidad
              th Costos
              th
              th Cantidad
              th Costos
              th
              th Costos                  
          caption Nota. Sena (2021).
          tr
            td Concentrado
            td.text-center 12
            td 18
            td Salario
            td.text-center 1
            td 250.000
            td Aseo 
            td 375.000
          tr
            td Sales
            td.text-center 58
            td 116.000
            td Prestaciones
            td.text-center 1
            td 75.000
            td Servicios Públicos
            td 100.000
          tr
            td 
            td
            td
            td Seguridad social
            td.text-center 1
            td 50.000
            td Veterinario
            td 200.000
          tr
            td Total
            td 
            td  1.943.000
            td Total
            td
            td 375.000
            td Total
            td 675.000
          tr
            td
            td
            td
            td
            td
            td
            td
            td
          tr
            <td colspan="2">Total costo orden</td>
            td 2.993.000
            td Costo unitario
            td
            td 748
            td
            td
          .col-1

      .row.mb-5.mt-5.ms-5
        .col-5
          img(src='@/assets/curso/supervisorPC.png')      
        .col-7
          .cajon.Color-Bkg-Cajon.p-4.mb-4.mt-4.Neg-Der.position-relative
            .titulo-sexto.color-acento-contenido
              span Del formato anterior se desprende que lo que se busca con la orden de producción es determinar las cantidades y el costo de los insumos necesarios para producir lo solicitado. Con esta información, se puede estimar un costo unitario y a partir de ello, establecer un margen de rentabilidad por cada litro de leche vendida.


      p.mb-4.ms-5 El costo unitario es el resultado del costo total de la orden de producción dividido en el número de unidades producidas, con los datos aquí presentados es posible determinar el valor de la utilidad bruta de la granja, puesto que si se supone un precio de venta de $ 1.000 por litro de leche, de forma rápida puede identificarse el beneficio unitario (1.000 – 748= $ 252) o global (4.000.000 – 2.993.000 = $ 1.007.000).


</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
    datosSlyder: [
      {
        titulo: '4P',
        texto:
          'La fase de las 4 “P” defina la forma en la que el producto llegará a los clientes; su nombre proviene del análisis de los factores más relevantes en este sentido, que son: el producto, el precio, la plaza y la promoción. Lo anterior implica que debe efectuarse un estudio que contemple las características del producto, su precio de venta en relación con los terceros, la plaza, entendida como el lugar donde se ofertan los bienes, y la promoción, que refiera a los esfuerzos comerciales para penetrar en el mercado.',
        imagen: require('@/assets/template/imagenBanner1.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Comunicación',
        texto:
          'Aborda todos los canales para la transmisión de información, esto incluye la comunicación asertiva entre los funcionarios de las diversas áreas que colaboran para la elaboración, distribución y venta de bienes, así como la debida retroalimentación obtenida por parte de los consumidores. Es recomendable apoyarse en las tecnologías de la información para facilitar el proceso, haciendo uso de herramientas contempladas en el marketing digital como la gestión redes sociales o mensajería instantánea.',
        imagen: require('@/assets/template/imagenBanner2.png'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Puesta en marcha',
        texto:
          'Para este paso se deben definir las tareas y los responsables de estas. La asignación puede dirigirse a áreas, cargos o personas según las necesidades; sin embargo, es importante recalcar que el factor tiempo resulta determinante, puesto que ciertas estrategias requieren de una secuencia para ser efectivas. Por ejemplo, una estrategia publicitaria puede tener diferentes efectos si la campaña en medios se realiza antes (para crear expectativa) o después del lanzamiento de un producto.',
        imagen: require('@/assets/template/imagenBanner3.png'),
        //leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Presupuesto',
        texto:
          '<p>Este tipo de planeación no puede obviar el factor económico que implica su implementación. La empresa como órgano social debe trabajar de manera cooperativa con las demás áreas organizacionales, puesto que la armonía garantiza que los propósitos comunes sean alcanzados.</p><p>Una campaña muy costosa puede traer una demanda tan grande que la capacidad productiva no logre abastecerla, de la misma manera, la aplicación de una estrategia publicitaria puede representar más dinero del que tiene a disposición la empresa, lo que implica posibles sobreendeudamientos o incumplimientos en los pagos que afecten la reputación, causando un efecto contrario al buscado.</p><p>El presupuesto debe elaborarse de manera previa y simultánea a la programación de las tareas propias de la puesta en marcha, de tal forma que se tenga certeza de la disponibilidad de recursos en las fechas esperadas. Este trabajo suele requerir del acompañamiento del área financiera, quienes deberán dar aprobación previa implementación, para garantizar que todas las tareas puedan llevarse a cabo de acuerdo con el programa.</p>',
        imagen: require('@/assets/template/imagenBanner4.png'),
        //leyendaImagen: 'Leyenda de la imagen',
      },
    ],
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
