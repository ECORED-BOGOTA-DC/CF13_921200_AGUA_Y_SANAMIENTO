<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido    
      .titulo-principal__numero
        span.text-white 1
      h1 Política de atención integral en salud.

    .row.justify.content-center.align.items-center
      .col-md-6
        figure
          img.img-fluid(src="@/assets/curso/tema1/img01.png")
      .col-md-6.align-self-center
        hr
        p.mb-4 De acuerdo con el documento del Ministerio de Salud y Protección Social (2016) su política de atención integral en salud se define como un sistema de salud al servicio de la gente. Esta política nace en pro de garantizar el derecho a la salud, en consecuencia, el objetivo principal es mejorar la salud de la población a través del acceso a los servicios de manera oportuna, eficaz, con calidad y acogiendo el principio de promoción de la salud.
        .tarjeta-color.bg_color1.me-5.pe-4
          .p-3
          p.ps-5.pe-3.pb-4 La política, al ser integral, hace referencia a la igualdad de trato y oportunidades en acceso. Todas las actividades de promoción, prevención, diagnóstico, tratamiento, rehabilitación y paliación están disponibles para cualquier persona que las requiera.

    .row.justify.content-center
      .col-md-7
        figure.mb-5
          img.mx-auto.d-block(src="@/assets/curso/tema1/img02.svg" style= "width: 85px")
        p.mb-4 Garantizar el derecho a la salud de cada individuo requiere de un trabajo coordinado entre diferentes entidades y actores, además, pueden hacer parte de este trabajo, desde las que tienen un alcance local como prestadoras de servicios hasta las que tienen un alcance nacional como los ministerios. Cuando se realiza esta coordinación se crean planes de desarrollo territoriales que se articulan con el plan decenal de salud pública y se evalúan con instrumentos derivados del plan nacional de desarrollo.
        p La interacción de las entidades territoriales, las Instituciones Prestadoras de Salud (IPS) y las Entidades Promotoras de Salud (EPS) se articulan haciendo una gestión integral del riesgo en salud, identificando las causas que pueden generar enfermedades, haciendo énfasis en el cuidado teniendo en cuenta la diferenciación y prestando una atención primaria en zonas rurales, urbanas y dispersas. 
      .col-md-4
        figure
          img.img-fluid(src="@/assets/curso/tema1/img03.svg")
        .tarjeta-color.bg_color3.mt-2
          .p-1
          p.px-2.text-center.text-small <b>Nota:</b> Ministerio de salud y de protección social (2016). Política de atención integral en salud (p. 31)
    
    .row.align.items-center
      .col-md-2
        figure
          img.img-fluid(src="@/assets/curso/tema1/img04.svg")
      .col-md-8.align-self-center
        p.mt-5 Es así como la política de atención integral en salud está conformada principalmente por dos columnas, el marco estratégico que convierte los principios y objetivos en estrategias, junto al modelo operacional que, a partir de las estrategias, adopta los mecanismos e instrumentos operativos y de gestión que orientan la intervención de los diferentes agentes del sistema.

    Separador

    #t_1_1.titulo-segundo.color-secundario(data-aos="zoom-out-right")
      h2 1.1.	Marco estratégico de la Política de Atención Integral en Salud (PAIS)

    p.mb-4 La transformación del modelo institucional de la Ley 100 (1993) a los objetivos de un sistema de salud centrado en la población y sus relaciones a nivel familiar y comunitario está contenida en la política de atención integral en salud.  

    TabsB.color-acento-contenido.px-5
      .py-4.py-md-5(titulo="La Atención Primaria en Salud (APS)" :icono="require('@/assets/curso/tema1/img05.svg')")  
        .row.p-3.justify-content-center.align-items-center
          .col-12.col-md-7
            p.mb-4 <b>La Atención Primaria en Salud (APS)</b>
            p.mb-4 Es la estrategia básica social, clínica y científica que provee asistencia a las personas, al tiempo que integra las necesidades de la población, la respuesta del sistema y los recursos disponibles con un enfoque de salud familiar y comunitaria. Cuando se habla de este enfoque se tiene en cuenta la coordinación de los procesos primarios de la salud en la población en general, se realizan trabajos que se tienen como prioridad los problemas de salud que no requieren alta tecnología médica para su solución.
            p.mb-0 La atención primaria en salud con enfoque de salud familiar y comunitaria permite también tener una mayor cercanía al equipo de salud, una mejor comprensión de las enfermedades mejora la percepción y confianza en los servicios de salud e involucra a la comunidad en la toma de decisiones de salud pública.
            p La atención primaria en salud es universal, intercultural, con enfoque diferencial, integral, comunitario, transparente, sostenible, eficiente, progresiva e irreversible.
          .col-12.col-md-5
            img.pe-4(src='@/assets/curso/tema1/img09.png')
        .row.justify-content-center
          .col-8
            figure
              img.mt-5(src='@/assets/curso/tema1/img10.svg')
      .py-4.py-md-5(titulo="El cuidado de la salud" :icono="require('@/assets/curso/tema1/img06.svg')")
        p.mb-4 <b>El cuidado de la salud</b>
        p.mb-0 Son las capacidades, decisiones y acciones que toma una persona para proteger su salud, la de su familia, comunidad y medio ambiente. 
        p.mb-0 La base del cuidado de la salud es el autocuidado, así que depende del conocimiento que tenga cada individuo en temas de salud, higiene, nutrición, estilos de vida, manejo de estrés, uso de tecnología, entre otras.
        p Adicionalmente, el cuidado a la salud también tiene en cuenta cómo los servicios de la salud se acercan a la comunidad debido a que estos deben cumplir con tres condiciones básicas para tener una relación óptima:
        .tarjeta-color.bg_color4.py-4.mb-4
          .row.justify-content-center.align-items-center
            .col-12.col-md-7
              ul.lista-ul
                li 
                  i.fas.fa-angle-right(style= "color: #5D00F5")
                  | Permitir la libre personalidad: para que sea una decisión personal adquirir los hábitos de vida saludable.
                li 
                  i.fas.fa-angle-right(style= "color: #5D00F5")
                  | Consolidar redes de apoyo y socialización: para que todos los individuos conozcan los hábitos saludables.
                li 
                  i.fas.fa-angle-right(style= "color: #5D00F5")
                  | Permitir la adquisición de capital de salud: permitir experiencias de vida variables y acumulativas relacionadas con la vida de la persona. Por ejemplo, una persona con hábitos de vida saludable tendrá un mejor capital de salud que un fumador.
            .col-12.col-md-4
              figure
                img(src='@/assets/curso/tema1/img11.png' style= "height: 195px") 
        p.mb-4 El cuidado de la salud es una de las estrategias más importantes debido a que institucionalmente se pueden hacer campañas de promoción y prevención de la enfermedad, pero puede que estas no tengan ningún resultado visible si los individuos no tienen acciones de autocuidado.       
        .row.justify-content-center
          .col-12.col-md-8
            figure
              img.mt-5(src='@/assets/curso/tema1/img10.svg')
      .py-4.py-md-5(titulo="La gestión integral del riesgo en salud" :icono="require('@/assets/curso/tema1/img07.svg')")
        .row.justify-content-center
          .col-12.col-md-7
            p.mb-4 <b>La gestión integral del riesgo en salud</b>
            p.mb-4 Es la estrategia que permite la articulación de los objetivos con la financiación y prestación de servicios creando una sinergia de todos los componentes del sistema, minimizando su riesgo y optimizando su funcionamiento.
            p.mb-4 La gestión integral minimiza el riesgo de ocurrencia de una enfermedad y, en caso de aparecer reduce la severidad de las consecuencias. Cuenta con un componente colectivo y uno individual. Este primero, es liderado principalmente por las entidades territoriales articuladas con otras instituciones con el fin de disminuir la probabilidad de aparición de una nueva morbilidad. Mientras que el individual analiza los factores biológicos, determinantes sociales, estilo de vida, impactos de entornos y todos los factores asociados a la enfermedad.
            p.mb-4 Algunas de las acciones que se realizan dentro de la gestión integral del riesgo en salud son: la caracterización y clasificación del riesgo de las personas, conformación de grupos de riesgo, intervención sobre la apropiación individual del riesgo, monitoreo y seguimiento de intervenciones, gestión de la calidad de los procesos de atención, entre otros.
          .col-12.col-md-4
            figure
              img.mt-5(src='@/assets/curso/tema1/img12.png') 
        .row.justify-content-center
          .col-12.col-md-8
            figure
              img.mt-5(src='@/assets/curso/tema1/img10.svg')
      .py-4.py-md-5(titulo="El enfoque diferencial en la atención" :icono="require('@/assets/curso/tema1/img08.svg')")
        .row.justify-content-center
          .col-12.col-md-7
            p.mb-4 <b>El enfoque diferencial en la atención</b>
            p.mb-4 Es la estrategia mediante la cual se reconocen las diferencias de las personas y comunidades en términos de determinantes sociales. Dentro de la estrategia de enfoque diferencial se tienen en cuenta las condiciones de vulnerabilidad y potencialidad asociada a factores físicos, psíquicos, sociales, psicosociales, culturales, económicos, ambientales, entre otros.
            p.mb-4 Existen dos grandes visiones de la diferenciación, la primera es poblacional, que ve la vulnerabilidad como un gradiente que incrementa la probabilidad de ser afectado por un riesgo de cualquier naturaleza. Puede originarse en condiciones permanentes como ancianidad, discapacidad o pobreza estructural no intervenida, o en condiciones transitorias como desplazamiento forzoso, victimización por conflicto o caídas drásticas de ingresos económicos. La segunda es la diferenciación territorial donde se tienen en cuenta necesidades específicas culturales, territoriales, geográficas, ambientales, entre otras. El sistema de salud entonces debe ajustarse a cada contexto para tener en cuenta tanto las diferenciaciones poblacionales como las territoriales.
          .col-12.col-md-4
            figure
              img.mt-5(src='@/assets/curso/tema1/img13.png') 
        .row.justify-content-center
          .col-12.col-md-8
            figure
              img.mt-5(src='@/assets/curso/tema1/img10.svg')
    Separador

    #t_1_2.titulo-segundo.color-secundario(data-aos="zoom-out-right")
      h2 1.2.	Modelo Integral de Atención en Salud (MIAS)

    .row.justify.content-center.align.items-center
      .col-md-4
        figure
          img.img-fluid(src="@/assets/curso/tema1/img14.png")
      .col-md-8.align-self-center
        p.mb-0.pe-4 Es el modelo operacional que adopta herramientas para garantizar la oportunidad, continuidad, integralidad, aceptabilidad y calidad en la atención en salud a partir de las estrategias definidas.
        p.mb-4.pe-4 La atención se debe brindar con equidad, con una visión centrada en las personas, priorizando su bienestar y desarrollo, por ello se establecen acciones de salud tales como el cuidado, la detección temprana, tratamiento, rehabilitación, paliación a lo largo de la vida.
        .tarjeta-color.bg_color5.pe-4
          .p-3
          p.ps-5.pe-2.mb-0.text-white El modelo también va dirigido hacia las instituciones ya que define un conjunto de herramientas que facilitan reestructuraciones, incrementa la capacidad resolutiva de los servicios y permite el flujo de la información entre los usuarios y las organizaciones de forma efectiva.
          p.ps-5.pe-2.pb-4.text-white En general, el modelo integral en atención a la salud enlaza las acciones intersectoriales, colectivas e individuales para mejorar la capacidad del sistema de salud, orientando hacia su mantenimiento, la detección de riesgos, la curación de la enfermedad y la disminución de la discapacidad.

    Separador

    ul.lista-ul
      li 
        <i class="fas fa-circle fa-xs" style= "color:#009EE3 !important;"></i>
        h3.ps-2 Caracterización poblacional de acuerdo con el (PDSP) 2012-2021 
    
    p Es necesario organizar las poblaciones para que la atención y los servicios que se le prestarán sean acorde a sus necesidades y estén vinculadas con las metas propuestas en el plan nacional de salud pública.
    
    .bg_fondo1.mb-4
      .row.align-items-center(data-aos="zoom-in-up")
        .col-12.col-md-3
          figure.justify-center
            img(src="@/assets/curso/tema1/img16.png")        
        .col-12.col-md-8
          p.m-0 La organización de las poblaciones tiene dos enfoques, el primero es el curso de vida que ubica en el centro a las personas, familias y comunidades, permitiendo entender las relaciones dinámicas, las experiencias acumulativas y cómo estas impactan en la salud. 

    p.mb-5 El segundo enfoque es el de grupo de riesgo que tiene en cuenta condiciones similares en términos de interés en salud pública, comparten factores de riesgo, enfermedades, desenlaces clínicos similares por lo que se organizan bajo seis criterios los cuales son:

    .bg_fondo2
      .row.mb-5.justify-content-evenly
        .col-md-3
          .tarjeta-numerada.color-primario.p-5
            .tarjeta-numerada__numero
              .h2 1
            p.text-center Grupos sociales de riesgo.

        .col-md-3
          .tarjeta-numerada.color-primario.p-5
            .tarjeta-numerada__numero
              .h2 2
            p.text-center Enfermedades de alta frecuencia y cronicidad.

        .col-md-3
          .tarjeta-numerada.color-primario.p-5
            .tarjeta-numerada__numero
              .h2 3
            p.text-center Enfermedades prioritarias en salud pública.
      .row.mb-5.justify-content-evenly
        .col-md-3
          .tarjeta-numerada.color-primario.p-5
            .tarjeta-numerada__numero
              .h2 4
            p.text-center Enfermedades con tratamientos de alto costo.

        .col-md-3
          .tarjeta-numerada.color-primario.p-5
            .tarjeta-numerada__numero
              .h2 5
            p.text-center Condiciones intolerables para la sociedad.

        .col-md-3
          .tarjeta-numerada.color-primario.p-5
            .tarjeta-numerada__numero
              .h2 6
            p.text-center Enfermedades de alto costo.

      .row.mb-5.justify-content-center
        .col-12.col-md-7
          .tarjeta.color.bg_color7(data-aos="zoom-in-up")
            .p-4
            .row.justify-content-center
              .col-md-2.align-self-center
                figure
                  img(src="@/assets/curso/tema1/img18.svg") 
              .col-md-8
                p.m-0 La caracterización de la población debe hacerse para todos los ámbitos territoriales con el fin de tener en cuenta los resultados en las formulaciones de los planes territoriales de salud.
            .row.justify-content-center
              .col-12.col-md-11
                figure
                  img.mt-5(src='@/assets/curso/tema1/img19.svg')

    Separador

    ul.lista-ul
      li 
        <i class="fas fa-circle fa-xs" style= "color:#009EE3 !important;"></i>
        h3.ps-2 Regulación de Rutas Integrales de Atención en Salud (RIAS)

    .bg_fondo3.mb-4
      .row.align-items-center(data-aos="zoom-in-up")
        .col-12.col-md-7.mt-4
          p.m-0 Las Rutas Integrales de Atención en Salud (RIAS) son un instrumento regulatorio básico que permite la atención de las prioridades en salud, tienen un objetivo social que es la ganancia en salud y la disminución de la carga de enfermedad. Así mismo, son herramientas que definen las condiciones necesarias para asegurar la integralidad en la atención. Se tienen en cuenta varios factores entre los que se encuentran el autocuidado, la promoción del bienestar y el desarrollo de los individuos, así como las intervenciones para la prevención, diagnóstico, tratamiento, rehabilitación de la discapacidad y paliación. 
        .col-12.col-md-5
          figure.justify-center
            img(src="@/assets/curso/tema1/img21.svg")        

    p.m-0.mb-4 Están diseñadas para los diferentes agentes del sistema: entes territoriales, aseguradores y prestadores de salud. Esta articulación permite que a partir de las RIAS se consoliden acciones del plan de intervenciones colectivas y del plan de beneficios.
    p.m-0.mb-5 Existen tres tipos de Rutas Integrales de Atención en Salud (RIAS) estas son:

    AcordionA(tipo="b" clase-tarjeta="tarjeta tarjeta--azul").mb-5
      .row(titulo="Ruta de promoción y mantenimiento de la salud")
        .col-md-12.mb-4.mb-md-0
          p Maneja los riesgos colectivos en salud y protección de la salud, promueve entornos saludables, desarrollo de individuos e incluye acciones de cuidado desde y hacia el individuo.
  
      div(titulo="Ruta de grupo de riesgo")
        p Incorpora actividades individuales y colectivas, está dirigida hacia la identificación oportuna de los factores de riesgo y su intervención.
  
      div(titulo="Ruta específica de atención")
        p Aborda condiciones específicas orientadas al tratamiento, rehabilitación y paliación.

    p.m-0.mb-4.pt-4 Entre otras características de Rutas Integrales de Atención en Salud (RIAS)

    .row.justify-content-end.align-items-center
      .col-md-3
        figure
          img.d-none.d-lg-block(src="@/assets/curso/tema1/img22.svg")
      .col-md-8
        figure
          img.img549.mb-4(src="@/assets/curso/tema1/img26.svg")
        .row.align-items-center
          .col-md-1
            figure
              img.img-a.img-t.mb-2(src='@/assets/curso/tema1/img23.svg')
          .col-md-7
            p.m-0 Documentan, monitorean y evalúan los resultados y las diferencias.
          figure.mt-4
            img.img549.mb-4(src="@/assets/curso/tema1/img26.svg")
        .row.align-items-center               
          .col-md-1
            figure
              img.img-a.img-t(src='@/assets/curso/tema1/img24.svg')
          .col-md-7
            p.m-0 Facilitan la identificación de los recursos humanos, de infraestructura y financieros apropiados
          figure.mt-4
            img.img549.mb-4(src="@/assets/curso/tema1/img26.svg")
        .row.align-items-center.mb-4               
          .col-md-1
            figure
              img.img-a.img-t(src='@/assets/curso/tema1/img25.svg')
          .col-md-7
            p.m-0 Describen explícitamente los elementos clave de la atención basada en la evidencia, las mejores prácticas, y las expectativas de los usuarios 
          figure.mt-4
            img.img549.mb-4(src="@/assets/curso/tema1/img26.svg")

    Separador

    ul.lista-ul
      li 
        <i class="fas fa-circle fa-xs" style= "color:#009EE3 !important;"></i>
        h3.ps-2 Implementación de la Gestión Integral del Riesgo de Salud (GIRS) 
    
    .bg_fondo4.mb-4
      .row.align-items-center(data-aos="zoom-in-up")
        .col-12.col-md-4
          figure
            img.mt-3(src="@/assets/curso/tema1/img28.png")        
        .col-12.col-md-7.text-black
          p.m-0.text-white.mb-4.ms-3 Es necesaria la coordinación, monitoreo y ajuste de todas las acciones planificadas en las Rutas Integrales de Atención en Salud (RIAS) debido a esto nace la Gestión Integral del Riesgo en Salud (GIRS) que busca anticiparse a la ocurrencia de los eventos de interés en salud pública, prevenir las enfermedades, así como las discapacidades producidas por estas.

    p.mb-5.ms-5.text-center La Gestión Integral del Riesgo de Salud (GIRS) se vuelve operativa mediante:

    .row.justify-content-center
      .col-lg-8
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/tema1/img29.svg' alt='AvatarTop' style= "height: 110px")
          .tarjeta.tarjeta--azul
            .p-4
              p.mt-4.me-5.pe-4 Identificar y ponderar los riesgos de salud pública, priorizar grupos de riesgo y armonizar los diferentes actores.
    
    .row.justify-content-center
      .col-lg-8
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/tema1/img30.svg' alt='AvatarTop' style= "height: 110px")
          .tarjeta.tarjeta--azul
            .p-4
              p.m-0.mt-4.pt-3 Recolección y análisis de evidencias sobre la detección del riesgo.
    
    .row.justify-content-center
      .col-lg-8
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/tema1/img31.svg' alt='AvatarTop' style= "height: 110px")
          .tarjeta.tarjeta--azul
            .p-4
              p.mt-4.pt-3 Desarrollar y adaptar las Rutas Integrales de Atención en Salud (RIAS).
    
    .row.justify-content-center
      .col-lg-8
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/tema1/img32.svg' alt='AvatarTop' style= "height: 110px")
          .tarjeta.tarjeta--azul
            .p-4
              p.mt-4.pt-3 Identificar circunstancias que inciden en la aparición de la enfermedad.


    p.mb-5 La Gestión Integral del Riesgo de Salud (GIRS) requiere de la participación de varios agentes entre los cuales se encuentran:

    .row
      .col-xl-11
        TabsA.color-acento-botones.mb-5
          .tarjeta.color-acento-botones--borde.p-4(titulo="Entidad territorial")
            .row.justify-content-around.align-items-center.mt-4
              .col-xl-3.mb-4
                figure
                  img(src='@/assets/curso/tema1/img33.png', alt='Texto que describa la imagen')
              .col-xl-6
                p Coordina todos los agentes del sistema con los demás sectores, ejecuta gestión colectiva del riesgo, los identifica, comunica y genera estrategias preventivas.
          
          .tarjeta.color-acento-botones--borde.p-4(titulo="Entidades Administradoras de Planes de Beneficios (EAPB)")
            .row.justify-content-around.align-items-center.mt-4
              .col-xl-3.mb-4
                figure
                  img(src='@/assets/curso/tema1/img34.png', alt='Texto que describa la imagen')
              .col-xl-6
                p Coordinan la gestión individual del riesgo en salud, monitorean acciones orientadas a minimizar el riesgo a padecer de enfermedad.

          .tarjeta.color-acento-botones--borde.p-4(titulo="Red de servicios")
            .row.justify-content-around.align-items-center.mt-4
              .col-xl-3.mb-4
                figure
                  img(src='@/assets/curso/tema1/img35.png', alt='Texto que describa la imagen')
              .col-xl-6
                p Manejan la integralidad del riesgo de cada individuo, comunican ese riesgo y realizan las intervenciones clínicas.
          
          .tarjeta.color-acento-botones--borde.p-4(titulo="Afiliado")
            .row.justify-content-around.align-items-center.mt-4
              .col-xl-3.mb-4
                figure
                  img(src='@/assets/curso/tema1/img36.png', alt='Texto que describa la imagen')
              .col-xl-6
                p Es el individuo responsable del autocuidado, también se incluye la familia y los cuidadores.
        
        p.mb-4 Para tener una mejor eficiencia y poder realizar un cumplimiento de los objetivos la Gestión Integral del Riesgo de Salud (GIRS) deben basarse en los grupos de riesgo y en los requerimientos de las Rutas Integrales de Atención en Salud (RIAS)

    Separador

    ul.lista-ul
      li 
        <i class="fas fa-circle fa-xs" style= "color:#009EE3 !important;"></i>
        h3.ps-2 Delimitación territorial del modelo integral de atención en salud
    
    .row.justify-content-center.mb-4
      .col-12.col-md-4
        figure
          img(src='@/assets/curso/tema1/img37.svg')
      .col-12.col-md-8
        p.mb-4 Cada territorio tiene necesidades particulares, por eso la operación del Modelo Integral de Atención en Salud (MIAS) debe adaptarse a las diferentes condiciones, no solo desde un punto de vista físico, sino que se deben incluir las características sociales, geográficas, étnicas y de género.
        p.mb-4 Hacer más efectiva la operación del Modelo Integral de Atención en Salud (MIAS) es una prioridad, debido a esto es necesario armonizar las funciones para los dos tipos de entidades territoriales, municipio y departamento, y también se necesita homologar el encuadre territorial del modelo y la operación de los tres agentes del sistema (ente territorial, Entidad Administradora de Beneficios (EAPB) y redes de prestación) con la población del territorio.
        p.mb-4 El modelo de atención reconoce tres tipos de ámbitos territoriales:
        .tarjeta.color-acento-contenido.p-4
          SlyderA
            .row
              .col-md-11.mb-4.mb-md-0
                p.mb-4.ms-5.mt-4 <b>Urbano:</b>
                p.ms-5 Hay una alta agregación de población, densidad y accesibilidad geográfica. De acuerdo con el artículo 65 del plan de desarrollo 2014-2018 son territorios con más de un millón de habitantes, no existe una barrera relevante entre los servicios de salud y la población. 
              
            div
              p.mb-4.ms-5.mt-4 <b>Alta ruralidad:</b>
              p.ms-5.me-4 Estos son la mayoría de los municipios de Colombia, la oferta de servicios tiende a ser monopólica, normalmente es pública, sin embargo, es de baja complejidad y tiene poca capacidad.
                            
            .row
              .col-md-11.mb-4.mb-md-0
                p.mb-4.ms-5.mt-4 <b>Dispersos:</b>
                p.ms-5 Son municipios de densidad poblacional muy baja, tiene muchas limitaciones en los servicios, barreras geográficas y carencia de vías de acceso.    
          
        .row.justify-content-end
          .col-12.col-md-12
            figure
              img.mt-0(src='@/assets/curso/tema1/img38.svg')

    p.mb-4 Teniendo en cuenta los diferentes ámbitos se deben adaptar las Rutas Integrales de Atención en Salud (RIAS) conformar y organizar las redes de salud y tener criterios diferenciales en la operación de los aseguradores para poder atender a todos los afiliados de forma oportuna. Debido a la complejidad que puede presentar la implementación de los servicios de la salud, lo más recomendable es crear redes integrales que permitan aprender de los procesos y prestar un mejor servicio.

    Separador

    ul.lista-ul.mb-5
      li 
        <i class="fas fa-circle fa-xs" style= "color:#009EE3 !important;"></i>
        h3.ps-2 Redes integrales de prestadores de servicios de salud

    .row.justify-content-center.mb-5.position-relative
      .col-12.col-md-5.m-bottom
        .tarjeta.color-primario.m-right
          p.m-0.pd-right.py-4.ps-4.text-small La red integral de prestación de servicios de salud surge a raíz de las necesidades de la población ubicada en un ámbito territorial, el riesgo de las aseguradoras para su población afiliada, los requerimientos de las Rutas Integrales de Atención en Salud (RIAS) y los resultados de los grupos poblacionales y grupos de riesgo.
      .col-12.col-md-7
        .tarjeta-color.bg_color9.m-left
          p.m-0.pd-left.py-4.pe-4.text-small Concretamente, se articulan organizaciones funcionales en temas de salud tanto públicas como privadas teniendo en cuenta las condiciones de operación del Modelo Integral de Atención en Salud (MIAS) y bajo principio de disponibilidad, adaptabilidad, accesibilidad y calidad, contando con recursos humanos, técnicos y financieros para formar una red integral de prestadores de servicios de salud. 
      figure
        img.img290(src='@/assets/curso/tema1/img39.png')
   

    p.mb-4.m-top Cada red debe consolidarse para una población y entorno territorial de referencia y deberá contar con dos componentes prestacionales que son:
    
    .bg_fondo5
      .row.justify-content-center
        .col-12.col-md-8.col-lg-8
          figure
            img(src='@/assets/curso/tema1/img41.svg')
    
    Separador

    p.mb-4 Las funciones generales del aseguramiento social en salud incluyen: 

    .row.justify-content-center.mb-5
      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img42.svg' alt='AvatarTop')
          .tarjeta.color.bg_color8
            .p-4
              p Protección frente al riesgo financiero derivado del riesgo en salud de la población. En el aseguramiento social colombiano no hay deducibles, exclusiones ni periodos de latencia por lo que el asegurador debe asumir ese riesgo.

      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img43.svg' alt='AvatarTop')
          .tarjeta.color.bg_color8
            .p-4
              p Agencia, bajo el cual el asegurador representa al afiliado y puede efectuar compras en volúmenes o intervenir en la prestación de servicios de manera que le permita reducir los precios de los bienes, servicios y controlar los costos.

      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema1/img44.svg' alt='AvatarTop')
          .tarjeta.color.bg_color8
            .p-4
              p Efecto de acceso y de resultados en salud, que permite al asegurado acceder a servicios adecuados a sus riesgos y con resultados previsibles, más allá de las restricciones financieras derivadas de sus ingresos.

    p.mb-4 En el contexto del Modelo Integral de Atención en Salud (MIAS) el asegurador, entre otras competencias debe:

    SlyderF.mb-5(columnas="col-lg-6 col-xl-4")
      .tarjeta.color-acento-botones.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/tema1/img45.svg' alt='AvatarTop')
        p.text-center Identificar y calcular los riesgos en salud de su población afiliada. 

      .tarjeta.color-acento-botones.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/tema1/img46.svg' alt='AvatarTop')
        p.text-center Conformar grupos de riesgo. 

      .tarjeta.color-acento-botones.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/tema1/img47.svg' alt='AvatarTop')
        p.text-center Adoptar, adaptar o desarrollar rutas integrales de atención. 

      .tarjeta.color-acento-botones.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/tema1/img48.svg' alt='AvatarTop')
        p.text-center Gestionar la demanda.

      .tarjeta.color-acento-botones.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/tema1/img49.svg' alt='AvatarTop')
        p.text-center Disponer y aplicar mecanismos de contratación, mecanismos de pago orientados a resultados. 

    Separador

    ul.lista-ul
      li 
        <i class="fas fa-circle fa-xs" style= "color:#009EE3 !important;"></i>
        h3.ps-2 Redefinición del esquema de incentivos
    
    p.mb-4 Para hacer posible el Modelo Integral de Atención en Salud (MIAS) los incentivos se orientan hacia los resultados esperados, se tiene especial precaución en que los resultados se hacen viables sin poner en riesgo la sostenibilidad del sistema.

    .row.justify-content-center
      .col-12.col-md-7
        p.mb-4 Garantizar una sostenibilidad es responsabilidad tanto del prestador como de los proveedores de insumos, de este modo deben articularse para redefinir la unidad de atención garantizando el derecho en la integridad y asegurando que los servicios y tecnologías de salud se suministren de manera completa.
        .cajon.color-secundario.p-4.mb-4
          .h5 Cajón texto color
          p Los pagos deben realizarse de acuerdo con la formulación de la ley estatutaria y las Rutas Integrales de Atención en Salud (RIAS) definidas. Estos pagos deben ser integrales, regulados y de forma tal que generen incentivos en forma de descuentos cuando se minimicen riesgos para el sistema de salud.
      .col-12.col-md-5
        figure
          img(src='@/assets/curso/tema1/img50.svg')
    .row.justify-content-center
      .col-12.col-md-5
        figure
          img(src='@/assets/curso/tema1/img51.png')
      .col-12.col-md-7
        p.mb-3.mt-5 Al mismo tiempo se deben desarrollar incentivos a los usuarios teniendo como objetivo el autocuidado, participación en diferentes programas, adherencia a tratamientos y otros.
        p.mb-4 Con el fin de garantizar la calidad y la centralización del sistema en el ciudadano son varios los requerimientos y procesos que se deben cumplir dentro del sistema de información en salud.
 
    Separador
    
    ul.lista-ul
      li 
       <i class="fas fa-circle fa-xs" style= "color:#009EE3 !important;"></i>
        h3.ps-2 Requerimientos y procesos del sistema de información

    p.mb-4 El sistema de salud debe estar centrado en el ciudadano, por lo tanto, se debe contar con la información necesaria para su atención; esta información debe recolectarse, analizarse y disponerse individualmente para después gestionarse permitiendo integrar así los requerimientos de los agentes en el sistema de salud.

    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/img52.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p La gestión de la información permite hacer análisis individuales, de comunidades o de ámbitos territoriales, lo que permite obtener la relación de las poblaciones con sus determinantes sociales.
          br
          br
          | El modelo de información en salud debe estar alojada en un solo sitio y debe estar disponible para su estudio, sin embargo, para todos los agentes del sistema se les debe garantizar el derecho a la intimidad y el derecho a la privacidad.

    p.ms-5 Así mismo la información debe permitir comparación y trazabilidad al estar almacenada preferiblemente en medios electrónicos bajo mecanismos de seguridad, de este modo es posible realizar seguimiento de resultados, establecer incentivos y realizar ajustes en caso de ser necesario.

    Separador
    
    ul.lista-ul
      li 
       <i class="fas fa-circle fa-xs" style= "color:#009EE3 !important;"></i>
        h3.ps-2 Fortalecimiento del Recurso Humano en Salud (RHS)

    p.mb-4 Para el fortalecimiento de desarrollo del RHS se deben realizar acciones a nivel de cuatro ejes: 

    .row.justify-content-center
      .col-md-10
        LineaTiempoD.color-acento-contenido.mb-5
          .row(numero="1" titulo="La formación del Recurso Humano en Salud (RHS)")
            .col-md-12.mb-4.mb-md-0.px-4
              figure
                img(src='@/assets/curso/tema1/img53.png', alt='Texto que describa la imagen')
              p.mt-4 Es una tarea que exige un proceso explícito, debe incluir cambio en procesos académicos, fortalecimiento de gremios, fortalecimiento de entidades territoriales, coordinación con la población, prestadores y aseguradores. Para tener resultados a corto plazo se realizan acciones de formación continua que ayuda a mejorar el servicio de salud principalmente en el nivel primario. A mediano plazo se abren programas de especializaciones y posgrados en medicina y salud familiar, también se forman médicos en diferentes territorios del país. A largo plazo se ajustan planes curriculares de formación de recurso humano en el sector salud y se evalúan la calidad y pertinencia de esos programas para el mejoramiento continuo.  

          .row(numero="2" titulo="La armonización del Recurso Humano en Salud (RHS)")
            .col-md-12.mb-4.mb-md-0.px-4
              figure
                img(src='@/assets/curso/tema1/img54.png', alt='Texto que describa la imagen')
              p.mt-4 Con el esquema de cuidado integral y provisión de servicios: se desarrollan equipos multidisciplinarios en salud y se diseñan nuevos perfiles como promotores de salud, parteras, líderes comunitarios entre otros, de modo que se genere un desarrollo progresivo en los modelos territoriales de salud, de acuerdo con las orientaciones del Modelo Integral de Atención en Salud (MIAS).

          .row(numero="3" titulo="El fortalecimiento del Recurso Humano en Salud (RHS)")
            .col-md-12.mb-4.mb-md-0.px-4
              figure
                img(src='@/assets/curso/tema1/img55.png', alt='Texto que describa la imagen')
              p.mt-4 Responsable de la planeación y gestión territorial en salud: es la definición participativa de las competencias que exige la implementación del Modelo Integral de Atención en Salud (MIAS) a nivel de la administración, gestión, gerencia y planeación en salud.

          .row(numero="4" titulo="Gestión")
            .col-md-12.mb-4.mb-md-0.px-4
              figure
                img(src='@/assets/curso/tema1/img56.png', alt='Texto que describa la imagen')
              p.mt-4 Planificación y mejoramiento de condiciones laborales del Recurso Humano en Salud (RHS) a nivel nacional y territorial.

    Separador
    
    ul.lista-ul
      li 
       <i class="fas fa-circle fa-xs" style= "color:#009EE3 !important;"></i>
        h3.ps-2 Fortalecimiento de la investigación, innovación y apropiación de conocimiento

    .row.justify-content-center
      .col-12.col-md-4
        figure
          img(src='@/assets/curso/tema1/img57.png', alt='Texto que describa la imagen')
      .col-12.col-md-8
        p.mb-4 Se debe mejorar continuamente el sistema de salud, ello se logra a partir del fortalecimiento de los sistemas de información, implementando nuevas tecnologías y fortaleciendo la investigación e innovación en sistemas y servicios de salud a nivel nacional y regional.
        p.mb-4 El fortalecimiento de los programas debe orientarse a solucionar las necesidades en salud de las poblaciones, al tiempo que se garantizan la sostenibilidad financiera, se gerencia eficientemente los recursos, se plantean políticas públicas en beneficio de los ciudadanos y se da acceso a los adelantos que se logren a la comunidad en general.
        p.m-0 Así como se fortalece la innovación y la investigación, también es necesario aumentar la capacidad de atención del sistema, aumentar el territorio donde hay presencia de instituciones del sector salud y mejorar la gobernanza de los recursos.


      



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
