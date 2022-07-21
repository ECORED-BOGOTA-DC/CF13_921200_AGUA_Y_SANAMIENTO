<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido    
      .titulo-principal__numero
        span.text-white 3
      h1 Sistemas de recolección de información en salud
  
    .row.justify-content-center.align-items-center           
      .col-12.col-md-10
        p(data-aos="fade-down").bg_cajon.p-3.text-center Mantener información documentada sobre los sistemas de salud, las estrategias de intervención implementadas y las condiciones generales de la población permite actuar de manera apropiada ante eventos no deseados como pandemias, enfermedades colectivas entre otros.
        img.img-a.img-t.mt-5(data-aos="slide-left")(src='@/assets/curso/tema3/img01.png', alt='')
        p.m-0.mt-4 De acuerdo con Bernal, O., y Forero J, (2011) en su artículo sistemas de información en el sector salud en Colombia, se puede definir a los sistemas de recolección como: 
        .hr 
        .bloque-texto-d.color-secundario.p-4
          .bloque-texto-d__texto.mb-2
            i.fas.fa-quote-left
          p.m-0.bloque-texto-d__texto Aquel que integra la recolección, procesamiento y reporte de información necesaria para el mejoramiento de los servicios de salud, a través de una mejor gestión en todos los niveles del sistema.           
          .bloque-texto-d__autor 
            p.mb-0.m-right2.mt-4 <b>Bernal, O., y Forero J, (2011), (p.88)</b>
            i.fas.fa-quote-right

    Separador

    #t_3_1.titulo-segundo.color-acento-contenido(data-aos="zoom-out-right")
      h2 3.1.	Clasificación de los sistemas de recolección de información

    p.m-0.mb-4 Teniendo en cuenta que las organizaciones del sector salud, dependiendo de donde provienen sus recursos se subdividen en públicas y privadas, de la misma forma se podría hacer una primera aproximación de la clasificación de los sistemas de recolección:  

    .bg_fondo14.mb-5
      .row.align-items-end
        .col-12.col-md-3.mb-4.mb-md-0(data-aos="fade-right")
          figure.justify-center
            img.img-fluid(src="@/assets/curso/tema3/img02.png")        
        .col-12.col-md-7(data-aos="fade-left")
          ul.lista-ul
            li 
              i.fas.fa-angle-right(style= "color: #5D00F5")
              p.mt-2.m-0 Públicos: dependientes del estado.
            li 
              i.fas.fa-angle-right(style= "color: #5D00F5")
              p.mt-2.m-0 Privados: prestadores de servicios de salud y agremiaciones, entre otras; aunque las instituciones privadas también deben reportar a los sistemas de información gubernamentales, sus sistemas son independientes, no se encuentran integrados y no necesariamente son compatibles con los estatales (Bernal, O., y Forero J, (2011), p.90).
    
    .row.justify-content-center
      .col-12.col-md-8
        p.m-0.border.border-2.p-2.text-center(data-aos="fade-up") Buscar información sobre las condiciones de salud de la población en Colombia se puede realizar gracias a la existencia de unos instrumentos de recolección de información que se han implementado durante la última década.

    Separador

    #t_3_2.titulo-segundo.color-acento-contenido(data-aos="zoom-out-right")
      h2 3.2.	Instrumentos de recolección de información existentes en Colombia

    p.m-0.mb-4 Aunque no todas las entidades prestadoras de servicios de salud pertenecen al estado, si todas están en la obligación de informar y reportar todas las variables que sean de especial seguimiento y que son determinadas por el Ministerio de Salud. 

    .row(data-aos="fade-right")
      .col-xl-11
        TabsA.color-acento-botones.mb-5
          .tarjeta.color-acento-botones--borde.p-4(titulo="Sistema de Vigilancia en Salud Pública (SIVIGILA)")
            .row
              .col-xl-12.mb-3.mt-2
                h5.ms-0.ms-xl-3 Sistema de Vigilancia en Salud Pública (SIVIGILA)
                p.m-0.mt-4.ms-0.ms-xl-3 El sistema regulador y que consolida la información es el Sistema de Vigilancia en Salud Pública (SIVIGILA), de acuerdo con Bernal, O., y Forero J, (2011) “es un sistema de reporte de eventos de interés en salud pública, gestionado por el Instituto Nacional de Salud (INS), que reporta especialmente patologías infecciosas, aunque recientemente se ha adicionado un módulo de mortalidad materna” (p.90).
            .row.justify-content-around.align-items-center
              .col-xl-8.mb-4
                p.m-0.ms-0.ms-xl-3 Este sistema siempre se encuentra en actualización para mejorar los reportes, una de las últimas actualizaciones más importantes fue realizada en el 2017 mejorando procesos de notificación y gestión de información que se aplicarán en el periodo del 2018 al 2020 (Instituto Nacional de Salud INS, 2017).
              .col-xl-4
                figure
                  img(src='@/assets/curso/tema3/img04.svg', alt='Texto que describa la imagen')
          
          .tarjeta.color-acento-botones--borde.p-4(titulo="Sistema Integrado de Información de la Protección Social (SISPRO)")
            .row
              .col-xl-12.mb-3.mt-2
                h5 Sistema Integrado de Información de la Protección Social (SISPRO)
                p.m-0 Este sistema es considerado la bodega de datos de salud del país, en el cual integra datos e información de salud, pensiones, riesgos profesionales, trabajo, empleo y asistencia social. Cada fuente de información del Sistema de Información de la Protección Social (SISPRO) tiene una estructura de reporte y consolidación independiente (Bernal, O y Forero J, 2011, p.90).

            .row.justify-content-around.align-items-center
              .col-xl-7.mb-4
                p.m-0.mb-3 Se puede definir algunas características generales del sistema de acuerdo con la información suministrada por el ministerio de salud y protección social (s.f.)
                ul.lista-ul
                  li 
                    i.fas.fa-angle-right(style= "color: #5D00F5")
                    p.mt-1.m-0 Está conformado por bases de datos.
                  li 
                    i.fas.fa-angle-right(style= "color: #5D00F5")
                    p.mt-1.m-0 Cuenta con información de oferta y demanda de servicios de salud y todo lo asociado a los mismos.
                  li 
                    i.fas.fa-angle-right(style= "color: #5D00F5")
                    p.mt-1.m-0 Permite la construcción de indicadores.
                  li 
                    i.fas.fa-angle-right(style= "color: #5D00F5")
                    p.mt-1.m-0 Recoge información de fuentes internas y externas del ministerio.
              .col-xl-5.align-self-end.mb-5
                figure
                  img(src='@/assets/curso/tema3/img05.svg', alt='Texto que describa la imagen')

    p.m-0.mb-4.mb-md-5 Este sistema es alimentado o construido por medio de diferentes reportes que recibe de otros instrumentos como: 

    .row.justify-content-center
      .col-12.col-md-4.mb-4.mb-md-0(data-aos="fade-right")
        figure
          img.img271(src='@/assets/curso/tema3/img06.svg')
      .col-12.col-md-8(data-aos="fade-left")
        AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
          .row(titulo="El Registro Único de Afiliados (RUAF)")
            .col-md-12.mb-4.mb-md-0
              p.m-0.mb-4.mx-5 Según Bernal, O., y Forero J, (2011) maneja información de afiliación a todos los componentes de la protección social (salud, pensiones, riesgos profesionales, etc.) La información es reportada directamente por las administradoras al Registro Único de Afiliados (RUAF) excepto salud que tiene un mecanismo de reporte diferente a través del Fondo de Solidaridad y Garantía (FOSYGA) (p. 90).
              p.m-0.mx-5 El sistema permite el flujo de información entre los actores del Sistema, respetando la confidencialidad de la información y el rol de cada uno de los administradores. (Ministerio de Salud, 2020).
          div(titulo="Los Registros Individuales de Prestación de Servicios de Salud (RIPS)")
            p.m-0.mx-5 Estos ya son un conjunto de datos mínimo y básicos del sistema de seguridad social, fue creado en cumplimiento de la resolución 3372 (2000) y es aplicable para instituciones prestadoras de salud (IPS) profesionales independientes entre otros. Con estos datos se realiza regulación, control y soporte de venta de servicios de salud (Ministerio de Salud, 2015).
          div(titulo="La Planilla Integrada de Liquidación de Aportes (PILA)")
            p.m-0.mx-5 La Planilla Integrada de Liquidación de Aportes (PILA) es la base de datos que maneja información de empleo, cotizantes y aportantes a los diferentes módulos de la protección social (Bernal, O y Forero J, 2011, p.90).
          .row(titulo="El Sistema de Gestión Hospitalaria (SIHO)")
            .col-md-12.mb-4.mb-md-0
              p.m-0.mb-4.mx-5 El Sistema de Gestión Hospitalaria (SIHO) el cual fue creado bajo el Decreto 2193 (2004) hace obligatorio el reporte de los Registros Individuales de Prestación de Servicios de Salud (RIPS) al Ministerio de Salud, los reportes periódicos de las finanzas y servicios a la superintendencia de salud por la mayoría de los actores que intervienen (Zapata, J, 2013, p.25).
              p.m-0.mx-5 Este sistema recopila en forma periódica información contable, flujos de ingresos y gastos, la producción hospitalaria y de pasivos pensionales, entre otra información que reportan los cerca de mil hospitales públicos (Zapata, J, 2013, p.31).
          div(titulo="El Sistema de Información de Precios de Medicamentos (SISMED)")
            p.m-0.mx-5.mb-4 El Sistema de Información de Precios de Medicamentos (SISMED) es una estrategia de salud pública que tiene por objetivo mejorar la accesibilidad a medicamentos esenciales por parte de la población, especialmente para aquellos de escasos recursos económicos, enmarcado en los lineamientos de lucha contra la pobreza y descentralización.
            p.m-0.mx-5 El sistema de información de precios medicamentos registra datos de precios de compra y venta de medicamentos por parte de IPS, EPS, droguerías, etc. (Bernal, O y Forero J, 2011, p.90).


    


</template>

<script>
export default {
  name: 'Tema3',
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
