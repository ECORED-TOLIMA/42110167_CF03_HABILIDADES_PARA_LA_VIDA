<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 La agencia y la producción de transformaciones sociales
    
    p.mb-4 Las personas enfrentan diferentes situaciones y desafíos en los entornos donde participan. Frente a estas situaciones, cada persona puede tomar decisiones, construir relaciones y desarrollar acciones orientadas a transformar aspectos de su vida cotidiana y de los contextos donde interactúa.
    
    .row.justify-content-center.mb-4
      .col-lg-4.col-md-6.col-sm-8.mb-lg-0.mb-4(data-aos="zoom-in")
        img(src='@/assets/curso/temas/tema2/img01.png', alt='')
      .col-lg-6
        p La agencia se relaciona con la capacidad que tienen las personas y las comunidades para actuar de manera consciente, participar en diferentes espacios y aportar a la construcción de cambios orientados al bienestar propio y colectivo. Esta capacidad implica reconocer habilidades, tomar decisiones, afrontar situaciones y fortalecer formas de participación en los entornos familiares, sociales, educativos, laborales y comunitarios.
        p El fortalecimiento de competencias socioemocionales contribuye al desarrollo de esta capacidad de actuar, ya que permite fortalecer habilidades para la toma de decisiones, el liderazgo, la comunicación, el trabajo en equipo, la resolución de conflictos y la participación en diferentes espacios de la vida cotidiana.

    .row.justify-content-center.mb-4
      .col.col-lg-10.col-12
        .cajon.cajon.C02.color-secundario.px-4.py-3.mb-4
          p.mb-0 La agencia se relaciona con la capacidad que tienen las personas para tomar decisiones, actuar y desarrollar acciones orientadas a aquello que consideran importante para su bienestar y su proyecto de vida.

        p Esta capacidad puede fortalecerse a través del reconocimiento de las propias habilidades, la participación en diferentes espacios y el desarrollo de competencias socioemocionales que favorezcan la toma de decisiones, la participación y la construcción de cambios positivos en los diferentes contextos.

    .titulo-sexto.color-acento-contenido.offset-1(data-aos="zoom-in")
      h5 Figura 3.
      span  #[i Tipos de agencia     ]
    
    .row.justify-content-center.mb-4
      .col-md-10.desktop(data-aos="zoom-in")
        figure
          img(src='@/assets/curso/temas/tema2/img02-1.svg', alt='En la figura 3 se presentan los tipos de agencia según Mora y Oliveira (2014). La agencia adaptativa se centra en la subsistencia del joven, mientras que la agencia proyectiva implica la capacidad del joven para establecer planes y metas.')
          figcaption Nota. Adaptado de Mora & Oliveira (2014, p. 94)
      .col-md-6.movil(data-aos="zoom-in")
        figure
          img(src='@/assets/curso/temas/tema2/img02-2.svg', alt='En la figura 3 se presentan los tipos de agencia según Mora y Oliveira (2014). La agencia adaptativa se centra en la subsistencia del joven, mientras que la agencia proyectiva implica la capacidad del joven para establecer planes y metas.')
          figcaption Nota. Adaptado de Mora & Oliveira (2014, p. 94)

    .row.justify-content-center.mb-4
      .col.col-lg-8.col-12
        p Según la anterior figura y como señala Berger (2008), citado por Mora & Oliveira (2014), existen dos tipos de agencia:

        .row.mb-4
          .col-md-4.col-lg.mb-5.mb-lg-0
            .tarjeta-avatar
              img(src='@/assets/curso/temas/tema2/img03.svg' alt='')
              //- .tarjeta debe ir acompañado de una de una de estas clases => 
              //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
              //- estas clases tambien tienen un modificador --borde
              .tarjeta.color-secundario
                .p-4
                  h4.text-center Agencia adaptativa
                  p.mb-0 En la que las personas se enfocan en el presente y subsisten con los recursos inmediatos disponibles.

          .col-md-4.col-lg.mb-5.mb-lg-0
            .tarjeta-avatar
              img(src='@/assets/curso/temas/tema2/img04.svg' alt='')
              .tarjeta.color-secundario
                .p-4
                  h4.text-center Agencia proyectiva
                  p.mb-0 En la que, dependiendo de los recursos accesibles, las personas elaboran planes y se fijan metas a largo plazo.

    .row.justify-content-center
      .col.col-lg-10.col-12
        .cajon.cajon.C01.p-4(style="border-radius:20px !important")
          p.mb-0 La capacidad de agencia desde la ciudadanía impulsa cambios sociales al abordar problemas específicos dentro de las comunidades, siempre con la participación de sus miembros. Esto parte de una reflexión crítica y la construcción de conocimiento basada en las necesidades colectivas, desarrollando habilidades clave para la transformación social (Arnal citado por Alvarado & García, 2008).

    Separador

    #t_2_1.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 2.1. La agencia y la capacidad de actuar en los diferentes contextos

    p.mb-4 La agencia se relaciona con la capacidad que tienen las personas para tomar decisiones, actuar y participar de manera consciente en los diferentes espacios donde interactúan. Esta capacidad permite reconocer necesidades, identificar oportunidades y desarrollar acciones orientadas a afrontar situaciones que afectan el bienestar personal o colectivo.

    .bloque-texto-g.bloque-texto-g--inverso.color-primario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema2/img05.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Las personas ejercen agencia cuando participan activamente en la búsqueda de soluciones, toman decisiones frente a situaciones de la vida cotidiana o desarrollan acciones que contribuyen al bienestar propio y al de otras personas. Esta capacidad no depende únicamente de los recursos materiales o de las condiciones del entorno, sino también del reconocimiento de las propias capacidades, de la confianza en sí mismo y de las habilidades para relacionarse y actuar junto con otros.

    .row.justify-content-center.mb-4
      .col.col-lg-10.col-12
        p Los entornos familiares, educativos, laborales, sociales y comunitarios influyen en la manera en que las personas desarrollan su capacidad de actuar y participar. En algunos contextos pueden existir barreras que dificultan la participación o limitan las oportunidades de desarrollo; sin embargo, también existen espacios, relaciones y redes de apoyo que permiten fortalecer capacidades y promover acciones orientadas a generar cambios positivos.
    
    .row.justify-content-center.align-items-center
      .col-lg-10
        .cajon.color-secundario.p-4.mb-4
          .row.justify-content-center
            .col-lg-2.col-md-6.col-sm-8.mb-lg-0.mb-4(data-aos="zoom-in")
              figure
                img(src='@/assets/curso/temas/tema2/img06.svg', alt='')
            .col-lg-10(data-aos="fade-left")
              p.mb-0 En este proceso, las competencias socioemocionales cumplen un papel importante, ya que fortalecen habilidades para la toma de decisiones, la comunicación, la empatía, la resiliencia, el liderazgo y el trabajo en equipo. Estas capacidades permiten afrontar situaciones de manera más consciente, participar en diferentes espacios y construir relaciones orientadas a la convivencia y el trabajo con otras personas.

    .row.justify-content-center
      .col.col-lg-10.col-12
        p Reconocer la capacidad de actuar y participar en los diferentes contextos permite comprender que las personas no son únicamente receptoras de situaciones o decisiones externas, sino que también pueden aportar, proponer acciones y contribuir a la construcción de cambios positivos en sus entornos desde sus experiencias, capacidades y formas de relacionarse con los demás.

    Separador

    #t_2_2.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 2.2. Participación, liderazgo y transformación social

    p.mb-4 La participación y el liderazgo cumplen un papel importante en la construcción de cambios orientados al bienestar individual y colectivo. A través de la interacción en diferentes espacios familiares, educativos, laborales, sociales y comunitarios, las personas pueden expresar sus ideas, construir acuerdos, proponer soluciones y aportar al fortalecimiento de la convivencia y el tejido social.

    .row.justify-content-center
      .col-lg-10
        .box___style_2(data-aos="zoom-in").mb-4
          .row.align-items-center
            .col-xl-auto.d-none.d-lg-block
              figure
                img(src='@/assets/curso/temas/tema2/img07.svg', alt='').m-auto
            .col-xl.fit___box_container
              p El liderazgo no se relaciona únicamente con dirigir grupos o asumir cargos de representación. También implica la capacidad de motivar, trabajar con otras personas, promover el diálogo y desarrollar acciones orientadas a la construcción de relaciones más respetuosas, solidarias y participativas. En este sentido, el liderazgo puede manifestarse en diferentes situaciones de la vida cotidiana, mediante acciones que contribuyan al bienestar propio y al de las comunidades.
              p.mb-0 La participación activa y el liderazgo se fortalecen a través del desarrollo de competencias socioemocionales como la comunicación, la empatía, la regulación emocional, la resiliencia y el trabajo en equipo. Estas capacidades favorecen la construcción de relaciones colaborativas, la resolución de conflictos y la capacidad de actuar frente a situaciones que afectan la convivencia o el bienestar colectivo.

    .row.justify-content-center
      .col.col-lg-10.col-12
        p La participación y el trabajo conjunto entre personas y comunidades permiten fortalecer la convivencia, construir acuerdos y generar acciones orientadas al bienestar colectivo. Escuchar diferentes perspectivas, dialogar, apoyar iniciativas colectivas o promover relaciones basadas en el respeto y la solidaridad son acciones que pueden generar cambios positivos en los diferentes entornos donde las personas interactúan.

        .cajon.cajon.C02.color-secundario.px-4.py-3.mb-4
          p.mb-0 Por esta razón, fortalecer capacidades para la participación y el liderazgo contribuye no solo al desarrollo personal, sino también a la construcción de entornos más democráticos, incluyentes y orientados al fortalecimiento del bienestar colectivo y la convivencia.

    Separador

    #t_2_3.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 2.3. Las competencias socioemocionales y la construcción de cambios en el entorno
    
    p.mb-4 Las competencias socioemocionales permiten a las personas afrontar de manera más consciente las situaciones que se presentan en su vida cotidiana y contribuir a la construcción de cambios orientados al bienestar individual y colectivo. Estas capacidades fortalecen la manera en que las personas se relacionan, toman decisiones, resuelven conflictos y participan en diferentes espacios sociales y comunitarios.

    .row.justify-content-center
      .col.col-lg-10.col-12
        figure.mb-4
          img(src='@/assets/curso/temas/tema2/img08.png', alt='')

        p El desarrollo de habilidades como la empatía, la comunicación, la regulación emocional, la resiliencia, el liderazgo y el trabajo en equipo favorece la construcción de relaciones más positivas y la capacidad de actuar frente a situaciones que afectan la convivencia o limitan las oportunidades de participación y desarrollo. Así mismo, estas competencias permiten reconocer diferentes perspectivas, construir acuerdos y fortalecer la participación en acciones individuales y colectivas.
    
    .row.justify-content-center.mb-4
      .col-lg-10.col-12
        .recurso-transformacion.p-4
          .row
            .col-lg-3.col-md-4.col-12.mb-4.mb-md-0.d-none.d-lg-block
              figure.mb-0
                img(src='@/assets/curso/temas/tema2/img09.png', alt='')

            .col-lg-9.col-md-8.col-12
              .recurso-transformacion__contenido
                figure.mb-3
                  img(src='@/assets/curso/temas/tema2/img010.svg', alt='')

                p.mb-0 Las transformaciones sociales no siempre ocurren a través de grandes acciones o cambios inmediatos. También se construyen desde las decisiones, relaciones y acciones cotidianas que las personas desarrollan en sus diferentes contextos. Participar en espacios comunitarios, apoyar iniciativas colectivas, promover relaciones respetuosas o contribuir a la solución de situaciones que afectan a otras personas son ejemplos de acciones que pueden generar impactos positivos en los entornos donde se participa.
    
    .row.justify-content-center
      .col.col-lg-10.col-12
        p En este proceso, la agencia y las competencias socioemocionales se relacionan de manera permanente, ya que fortalecen la capacidad de las personas para actuar, participar y contribuir a la construcción de cambios desde sus experiencias, capacidades y formas de relacionarse con los demás.
        p Reconocer que las acciones individuales y colectivas pueden generar transformaciones en los entornos permite fortalecer el sentido de participación, corresponsabilidad y construcción colectiva, aportando al fortalecimiento de comunidades orientadas a la convivencia, la participación y el bienestar colectivo.
    
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
