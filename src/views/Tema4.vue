<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido    
      .titulo-principal__numero
        span.text-white 4
      h1 Normas de seguridad y conservación del medio ambiente y salud pública

    p.mb-4 La normatividad legal vigente es la base de todos los procesos ambientales y de salud pública, por lo cual es muy importante conocer a manera general la información más relevante del tema, sin embargo, es importante aclarar que siempre se debe consultar las últimas actualizaciones.

    .row.justify-content-center.align-items-center
      .col-lg-6
        .cajon.color-primario.p-4.mb-4(data-aos="fade-right")
          p De acuerdo con Bernal, O y Forero J, 2011, el marco legal muestra el contexto institucional a nivel gubernamental en el cual se desarrollan los sistemas de información de la salud en Colombia (p.88) Sin embargo, en este caso es importante definir y referenciar un término que es muy importante Salud Ambiental, de acuerdo con el Ministerio de Salud y Protección Social (s.f.) en su página web referencia que: 
        p.mb-4 La salud ambiental es un componente esencial de la salud pública que promueve la calidad de vida, donde el ser humano debe ser tomado en cuenta como un integrante más de los ecosistemas. Por lo tanto, los factores ambientales que pueden afectar la salud de nuestra población, no se reducen a los agentes físicos, químicos o biológicos; sino también, se deben incluir aquellos otros factores que afectan los ecosistemas; dentro de los cuales pueden mencionarse el cambio climático, la pérdida de la biodiversidad y la deforestación; los cuales influyen de forma directa o indirecta en la calidad de vida individual, familiar y colectiva. 
      .col-lg-6(data-aos="fade-left")
        figure
          img.img-t.m-auto(src='@/assets/curso/tema4/img01.png')

    p Luego en la búsqueda de normatividad aplicable a salud pública también debe ser analizada la normatividad en temas de ambiente. 

    Separador

    #t_4_1.titulo-segundo.color-acento-contenido.pt-4(data-aos="zoom-out-right")
      h2 4.1.	Normatividad de importancia

    .bg_fondo15
      p.mb-4 De acuerdo Bernal, O y Forero J, 2011, una de las leyes de mayor importancia en el sector salud es la Ley 100 (1993), que reformó al sector salud en el país, en el objeto, fundamentos y características del sistema. Establece, entre otros la protección integral, es decir que el sistema general de seguridad social en salud brindará atención en salud integral a la población en sus fases de educación, información y fomento de la salud y la prevención, diagnóstico, tratamiento y rehabilitación en cantidad, oportunidad, calidad y eficiencia (p.88).

      .row.justify-content-center.mb-4
        .col-lg-10
          .tarjeta-color.bg_color10.p-4(data-aos="fade-down")
            .row.justify-content-center.align-items-center
              .col-lg-5.mb-4.mb-lg-0
                figure
                  img.img-t.m-auto(src='@/assets/curso/tema4/img03.png') 
              .col-lg-6 
                p La importancia de esta ley es que, aunque desde 1993 se estableció que se debe informar todos los aspectos relevantes al sistema de salud pública, la ley 100 (1993) definió responsabilidades de cada actor diferenciando el nacional del regional, así como hacer el seguimiento a elementos como: 
                ul.lista-ul
                  li 
                    i.fas.fa-angle-right(style= "color: #5D00F5")
                    | Indicadores de precios de medicamentos.
                  li 
                    i.fas.fa-angle-right(style= "color: #5D00F5")
                    | Elementos de gestión y calidad.

    .row.justify-content-center
      .col-lg-10  
        .tarjeta--container.row.mb-5
          .col-lg.tarjeta.color-primario.p-5(data-aos="fade-right")
            .row.justify-content-center.mb-4
              .col-6
                figure
                  img.img-t.m-auto(src='@/assets/curso/tema4/img04.svg', alt='Texto que describa la imagen')
              
            h4.text-center.mb-4 Decreto único reglamentario del sector salud<br>y protección social
            p.m-0.text-center Este es el denominado decreto 780 (2016): por medio del cual se expide el decreto único reglamentario del sector salud y protección social, en su parte 8 normas relativas a la salud pública, título VIII sistema de vigilancia en salud pública.
            
          .col-lg.tarjeta.color-acento-botones.p-5(data-aos="fade-left")
            .row.justify-content-center.mb-4
              .col-6
                figure
                  img.img-t.m-auto(src='@/assets/curso/tema4/img05.svg', alt='Texto que describa la imagen')
              
            h4.text-center.mb-4 Decreto Único Reglamentario del Sector Ambiente<br>y Desarrollo Sostenible
            p.m-0.text-center Según el Ministerio de Ambiente y desarrollo sostenible (s.f.), el decreto 1076 del 26 de mayo de 2015, es una compilación de las normas expedidas por el gobierno nacional en cabeza del presidente de la república, la pretensión de esta iniciativa es recoger en un solo cuerpo normativo todos los decretos reglamentarios vigentes expedidos hasta la fecha, que desarrollan las leyes en materia ambiental.

    .tarjeta.bg_color15.p-3(data-aos="fade-up")
      p.m-0 En materia ambiental se compilaron en un solo decreto aproximadamente 1650 artículos que se encontraban dispersos en 84 decretos reglamentarios. El decreto contiene tres libros, el primero de ellos referente a la Estructura del sector ambiental, el segundo al régimen reglamentario del sector ambiente y el tercero a disposiciones finales.
      
    Separador

    #t_4_2.titulo-segundo.color-acento-contenido.pt-4(data-aos="zoom-out-right")
      h2 4.2.	Otras normas

    p.mb-4.mb-lg-5 El marco normativo del país en relación con salud pública y medio ambiente es de gran extensión, su análisis debe ser particular, es decir, en el momento de requerir se debe realizar una búsqueda exhaustiva de la información para analizarla, sin embargo, se resaltan algunas:
                   
    .row.justify-content-center.mb-5(data-aos="fade-up-right")
      .col-lg-12
        SlyderB(:datos="datosSlyder")  

    .bg_color3.p-4(data-aos="fade-up")
      p.m-0 <b>Nota:</b> Este es un recuento muy general de algunas normas, siempre es relevante en el momento de realizar la revisión verificar el histórico de la legislación puntual que es requerida e indagar por las nuevas actualizaciones o derogaciones que apliquen.
      
    Separador

    #t_4_3.titulo-segundo.color-acento-contenido.pt-4(data-aos="zoom-out-right")
      h2 4.3.	Principio de rigor subsidiario

    p.m-0.mb-4 En materia ambiental se aplica el principio de rigor subsidiario consagrado en el artículo 63 de la Ley 99 (1993) el cual indica que: 

    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-right")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema4/img17.png')})`}"
      )
      .bloque-texto-g__texto.p-4(data-aos="fade-left")
        p Principio de Rigor Subsidiario. Las normas y medidas de policía ambiental, es decir aquellas que las autoridades medioambientales expidan para la regulación del uso, manejo, aprovechamiento y movilización de los recursos naturales renovables, o para la preservación del medio ambiente natural, bien sea que limiten el ejercicio de derechos individuales y libertades públicas para la preservación o restauración del medio ambiente, o que exijan licencia o permiso para el ejercicio de determinada actividad por la misma causa, podrán hacerse sucesiva y respectivamente más rigurosas, pero no más flexibles, por las autoridades competentes del nivel regional, departamental, distrital o municipal, en la medida en que se desciende en la jerarquía normativa y se reduce el ámbito territorial de las competencias, cuando las circunstancias locales especiales así lo ameriten, en concordancia con el artículo 51 de la presente Ley. (Congreso de la República de Colombia, 1993).

    .row.justify-content-center.mb-4
      .col-12.col-md-10
        p.m-0 A partir de este principio se establece, que, sin importar la jerarquía de la legislación, en el campo ambiental, siempre se aplicará la norma de mayor rigurosidad, es decir, si hay dos normas que legislan sobre el mismo tema por ejemplo parámetros de calidad del agua, se deberá revisar cada uno de los valores de los parámetros y cumplir el de mayor rigurosidad, sin importar el nivel jerárquico de las normas.
    
    Separador

    #t_4_4.titulo-segundo.color-acento-contenido.pt-4(data-aos="zoom-out-right")
      h2 4.4.	Matriz legal ambiental

    p.mb-5 Para establecer la normativa aplicable en el campo ambiental y de salud pública, se recomienda seguir los pasos establecidos por la construcción de una matriz de requisitos legales a través del procedimiento sugerido Rodríguez, F. (s.f.) de la secretaría de ambiente de Bogotá:  

    .row.justify-content-center
      .col-lg-10.d-none.d-lg-block
        .row.mb-5.justify-content-evenly(data-aos="zoom-in-down").medidas_tarjetas-t4-4.medida_numero-t4-4 
          .col-lg-4.col-md-6.col-xl-4.mb-4.mb-xl-0
            .tarjeta-numerada.color-primario.p-4.mb-5 
              .tarjeta-numerada__numero.num_1
                .h2.numero 1
              p.m-0.text-center.flex-center-text Definir responsables.

            .tarjeta-numerada.color-primario.p-4.mb-5
              .tarjeta-numerada__numero.num_1
                .h2.numero 2
              p.text-center.flex-center-text.ms-2 Identificación de legislación, requisitos legales y otros requisitos (teniendo en cuenta el principio de rigor subsidiario).

            .tarjeta-numerada.color-primario.p-4.mb-5
              .tarjeta-numerada__numero.num_1
                .h2.numero 3
              p.text-center.flex-center-text.ms-2 Definir periodicidad de revisión y actualización.
          .col-lg-3.col-xl-3.mb-3.mb-xl-0
            figure
              img.img_tar-num.mb-4.mb-lg-0.d-none.d-lg-block(src='@/assets/curso/tema4/img18.svg')
          .col-lg-4.col-md-6.col-xl-4.mb-4.mb-xl-0
            .tarjeta-numerada.color-primario.p-4.mb-5
              .tarjeta-numerada__numero.num_1
                .h2.numero 4
              p.text-center.flex-center-text.ms-2 Definir canales y mecanismos de distribución y comunicación.

            .tarjeta-numerada.color-primario.p-4.mb-5
              .tarjeta-numerada__numero.num_1
                .h2.numero 5
              p.text-center.flex-center-text.ms-2 Metodología de evaluación del grado de cumplimiento de cada requisito legal.

            .tarjeta-numerada.color-primario.p-4
              .tarjeta-numerada__numero.num_1
                .h2.numero 6
              p.text-center.flex-center-text Generación de un registro. (p. 4).

    .row.justify-content-center.align-items-center
      .col-lg-10.d-lg-none.d-md-block
        .row.justify-content-center(data-aos="zoom-in-down").medidas_tarjetas-t4-4.medida_numero-t4-4 
          .col-md-6
            .tarjeta-numerada.color-primario.p-4.mb-5 
              .tarjeta-numerada__numero.num_1
                .h2.numero 1
              p.m-0.text-center.flex-center-text Definir responsables.

            .tarjeta-numerada.color-primario.p-4.mb-5
              .tarjeta-numerada__numero.num_1
                .h2.numero 2
              p.text-center.flex-center-text.ms-2 Identificación de legislación, requisitos legales y otros requisitos (teniendo en cuenta el principio de rigor subsidiario).

            .tarjeta-numerada.color-primario.p-4.mb-5
              .tarjeta-numerada__numero.num_1
                .h2.numero 3
              p.text-center.flex-center-text.ms-2 Definir periodicidad de revisión y actualización.
          .col-md-6
            .tarjeta-numerada.color-primario.p-4.mb-5
              .tarjeta-numerada__numero.num_1
                .h2.numero 4
              p.text-center.flex-center-text.ms-2 Definir canales y mecanismos de distribución y comunicación.

            .tarjeta-numerada.color-primario.p-4.mb-5
              .tarjeta-numerada__numero.num_1
                .h2.numero 5
              p.text-center.flex-center-text.ms-2 Metodología de evaluación del grado de cumplimiento de cada requisito legal.

            .tarjeta-numerada.color-primario.p-4.mb-4
              .tarjeta-numerada__numero.num_1
                .h2.numero 6
              p.text-center.flex-center-text Generación de un registro. (p. 4).

    .row.justify-content-center.mb-5
      .col-md-6.d-lg-none.d-md-block
        figure
          img.img-t.m-auto(src='@/assets/curso/tema4/img18.svg')
    
    p.mb-4.mb-lg-0 Usualmente las matrices legales de las organizaciones o entidades son desarrolladas en ese último paso de generación de un registro, el cual hace referencia a un documento donde quede consignado que base normativa fue identificada y si el proyecto o la organización lo cumple o no, para ello se realizan tablas con la siguiente información como mínimo:

    .row.justify-content-center.align-items-center
        .col-lg-4(data-aos="fade-right")
          figure.justify-center
            img.img-t.m-auto(src="@/assets/curso/tema4/img20.svg") 
        .col-lg-8.mt-3(data-aos="fade-left")
          ol.lista-ol--cuadro.mt-4
            li 
              .lista-ol--cuadro__vineta
                span 1
              | Tipo de Norma: describe la tipología de la norma que se identificó que es aplicable (ley, decreto, resolución, acuerdo, Norma Técnica Colombiana NTC, entre otros).
            li 
              .lista-ol--cuadro__vineta
                span 2
              | Número: indicar el número de dicha norma.
            li 
              .lista-ol--cuadro__vineta
                span 3
              | Fecha: fecha en la cual se creó la norma y entró en rigor.
            li 
              .lista-ol--cuadro__vineta
                span 4
              | Objeto: resumir el objetivo de la norma y para qué es aplicable.
            li 
              .lista-ol--cuadro__vineta
                span 5
              | Artículos que aplican: resumir que artículos de la norma aplican a la organización.
            li 
              .lista-ol--cuadro__vineta
                span 6
              | Aplicable; en las últimas columnas se debe evaluar con una (x) si la norma se aplica actualmente o no en la organización. 


