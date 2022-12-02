<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido    
      .titulo-principal__numero
        span.text-white 2
      h1 Metodología de evaluación de programas de salud

    .bg_fondo7
      .row.justify-content-center.mb-4
        .col-md-10
          .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-4(data-aos="fade-right")
            .bloque-texto-g__img(
              :style="{'background-image': `url(${require('@/assets/curso/tema2/img01.png')})`}"
            )
            .bloque-texto-g__texto.p-4
              p María Naranjo (2006) en su artículo evaluación de programas de salud, establece que los programas de salud están diseñados para alcanzar unos objetivos concretos con el fin de mejorar el estado de salud de una población. En particular lograr estos objetivos requiere de actividades coherentes, organizadas e integradas de diferentes actores de la sociedad.

      .row.justify-content-center.mb-4
        .col-md-10
          p Con el fin de poder realizar revisiones y ajustes necesarios a los programas de salud es necesario hacer constante análisis y evaluación, donde se verifica si se están cumpliendo los objetivos para los cuales fue creado cada programa.

      .row.justify-content-center.mb-3
        .col-md-10(data-aos="fade-down")
          .bg_color10.p-4
            p.m-0 Las evaluaciones que se ejecuten deben tener una estructura definida y un proceso claro, así como una estructura sistemática y objetiva que minimicen al máximo el sesgo del evaluador, que permita ver el programa desde diferentes enfoques, entre los cuales están:

      .row.justify-content-center
        .col-md-6.col-lg.mb-3.mb-lg-0(data-aos="fade-right")
          .tarjeta-avatar.color
            img.img92.top_tarjavatar-t2(src='@/assets/curso/tema2/img02.svg' alt='AvatarTop')
            .tarjeta.color.bg_color11
              .p-4
                p.text-center Valoración sistemática y objetiva.

        .col-md-6.col-lg.mb-3.mb-lg-0(data-aos="fade-up")
          .tarjeta-avatar.color
            img.img92.top_tarjavatar-t2(src='@/assets/curso/tema2/img03.svg' alt='AvatarTop')
            .tarjeta.color.bg_color11
              .p-4
                p.text-center Uso de procedimientos científicos para investigar la efectividad de los programas.

        .col-md-6.col-lg.mb-3.mb-lg-0(data-aos="fade-left")
          .tarjeta-avatar.color
            img.img92.top_tarjavatar-t2(src='@/assets/curso/tema2/img04.svg' alt='AvatarTop')
            .tarjeta.color.bg_color11
              .p-4
                p.text-center Procedimientos para orientar la toma de decisiones en las diferentes fases de ejecución de un programa.

        p.mt-4 Álvarez, C (2014) en su manual de operación denominado el modelo de evaluación de programas de salud resalta también la importancia de la evaluación de las estrategias y programas de salud, visto que es una herramienta esencial para la toma de decisiones y el mejoramiento paulatino de los programas y sus estrategias.
        p Por lo cual, las personas que participen de un programa de salud deben estar ampliamente capacitados en técnicas de evaluación y deben ejecutarla a través de diferentes etapas.

    Separador

    #t_2_1.titulo-segundo.color-acento-contenido(data-aos="zoom-out-right")
      h2 2.1.	Enfoques y alcances de evaluación

    p.mb-5 Álvarez, C. (2014) en su manual de operación respecto al modelo de evaluación de programas de salud, menciona que debido a los diferentes objetivos que pueden llegar a tener los programas de salud, es necesario tener enfoques que se adapten a la evaluación de esos objetivos al tiempo que se determina el alcance de los ítems a evaluar.

    .row.justify-content-center.mb-4
      .col-12.col-md-12
        p.text-center En general hay dos grandes corrientes de evaluación: 

    .row.justify-content-center.mb-5
      .col-12.col-md-10(data-aos="fade-down-right")
        figure
          img.img-fluid(src="@/assets/curso/tema2/img05.svg")

    p.mb-5 Cuando se habla del alcance de la evaluación se puede realizar en distintos niveles:

    .row.justify-content-center.mb-4
      .col-lg-10
        .tarjeta-avatar-b.tema2.mb-3
          .tarjeta-avatar-b__img
            img(data-aos="fade-right")(src='@/assets/curso/tema2/img06.svg' alt='AvatarTop' style= "height: 178px")
          .tarjeta.color-acento-contenido
            .p-4
              h4 Alcance global
              p.m-0 Integra la medición de las necesidades de salud de una población, tiene en cuenta las políticas públicas a las cuales esa población está sujeta y al mismo tiempo evalúa si alguna vez se han desarrollado otros programas de salud con la comunidad.
    
    .row.justify-content-center
      .col-lg-10
        .tarjeta-avatar-b.tema2.mb-3
          .tarjeta-avatar-b__img
            img(data-aos="fade-right")(src='@/assets/curso/tema2/img07.svg' alt='AvatarTop' style= "height: 178px")
          .tarjeta.color-acento-contenido
            .p-4
              h4 Alcance operativo
              p.m-0 Se define la evaluación en términos de la estructura y los procesos de atención a la salud, los procesos para prestar el servicio y los equipos con los que se cuenta.

    Separador
    
    #t_2_2.titulo-segundo.color-acento-contenido(data-aos="zoom-out-right")
      h2 2.2.	Etapas del proceso de evaluación

    p.mb-4 Álvarez, C. (2014) en su manual de operación en referencia al modelo de evaluación de programas de salud, manifiesta en términos generales, que el proceso de evaluación de un programa o alguno de sus componentes, debe ser planeado y organizado cuidadosamente. Sin embargo, generalizando los procesos evaluativos se puede dividir en tres grandes etapas:  

    .row.justify-content-center.mb-5.pb-5
      .col-12.col-md-10(data-aos="fade-up-right")
        figure
          img.img-fluid(src="@/assets/curso/tema2/img08.svg")

    .row.justify-content-center.mb-5
      .col-12.col-md-8
        .titulo-sexto.color-acento-contenido
          h5 Figura 1. 
          span Etapas del proceso de evaluación
        figure.mb-5(data-aos="fade-down")
          img.img-fluid(src="@/assets/curso/tema2/img09.svg")
        .tarjeta-color.bg_color3.mt-2
          .p-2
          p.text-center.pb-4 <b>Nota:</b> tomado de Álvarez, C. (2014). Manual de operación, el modelo de evaluación de programas de salud (p.35).
    
    ul.lista-ul.mb-5
      li 
        <i class="fas fa-circle fa-xs" style= "color:#009EE3 !important;"></i>
        h3.ps-2 Diagnóstico del entorno del programa y definición de propósitos generales de la evaluación

    .row.justify.content-center.align.items-center.mb-5
      .col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
        figure
          img.img-t.m-auto(src="@/assets/curso/tema2/img10.png")
      .col-lg-7.align-self-center(data-aos="fade-left")
        .cajon-b.color-primario.p-2.mb-2
          p.mb-4 Realizar un diagnóstico del entorno del programa es un proceso que debe tener en cuenta varios lineamientos y diferentes puntos de vista para tener un concepto global y así poder establecer los propósitos generales de la evaluación.
          p En primera medida se realiza el reconocimiento del contexto de operación del programa y una vez reconocido se procede a determinar los propósitos, en caso de no hacer un reconocimiento del contexto se pueden plantear propósitos que no se pueden cumplir o que simplemente no se necesitan, esto genera costos innecesarios en los programas y retrasos en los tiempos de ejecución de propósitos que sí son necesarios.

    ul.lista-ul.mb-4
      li 
        <i class="fas fa-circle fa-xs" style= "color:#009EE3 !important;"></i>
        h3.ps-2 Reconocimiento del contexto de operación del programa

    .row.justify.content-center.align.items-center.mb-5
      .col-lg-7.align-self-center.order-last.order-lg-first(data-aos="fade-right")
          p.m-0 Esta actividad se considera la base de los programas en salud, es tan relevante que debe ser considerada antes de iniciar la planeación y desarrollo de las actividades de evaluación de programas. Dentro del reconocimiento se debe estudiar el programa y los posibles problemas que este puede presentar sobre todo en términos de operación. Debido a esto se deben realizar visitas de campo, entrevistas informales con trabajadores y beneficiarios, revisión de infraestructura y de ser necesario elaborar listado de requerimientos.
      .col-lg-5.order-first.order-lg-last.mb-4.mb-lg-0(data-aos="fade-left")
        figure
          img.img-t.m-auto(src="@/assets/curso/tema2/img11.png")

    .bg_fondo8.mb-4
      .row.align-items-center
        .col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
          figure.justify-center
            img.img-t.m-auto(src="@/assets/curso/tema2/img12.svg")        
        .col-lg-8(data-aos="fade-left")
          p.m-0.me-4 Cuando la evaluación se hace sobre un propósito poblacional es necesario identificar las características de las localidades, los servicios de salud, los perfiles del personal, la infraestructura que incluye los centros de salud, archivos, consultorios, equipos y ver si todo está articulado en función de la comunidad. Por ejemplo, de nada serviría tener una infraestructura adecuada si el horario de atención no se ajusta a las necesidades poblacionales, o si esta no puede acceder al lugar porque no hay vías.

    ul.lista-ul.mb-4.pt-5
      li 
        <i class="fas fa-circle fa-xs" style= "color:#009EE3 !important;"></i>
        h3.ps-2 Determinación de los propósitos de la evaluación

    p Este punto es clave para atender las expectativas de los usuarios principales, determinando si los propósitos que se quieren alcanzar corresponden a los requerimientos de información de quien toma las decisiones.
    p Los propósitos principalmente se deben determinar teniendo en cuenta la efectividad, eficiencia y el impacto final de cada programa, sin embargo, para fines administrativos también se puede tener una perspectiva de enfocar los propósitos de evaluación frente a la calidad de la atención, necesidades o cumplimiento de la normatividad institucional.

    .bg_fondo9.mb-5
      .row.align-items-center(data-aos="zoom-in-up")
        .col-lg-7
          p.mt-4 Un ejemplo de un propósito definido acorde a la efectividad, eficiencia e impacto final es: determinar las coberturas de atención de los programas de prevención y promoción de la salud a nivel de la población usuaria de servicios. Mientras que un propósito con un fin administrativo sería: determinar la calidad de la atención médica hospitalaria para población adscrita al Sistema de Protección Social en Salud y el grado de satisfacción de sus usuarios.    
          p.m-0 Cabe resaltar que los propósitos no son excluyentes y que se pueden alcanzar de manera simultánea o progresiva, sin embargo, cada uno de los propósitos debe medirse con distintas metodologías, instrumentos y criterios de evaluación, así como deben disponer de diferentes recursos materiales y financieros para poder cumplirse. Los programas deben ser claros para que no se presente ningún tipo de ambigüedad, al tiempo que se articulan con los objetivos y cuente con los recursos necesarios. 
        .col-lg-5
          figure.justify-center
            img.img-t.m-auto(src="@/assets/curso/tema2/img15.svg") 

    ul.lista-ul.mb-4.pt-5
      li 
        <i class="fas fa-circle fa-xs" style= "color:#009EE3 !important;"></i>
        h3.ps-2 Descripción del programa a evaluar

    p.m-0 Esta etapa es una de las actividades más delicadas debido a que es el acercamiento formal del evaluador con el objeto de estudio y eso hace que conozca a detalle cada uno de los componentes del programa. 
    p.mb-5 En este punto, de ser necesario, se deben incorporar programas de intervención, mecanismos de control de gestión, parámetros de comparación, seguimiento de objetivos, metas y actividades de los programas, entre otros instrumentos, por lo que la decisión del evaluador incide directamente en la calidad del programa.

    .row.justify-content-center.mb-4
      .col-12.col-md-12
        p.text-center El evaluador debe determinar a rasgos generales si:

    .row.justify-content-center.align-items-center(data-aos="fade-right")
      .col-lg-5.height_tarjavatar-b2-t2
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/tema2/img16.svg' alt='AvatarTop')
          .tarjeta.color.bg_color14
            .p-4
              p.text-center.mt-2.mt-lg-4 El programa es ambiguo o poco claro.

      .col-lg-5.height_tarjavatar-b2-t2
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/tema2/img17.svg' alt='AvatarTop')
          .tarjeta.color.bg_color14
            .p-4
              p.text-center.mt-2.mt-lg-4 Las metas y actividades son precisas.

    .row.justify-content-center.align-items-center(data-aos="fade-left")
      .col-lg-5.height_tarjavatar-b2-t2
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/tema2/img18.svg' alt='AvatarTop')
          .tarjeta.color.bg_color14
            .p-4
              p.text-center.mt-2.mt-lg-3 Los resultados adicionales a los objetivos son trascendentales.

      .col-lg-5.height_tarjavatar-b2-t2
        .tarjeta-avatar-b.mb-5
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/tema2/img19.svg' alt='AvatarTop')
          .tarjeta.color.bg_color14
            .p-4
              p.text-center.mt-2.mt-lg-3 Los recursos materiales y físicos están disponibles.

    .bg_fondo10.mb-0.mb-md-4
      .row.justify-content-center.align-items-center(data-aos="zoom-in-up")
        .col-lg-3
          figure.justify-center
            img.img-t.mx-auto(src="@/assets/curso/tema2/img21.svg") 
        .col-lg-9.mt-5
          p.m-0 Luego de realizar los respectivos análisis, el evaluador debe entregar un informe que por lo menos debe tener los siguientes elementos:
          ol.lista-ol--cuadro.mt-2
            li 
              .lista-ol--cuadro__vineta
                span 1
              | Objetivos del programa.
            li 
              .lista-ol--cuadro__vineta
                span 2
              | Recursos de operación.
            li 
              .lista-ol--cuadro__vineta
                span 3
              | Indicadores y metas.
            li 
              .lista-ol--cuadro__vineta
                span 4
              | Financiamiento con calendario y conceptos de gasto.
            li 
              .lista-ol--cuadro__vineta
                span 5
              | Evidencias de las acciones realizadas a la fecha.

    ul.lista-ul.mb-4.pt-5
      li 
        <i class="fas fa-circle fa-xs" style= "color:#009EE3 !important;"></i>
        h3.ps-2 Formulación de preguntas de evaluación:

    p.mb-4 El proceso evaluativo se basa en la determinación de las preguntas de evaluación, estas preguntas deben ser congruentes con los criterios de evaluación y deben estar relacionadas con los propósitos generales de la evaluación y del programa.

    .bg_fondo11.mb-5.mb-lg-0
      .row.align-items-center
        .col-lg-4
          figure(data-aos="fade-right")
            img.img-t.m-auto(src="@/assets/curso/tema2/img23.png") 
        .col-lg-7(data-aos="fade-left")
          p.mb-4 Se recomienda que las preguntas de la evaluación cumplan con las siguientes características:
          ol.lista-ol--cuadro.ms-3.m-0
            li 
              .lista-ol--cuadro__vineta
                span 1
              | Deben ser exhaustivas y realizadas a todo el personal estratégico que forma parte del programa.
            li 
              .lista-ol--cuadro__vineta
                span 2
              | Deben haber sido consensuadas con los tomadores de decisiones para garantizar que sean preguntas útiles para el programa.
            li 
              .lista-ol--cuadro__vineta
                span 3
              | Deben haber sido seleccionadas y agrupadas para mantener un enfoque metodológico.
          
    .row.justify-content-end.mb-5
      .col-lg-8
        p.m-0 Las preguntas siempre deben tener un marco lógico de acuerdo con el programa, una estructura adecuada, evaluar los resultados esperados del programa, los recursos utilizados, los tiempos gastados y la relación entre diferentes acciones con sus respectivos resultados.      

    ul.lista-ul
      li 
        <i class="fas fa-circle fa-xs" style= "color:#009EE3 !important;"></i>
        h3.ps-2 Diseño metodológico y trabajo de campo

    .row.justify-content-center
      .col-lg-11
        figure.mb-4(data-aos="fade-down")
          img(src="@/assets/curso/tema2/img24.png") 
        p Una vez se definen los propósitos, el diseño metodológico es el cómo se van a realizar, para ello es necesario hacer diseño de estudio y planes de acción, definir los instrumentos y fuentes de información y organizar y ejecutar la supervisión del trabajo de campo.

    ul.lista-ul.pt-5.mb-5
      li 
        <i class="fas fa-circle fa-xs" style= "color:#009EE3 !important;"></i>
        h3.ps-2 Diseño de estudio y plan de acción

    .row.justify-content-center.align-items-center
      .col-lg-8.mb-4.mb-lg-0    
        .bg_fondo12.mb-5(data-aos="fade-right")
          p Esta etapa permite definir los procedimientos de estudio, la selección de las personas que serán estudiadas y las variables e instrumentos con las que se realizará la recolección de información.
          p A través del diseño de estudio se busca maximizar la confiabilidad y validez de los datos al tiempo que se reducen los posibles errores en los resultados. Para ello se debe hacer un análisis estadístico en la cantidad de información a recolectar teniendo en cuenta principios como muestra, universo, nivel de confiabilidad, entre otros.
        p El diseño de estudio debe ir de la mano con el plan de acción donde se determina si se hará una sola medición o si es necesario que se realicen mediciones comparativas y longitudinales, por ejemplo, determinar si hay un medicamento disponible en un centro de salud requerirá de solo una medición, si se habla de eficiencia en gastos de atención en salud por paciente atendido requerirá la comparación con otros puntos de atención para determinar que en promedio se gasta la misma cantidad de recursos en un paciente de un punto A que en un paciente de un punto B. Finalmente si se habla de satisfacción de la atención es necesario hacer un estudio antes, durante y después de la prestación del servicio para garantizar la confiabilidad de los resultados.
      .col-lg-4.mb-4
        figure(data-aos="fade-left")
          img.img-t.m-auto(src="@/assets/curso/tema2/img26.svg") 

    ul.lista-ul.mb-4.pt-5
      li 
        <i class="fas fa-circle fa-xs" style= "color:#009EE3 !important;"></i>
        h3.ps-2 Definición de instrumentos y fuentes de información

    p.mb-5 La confiabilidad, precisión, exactitud y reproducibilidad de los datos obtenidos en cualquier evaluación dependen de los instrumentos con los que se realice y de las fuentes de información seleccionadas. Dada la importancia de este procedimiento es necesario realizarlo de forma técnica y precisa, para ello se pueden utilizar:

    .row.mb-0.mb-md-5.mb-lg-5
      .col-sm-6.col-xl-3.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip.color-secundario(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema2/img27.png')})`}")
            .tarjeta-flip__contenido.p-2.p-xl-3
              p.mb-4.mt-4.text-center <b>Diseños no experimentales</b>
              p.text-center Son procesos donde se realiza una sola medición, no hace falta tener resultados previos ya que estos no van a influir sobre los resultados ni tampoco es necesario hacer mediciones posteriores por consiguiente no van a tener correlación con el presente.

      .col-sm-6.col-xl-3.mb-4.mb-xl-0
        .tarjeta.tarjeta-flip.color-secundario(@mouseover="indicadorTarjetaFlip = false")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema2/img28.png')})`}")
            .tarjeta-flip__contenido.p-2.p-xl-3
              p.mb-4.mt-4.text-center <b>Diseños experimentales para la evaluación de programas</b>
              p.text-center Aseguran los resultados obtenidos, tienen un gran rigor científico y la experimentación se hace a condiciones reales, de este modo no se permite la extrapolación de resultados haciendo que estos sean válidos.

      .col-sm-6.col-xl-3.mb-4.mb-sm-0
        .tarjeta.tarjeta-flip.color-secundario(@mouseover="indicadorTarjetaFlip = false")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema2/img29.png')})`}")
            .tarjeta-flip__contenido.p-2.p-xl-3
              p.mb-4.mt-4.text-center <b>Diseños experimentales para la evaluación de programas</b>
              p.text-center En este caso es válido experimentar en condiciones diferentes a las reales, son útiles cuando se quiere por ejemplo aplicar la introducción de nuevas técnicas de capacitación.

      .col-sm-6.col-xl-3
        .tarjeta.tarjeta-flip.color-secundario(@mouseover="indicadorTarjetaFlip = false")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema2/img30.png')})`}")
            .tarjeta-flip__contenido.p-2.p-xl-3
              p.mb-4.mt-4.text-center <b>Diseños cuasiexperimentales</b>
              p.text-center En este tipo de estudios el evaluador puede intervenir en las condiciones en las que se conducirá el estudio.

    ul.lista-ul.mb-4.pt-5
      li 
        <i class="fas fa-circle fa-xs" style= "color:#009EE3 !important;"></i>
        h3.ps-2 Organización, ejecución y supervisión del trabajo de campo

    .bg_fondo13
      .row.align-items-center
        .col-lg-4.mb-4.mb-lg-0
          figure(data-aos="fade-right")
            img.img-t.m-auto(src="@/assets/curso/tema2/img31.png") 
        .col-lg-8(data-aos="fade-left")
          p.m-0 Cuando se van a realizar las actividades de evaluación es importante contar con un coordinador de equipo, que conduzca tanto las actividades técnicas como las administrativas a fin de optimizar tiempos, al igual es recomendable que haya investigadores de campo, estadistas e informáticos en el equipo, así como un administrador de recursos financieros.
          p.m-0.mb-4 Los resultados de la ejecución de la evaluación siempre deben presentarse en un informe técnico que incluye el nombre de las personas que realizaron el estudio, resumen de las actividades desarrolladas, introducción con antecedentes, objetivos claros, métodos explicados, resultados con interpretación, conclusiones y bibliografía.



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
