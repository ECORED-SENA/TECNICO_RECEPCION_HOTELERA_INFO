<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/fondo-banner-principal.png')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0 Servicio de recepción hotelera
          
          .h2 Información del programa
          .banner-principal__datos
            ul
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto Servicio de recepción hotelera
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 633400
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Total Horas: 
                p.banner-principal__datos__item__texto 2208 Horas
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Duración en meses: 
                p.banner-principal__datos__item__texto 15 meses
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto virtual
        .d-none.d-lg-block.col-lg-5
          //- img(src="@/assets/curso/banner-princiapal.svg")
          .video
            | <iframe data-v-1f9e4816="" width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 1. Presentación

    p El 
      b Servicio Nacional de Aprendizaje – SENA 
      | le da la bienvenida al programa de formación 
      b Técnico en Servicio de Recepción Hotelera, 
      | cuyo objetivo es aportar a su proceso de formación en el área de 
      b.fst-italic hotelería y turismo, 
      | ofreciéndole la oportunidad de desempeñarse laboralmente como recepcionista y representante de reservas en pequeños, medianos y grandes hoteles en las diferentes regiones del país y proyectarse en el mercado nacional e internacional del turismo.
      br
      br
      | Este programa está diseñado para dar solución a las necesidades de personal capacitado en el área de 
      b recepción y reservas en las empresas hoteleras y de alojamiento, 
      | así mismo, para que los aprendices logren desarrollar conocimientos, habilidades y destrezas, trabajo en equipo, buenas relaciones con los clientes y puedan continuar sus estudios a nivel tecnológico.
      br
      br
      | El programa comprende una etapa lectiva, en la que el aprendiz desarrolla procesos de aprendizaje, y otra etapa productiva en la que se tiene la oportunidad de realizar prácticas en diferentes alternativas como contrato de aprendizaje, pasantías, proyecto productivo o unidades productivas familiares.
      br
      br
      | Esta modalidad de formación le brindará flexibilidad para ajustar sus tiempos de acuerdo con sus necesidades; contando con el acompañamiento continuo del tutor a través de encuentros sincrónicos y asincrónicos.
      br
      br
      b ¡Bienvenido al SENA y le invitamos a hacer del turismo su profesión!

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 2. Justificación del programa

    p La industria hotelera colombiana ocupa el segundo lugar en aporte de divisas al país, prueba de ello es que se ha desarrollado satisfactoriamente en las últimas décadas siendo responsable de la generación de inversiones por US$14.055 millones, de acuerdo con datos registrados por el segmento de comercio, restaurantes y hoteles en la balanza de pagos del Banco de la República. También es de resaltar que entre 2010 y 2017 se abrieron más de 200 hoteles en el país, de los cuales 123 pertenecen a cadenas hoteleras internacionales.
      br
      br
      |En este sentido, el programa ofrece al sector un perfil de desempeño para la atención de la recepción hotelera basado en habilidades de gestión del servicio a clientes, manejo de la operación de la recepción desde las técnicas y procedimientos establecidos.
      br
      br
      |De igual manera, el programa formará personas calificadas y cualificadas para atender los requerimientos operativos de un sector altamente competitivo, con capacidad de análisis, reflexión, actitud de liderazgo, creatividad e innovación en la búsqueda de soluciones a problemas reales, capacidad de adaptación a nuevas situaciones, determinación y perseverancia, con disposición hacia el trabajo en equipo, con habilidades para optimizar los recursos con responsabilidad y eficiencia, con valores y principios orientados hacia el respeto por la vida, la biodiversidad y su conservación impactando en el desarrollo sostenible de su región.


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 3. Competencias a desarrollar

    ul.lista-ul
        li 
          i.fas.fa-angle-right
          | Aplicar prácticas de protección ambiental, seguridad y salud en el trabajo de acuerdo con las políticas organizacionales y la normatividad vigente.
        li 
          i.fas.fa-angle-right
          | Desarrollar procesos de comunicación eficaces y efectivos, teniendo en cuenta situaciones de orden social, personal y productivo.
        li 
          i.fas.fa-angle-right
          | Ejercer derechos fundamentales del trabajo en el marco de la constitución política y los convenios internacionales.
        li 
          i.fas.fa-angle-right
          | Enrique Low Murtra-Interactuar en el contexto productivo y social de acuerdo con principios éticos para la construcción de una cultura de paz.
        li 
          i.fas.fa-angle-right
          | Generar hábitos saludables de vida mediante la aplicación de programas de actividad física en los contextos productivos y sociales.
        li 
          i.fas.fa-angle-right
          | Gestionar procesos propios de la cultura emprendedora y empresarial de acuerdo con el perfil personal y los requerimientos de los contextos productivo y social.
        li 
          i.fas.fa-angle-right
          | Interactuar en lengua inglesa de forma oral y escrita dentro de contextos sociales y laborales según los criterios establecidos por el Marco Común Europeo de Referencia para las Lenguas.
        li 
          i.fas.fa-angle-right
          | Procesar el recaudo de caja de acuerdo con normativa y el manual técnico.
        li 
          i.fas.fa-angle-right
          | Razonar cuantitativamente frente a situaciones susceptibles de ser abordadas de manera matemática en contextos laborales, sociales y personales.
        li 
          i.fas.fa-angle-right
          | Registrar al huésped de acuerdo con procedimiento y normativa técnica.
        li 
          i.fas.fa-angle-right
          | Reservar los servicios de acuerdo con procedimiento técnico.
        li 
          i.fas.fa-angle-right
          | Resultado del aprendizaje de la inducción.
        li 
          i.fas.fa-angle-right
          | Utilizar herramientas informáticas de acuerdo con las necesidades de manejo de Información.
        li 
          i.fas.fa-angle-right
          | Resultados de aprendizaje etapa práctica.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 4. Perfil de ingreso

    p 
      b Nivel académico: 
      | básica secundaria.
      br
      b Grado: 
      | 9. 
      br
      |Requiere certificación académica.
      br
      b Edad mínima definida por la ley: 
      | 14 años
      br
      b Requisitos adicionales: 
      | fase 2 obligatoria: superar prueba actitudinal y de inglés en A.
      br
      b Restricciones de ingreso soportadas en la legislación vigente:
      ul.lista-ul.ps-5
        li 
          i.fas.fa-angle-right
          | Personas con discapacidad visual o motora. 
        li 
          i.fas.fa-angle-right
          | Discapacidad cognitiva alta.
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 5. Perfil de egreso 
    p El egresado de este programa tendrá la capacidad de prestar el servicio de reservas, recepción y manejo de valores en caja, en idiomas español e inglés, de manera oportuna, manteniendo buenas relaciones interpersonales, trabajo en equipo y resolución de conflictos, contribuyendo así al cumplimiento de los estándares de calidad según las políticas del establecimiento. 


  //- Créditos
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 Créditos

    
    .creditos
      div(
        v-for="(creditoKey, index) of Object.keys(creditosData)"
        :class="index != Object.keys(creditosData).length -1 ? 'mb-4' : ''" 
      )
        .creditos__titulo {{configTitulos[creditoKey]}}
        table
          tbody
            tr(
              v-for="(item, idx) of creditosData[creditoKey]" 
              :key="creditoKey+idx"
            )
              td.text-bold(colspan='2' v-html="renderText(item.nombre)")
              td(colspan='2' v-html="renderText(item.cargo)")
              td(colspan='3' v-html="renderText(item.centro)")

  Footer

</template>
<script>
export default {
  name: 'Inicio',
  data: () => ({
    configTitulos: {
      liderEquipo: 'ECOSISTEMA DE RECURSOS EDUCATIVOS DIGITALES',
      contenidoInstruccional: 'CONTENIDO INSTRUCCIONAL',
      desarrolloProducto:
        'DISEÑO Y DESARROLLO DE RECURSOS EDUCATIVOS DIGITALES',
      gestoresRepositorio: 'GESTORES DE REPOSITORIO',
    },
  }),
  computed: {
    creditosData() {
      return this.$config.creditos
    },
  },
  methods: {
    renderText(textObj) {
      let newText = ''
      if (Array.isArray(textObj)) {
        textObj.forEach((texto, index) => {
          newText += (index ? '<br/>' : '') + texto
        })
      } else {
        newText += textObj
      }
      return newText
    },
  },
}
</script>

<style lang="sass">
.creditos
  td, th
    border-color: $color-sistema-c
</style>