</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    datosSlyder: [
      {
        titulo: 'Ley 9 (1979)',
        texto:
          'De acuerdo con García, C., García, J., y Vaca., M (2013) se creó el código sanitario nacional, adoptó un enfoque amplio de los aspectos que intervienen en la salud humana incluyendo elementos específicos en relación con la protección del medio ambiente, fundamentándose en la comprensión de que la relación del ser humano con su entorno ambiental es un determinante básico de la calidad de vida y la condición de salud (p.57).',
        imagen: require('@/assets/curso/tema4/img06.png'),
      },
      {
        titulo: 'Reglamento sanitario internacional (2005)',
        texto:
          'El alcance es prevenir y proteger la propagación internacional de enfermedades, proteger, controlarla y darle una respuesta de salud pública proporcionada y restringida a los riesgos, evitando al mismo tiempo las interferencias innecesarias con el tráfico y el comercio internacional.',
        imagen: require('@/assets/curso/tema4/img07.png'),
      },
      {
        titulo: 'CONPES 3550 (2008)',
        texto:
          'Lineamientos para la formulación de la política integral de Salud ambiental Con énfasis en los componentes de calidad de aire, calidad de agua y seguridad química.',
        imagen: require('@/assets/curso/tema4/img08.png'),
      },
      {
        titulo: 'Decreto 3678 (2010)',
        texto:
          'Define los criterios que deben tener en cuenta las autoridades para imponer sanciones de tipo ambiental.',
        imagen: require('@/assets/curso/tema4/img09.png'),
      },
      {
        titulo: 'CONPES 3700 (2011)',
        texto:
          'Estrategia Institucional para la Articulación de Políticas y Acciones en Materia de Cambio Climático en Colombia.',
        imagen: require('@/assets/curso/tema4/img10.png'),
      },
      {
        titulo: 'Política de salud ambiental (2011)',
        texto:
          'Adopta el modelo de determinación social de la salud, que considera que la salud o la enfermedad no son un acontecimiento de orden exclusivamente bio natural, ni se dan aisladas en un ambiente individual, sino que son la resultante de relaciones e interacciones dinámicas entre el individuo biológico, su entorno y sus condiciones de vida en los ámbitos económico, ambiental, cultural y político (García, C., García, J., y Vaca., M, 2013, p.61).',
        imagen: require('@/assets/curso/tema4/img11.png'),
      },
      {
        titulo: 'Objetivos de desarrollo sostenible (2015)',
        texto:
          'Agenda 2030: específicamente para este caso el objetivo 3 el cual busca garantizar una vida sana y promover el bienestar para todos en todas las edades.',
        imagen: require('@/assets/curso/tema4/img12.png'),
      },
      {
        titulo: 'Resolución 1536 (2015)',
        texto:
          'La cual se establecen disposiciones sobre el proceso de planeación integral para la salud, estableciendo sus disposicines las cuales están a cargo de las entidades territoriales del nivel departamental, distrital y municipal.',
        imagen: require('@/assets/curso/tema4/img13.png'),
      },
      {
        titulo: 'Resolución 518 (2015)',
        texto:
          'Resolución 518 (2015) por la cual se dictan disposiciones en relación con la gestión de la salud pública y se establecen directrices para la ejecución, seguimiento y evaluación del Plan de Salud Pública de Intervenciones Colectivas (PIC).',
        imagen: require('@/assets/curso/tema4/img14.png'),
      },
      {
        titulo: 'Ley 1931 (2018)',
        texto:
          'La cual define las características para la gestión del cambio climático de las personas públicas y privadas.',
        imagen: require('@/assets/curso/tema4/img15.png'),
      },
      {
        titulo: 'Resolución 1561 (2019)',
        texto:
          'Por el cual se establecen los términos de referencia para los estudios de impacto ambiental.',
        imagen: require('@/assets/curso/tema4/img16.png'),
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
