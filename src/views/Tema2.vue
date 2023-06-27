<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Pruebas de vulnerabilidad cibernética
    .bg1
      .row.mb-5.justify-content-center.align-items-center(data-aos="fade-left")

        .col-lg-4
          figure.mb-4.mb-lg-0
            img.img-t(src='@/assets/curso/tema2/img1.png', style="width: 400px" alt="").m-auto
        .col-lg-8
          .col-lg-12
          p Las empresas se enfrentan a una amplia gama de amenazas de ciberseguridad al volverse más dependientes de internet, el acceso remoto y la tecnología en general. #[span.txt-c1 Para mantener seguros sus datos y aplicaciones esenciales, deben identificar las vulnerabilidades potenciales que los ciberdelincuentes podrían explotar en nombre de sus objetivos.]
          .row
            .col-12.p-4.bg2.mb-3
              .row.align-items-center
                .col
                  p.mb-0 Mediante el uso de una combinación de herramientas de prueba de vulnerabilidades y técnicas de escaneo, los expertos en seguridad cibernética pueden ayudarlos a identificar y reforzar las brechas y debilidades de seguridad.
                .col-lg-auto
                  figure
                    img(src='@/assets/curso/tema2/img2.svg', style="width: 60px" alt="").m-auto

    .row.align-items-center.mb-0.mb-lg-4
      .col-lg-6
        .bg8.p-4
          .row.align-items-center
            .col-lg-2
              img.img-t.m-auto(src='@/assets/curso/tema2/img3.svg', alt='')
            .col-lg-10.p-3
              h4.text-white ¡Importante!
              p.m-0.text-white.pe-3 Es una práctica común que los entornos de desarrollo y prueba para los sistemas de aplicaciones comerciales, la mayoría de las veces también contengan datos confidenciales del cliente, que se utilizan para desarrollar, simular y probar la lógica del código de la aplicación.
      .col-lg-6
        .bg9.p-4
          .row.align-items-center
            .col-lg-2
              img.img-t.m-auto(src='@/assets/curso/tema2/img3.svg', alt='')
            .col-lg-10.p-0-.p-lg-5
              h4.text-white ¡Atención!
              p.m-0.text-white Esto implica que estos entornos de prueba, que no son de producción, también deban protegerse de la misma manera que el entorno de TI de producción.
    Separador
    #t_2_1
    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.1 Finalidad de las pruebas
    .bg1
      .row.mb-5.justify-content-center.align-items-center(data-aos="fade-left")
        .col-lg-4.mb-3
          figure
            img.img-t(src='@/assets/curso/tema2/img6.png', style="width: 350px"  alt="").m-auto
        .col-lg-8
          .col-lg-12
          p El enfoque de las pruebas de efectividad, frente a la metodología, es #[span.txt-c1 comprobar o medir la eficiencia de la ejecución del modelo de seguridad en organizaciones]. Con el fin de ayudar a las organizaciones se han desarrollado metodologías que favorecen la comprensión y el desarrollo de las pruebas, el alcance de objetivos y el beneficio que se gana al identificar sus etapas y gestionarlas.

          .row
            .col-12.p-4.bg6.mb-3
              .row.align-items-center
                .col
                  p.mb-0 Tales metodologías se desarrollan en diferentes etapas, ayudando a definir qué tanto ha avanzado la organización con la implementación del modelo. Así pues, por medio de la valoración de diferentes aspectos, se podrán identificar también vulnerabilidades y amenazas, a las cuales está expuesta la organización, de igual manera que las debilidades de los controles implementados.
                .col-lg-auto
                  figure
                    img(src='@/assets/curso/tema2/img7.svg', style="width: 60px"  alt="").m-auto
    p.mb-5 A continuación, explore el recurso didáctico con el que le #[span.txt-c1  presentamos las etapas del procedimiento de las pruebas], según lo estipulado por la Guía metodológica de pruebas de efectividad, del MINTIC:
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/SZD5lnzXAtI" title="Finalidad de las pruebas" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video. Finalidad de las pruebas

    Separador
    #t_2_2
    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.2 Pruebas y análisis
    .bg1
      .row.mb-5.justify-content-center.align-items-center(data-aos="fade-left")
        .col-lg-4.mb-3
          figure
            img.img-t(src='@/assets/curso/tema2/img8.png', style="width: 350px"  alt="").m-auto
        .col-lg-8
          .col-lg-12
          p Mediante las pruebas y análisis, las entidades identifican los diferentes riesgos que se muestran por las debilidades en la implementación del modelo de seguridad y de privacidad de la información y las vulnerabilidades que se manifiestan dada la ausencia de controles de seguridad que logren mitigar riesgos.
          .row
            .col-12.p-4.bg6.mb-3
              .row.align-items-center
                .col
                  p.mb-0 #[span.txt-c1 Este tipo de pruebas están orientadas a la evaluación de la estructura de seguridad de la organización; para ello, las organizaciones han de revisar diferentes frentes de trabajo como, por ejemplo, el Anexo A de la ISO 27001:2013], el ciclo de vida de la seguridad (PHVA), el nivel y estado de madurez de la organización en correspondencia con los niveles expuestos en el modelo de seguridad y privacidad y las recomendaciones para que la organización logre plasmar el concepto de Ciberseguridad.
    Separador
    #t_2_3
    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.3 Tipos de pruebas de efectividad
    .bg10
      .row.mb-3
        .col-lg-11
          p Respecto de los tipos de pruebas de efectividad, se pueden realizar tres tipos, basados en el nivel de conocimiento del entorno o de la infraestructura de la organización objetivo.
        .col-lg-1
          .row.justify-content-center
            .col-auto
              figure(data-aos="fade-down-right")
                img.img-t.m-auto(src='@/assets/curso/tema2/img9.svg', alt='')
    p.mb-4 <b>#[span.txt-c1 Estos tres tipos de prueba son:]</b>

    .row.justify-content-center.mb-5
      .col-11.col-lg.p-4.p-lg-4.bg_color2.m-2
        figure.mb-3
          img.imgtar(src='@/assets/curso/tema2/img11.png', alt='')
        h4.mb-3 Pruebas con conocimiento nulo del entorno
        p.mb-0 Se trata del tipo de prueba en la que simulará a un atacante real, ya que se basa en que cuenta con muy poco conocimiento o quizá nulo conocimiento del objetivo o su infraestructura.
      .col-11.col-lg.p-4.p-lg-4.bg_color2.m-2
        figure.mb-3
          img.imgtar(src='@/assets/curso/tema2/img12.png', alt='')
        h4.mb-3 Pruebas con conocimiento medio del entorno
        p.mb-0 Se refiere a cuando, para la prueba de #[em pentesting], se cuenta con más información sobre aquel ambiente que será atacado, es decir, direcciones IP, sistemas operativos, arquitectura de red etc. De igual manera es información limitada o media. Esto emula a alguna persona dentro de la red con conocimiento básico de la misma.
      .col-11.col-lg.p-4.p-lg-4.bg_color2.m-2
        figure.mb-3
          img.imgtar(src='@/assets/curso/tema2/img13.png', , alt='')
        h4.mb-3 Pruebas con conocimiento completo del entorno
        p.mb-0 Son pruebas en donde el hacker cuenta con toda la información disponible y relacionada con el sistema objetivo del ataque. Por lo general, son para asuntos de auditoría.
        Separador
    #t_2_4
    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.4 Procedimiento de ejecución de pruebas de efectividad
    .bg11
      .row.mb-5
        .col-lg-1
          .row.justify-content-center
            .col-auto
              figure(data-aos="fade-down-right")
                img.img-t.m-auto(src='@/assets/curso/tema2/img14.svg', alt='').my-4.my-lg-0
        .col-lg-11
          p Las pruebas de efectividad pueden realizarse por medio de las siguientes acciones de manera secuencial: contextualización, reconocimiento del objetivo, modelado de amenazas, evaluación de vulnerabilidades, explotación, postexplotación y reporte.
          p #[span.txt-c1 A continuación, se especifican las acciones con las que se aplican las pruebas de efectividad; comprenda los aspectos importantes de cada una de ellas y lleve registro en su libreta personal de apuntes:]

    .bg12.p-5.mb-5
      .row.align-items-center(data-aos="fade-left")
        .col-lg-4
          figure
            img.img-t(src='@/assets/curso/tema2/img16.svg', style="width: 400px"  alt="").m-auto
        .col-lg-8
          SlyderF(columnas="col-lg-6 col-xl-6")
            .tarjeta.bg13.p-4.pt-5
              .row.align-items-center
                .col-auto.mb-4
                  figure
                    img.img-t.m-auto(src='@/assets/curso/tema2/img24.svg'  alt="")
                .col-lg-9
                  h4 Contextualización
              p Esta acción se basa en identificar los alcances reales de las pruebas y de los procedimientos a ejecutar con base a las necesidades identificadas.
            .tarjeta.bg13.p-4.pt-5
              .row.align-items-center
                .col-auto.mb-4
                  figure
                    img.img-t.m-auto(src='@/assets/curso/tema2/img18.svg'  alt="")
                .col-lg-9
                  h4 Reconocimiento de objetivo
              p Esta acción, busca obtener tanta información del objetivo como sea posible para poder ser empleada en la acción de evaluación de vulnerabilidades y la acción de explotación.
            .tarjeta.bg13.p-4.pt-5
              .row.align-items-center
                .col-auto.mb-4
                  figure
                    img.img-t.m-auto(src='@/assets/curso/tema2/img19.svg'  alt="")
                .col-lg-9
                  h4 Modelado de amenazas
              p Esta acción establece la relación entre el atacante y el activo intentando definir el beneficio que puede alcanzar el atacante si logra penetrar el sistema y afectar la información de alguna manera.
            .tarjeta.bg13.p-4.pt-5
              .row.align-items-center
                .col-auto.mb-4
                  figure
                    img.img-t.m-auto(src='@/assets/curso/tema2/img20.svg'  alt="")
                .col-lg-9
                  h4 Evaluación de vulnerabilidades
              p Es la acción que descubre falencias en los sistemas y aplicaciones, que pueden llegar a ser aprovechados por un atacante.
            .tarjeta.bg13.p-4.pt-5
              .row.align-items-center
                .col-auto.mb-4
                  figure
                    img.img-t.m-auto(src='@/assets/curso/tema2/img21.svg'  alt="")
                .col-lg-9
                  h4 Explotación
              p Es la acción que busca, concretamente, acceder al sistema, apalancando las debilidades identificadas en la etapa anterior o sobrepasando los controles de seguridad existentes.
            .tarjeta.bg13.p-4.pt-5
              .row.align-items-center
                .col-auto.mb-4
                  figure
                    img.img-t.m-auto(src='@/assets/curso/tema2/img22.svg'  alt="")
                .col-lg-9
                  h4 Postexplotación
              p Acción que busca identificar el tipo de información que se puede obtener, a qué otros sistemas de información se puede ingresar desde el sistema capturado, las opciones de configuración, información de red, todo esto con el objetivo principal de determinar el valor de la máquina para la organización.
            .tarjeta.bg13.p-4.pt-5
              .row.align-items-center
                .col-auto.mb-4
                  figure
                    img.img-t.m-auto(src='@/assets/curso/tema2/img22.svg'  alt="")
                .col-lg-9
                  h4 Reporte
              p Acción con la que se documentan resultados obtenidos en cada anterior acción.
    .row.align-items-center.mb-0.mb-lg-4
      .col-lg-6
        .bg14.p-4
          .row.align-items-center
            .col-lg-12
              p.m-0 De la aplicación procedente, responsable y oportuna de las pruebas, depende en gran medida su efectividad y su potencial aprovechamiento. Las pruebas de efectividad han de realizarse con las acciones mencionadas, siendo cada una de estas, una acción vinculada consecuentemente con las anteriores o con las posteriores.
      .col-lg-6
        .bg8.p-4
          .row.justify-content-around.align-items-center
            .col
              .row.align-items-center
                .col.mb-3.mb-sm-0.pt-2
                  p.m-0.text-white Para ahondar en los aspectos importantes relacionados con pruebas de efectividad y su procedimiento, le recomendamos estudiar la Guía No 1. Guía metodológica de pruebas de efectividad del MinTIC.
                .col-sm-auto.d-flex.align-items-center
                  a.boton.color-acento-botones.me-3.mg4(href="https://www.mintic.gov.co/gestionti/615/articles-5482_G1_Metodologia_pruebas_efectividad.pdf" target="_blank")
                    span Enlace web
                    i.fas.fa-link

    Separador
    #t_2_5
    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.5 Alcance de las pruebas
    .bg10
      .row.mb-3
        .col-lg-11
          p Deberán existir una serie de reglas y otros elementos importantes para la aplicación de las pruebas de efectividad técnicas, con el fin de asegurar que tales actividades no lleguen a incurrir en fallas mayores y que, también, sea posible la afectación de la infraestructura o de las distintas operaciones de la organización.
        .col-lg-1
          .row.justify-content-center
            .col-auto
              figure(data-aos="fade-down-right")
                img.img-t.m-auto(src='@/assets/curso/tema2/img26.svg', alt='')
    p.mb-4 <b>#[span.txt-c1 Dentro del alcance, es posible definir aspectos como los que se especifican en el recurso que se muestra a continuación:]</b>
    .row.justify-content-center
      .col-lg-12
        ImagenInfografica.d-none.d-sm-flex.color-acento-botones.mb-5
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/tema2/img27.svg',  alt="")(data-aos="fade-right")
          .tarjeta.color-cuarto1.p-3(x="28.5%" y="14.3%" numero="+")
            p <b>Plan de trabajo</b>
            p.mb-0 Implica definir la duración de tiempo para realización de las pruebas, los sistemas que van a hacer parte de las pruebas, las acciones y actividades específicas, los procedimientos de contingencia en caso de alguna afectación, etc.
          .tarjeta.color-cuarto1.p-3(x="17.9%" y="61.8%" numero="+")
            p <b>Insumos</b>
            p.mb-0 Recursos necesarios para realizar las actividades: personal adicional, ventanas de tiempo, equipos, entre otros.
          .tarjeta.color-cuarto1.p-3(x="40.5%" y="30.4%" numero="+")
            p <b>Responsables</b>
            p.mb-0 Serán los encargados de efectuar las pruebas (sean proveedores o funcionarios de la entidad).
          .tarjeta.color-cuarto1.p-3(x="65%" y="18.7%" numero="+")
            p <b>Afectaciones Posibles</b>
            p.mb-0 Tipo de afectación que puede llegar a darse sobre cada sistema, también debe definirse si el objetivo es realizarlo en horario de producción o en horario de baja actividad laboral.
          .tarjeta.color-cuarto1.p-3(x="77.2%" y="54.8%" numero="+")
            p <b>Multas o Sanciones</b>
            p.mb-0 En caso de incumplir los parámetros anteriormente mencionados, deberán fijarse las sanciones disciplinarias o multas.
    .row.justify-content-center
      .col-lg-6
        ImagenInfografica.d-flex.d-sm-none.color-acento-botones.mb-5
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/tema2/img28.svg',  alt="La imagen presenta algunos elementos importantes en la aplicación de las pruebas de efectividad técnica, como son: plan de trabajo, responsables, posibles afectaciones, insumos y multas o sanciones.")(data-aos="fade-right")
          .tarjeta.color-cuarto1.p-3(x="49.5%" y="15.5%" numero="+")
            p <b>Plan de trabajo</b>
            p.mb-0 Implicar definir la duración de tiempo para realización de las pruebas, los sistemas que van a hacer parte de las pruebas, las acciones y actividades específicas, los procedimientos de contingencia en caso de alguna afectación, etc.
          .tarjeta.color-cuarto1.p-3(x="49.9%" y="34.8%" numero="+")
            p <b>Insumos</b>
            p.mb-0 Recursos necesarios para realizar las actividades: personal adicional, ventanas de tiempo, equipos, entre otros.
          .tarjeta.color-cuarto1.p-3(x="49.6%" y="54.5%" numero="+")
            p <b>Responsables</b>
            p.mb-0 Serán los encargados de efectuar las pruebas (sean proveedores o funcionarios de la entidad).
          .tarjeta.color-cuarto1.p-3(x="50%" y="72.5%" numero="+")
            p <b>Afectaciones Posibles</b>
            p.mb-0 Tipo de afectación que puede llegar a darse sobre cada sistema, también debe definirse si el objetivo es realizarlo en horario de producción o en horario de baja actividad laboral.
          .tarjeta.color-cuarto1.p-3(x="50.2%" y="91.5%" numero="+")
            p <b>Multas o Sanciones</b>
            p.mb-0 En caso de incumplir los parámetros anteriormente mencionados, deberán fijarse las sanciones disciplinarias o multas.
    .row.bg9
      .col-1.px-0.d-flex.align-items-center
        figure
          img(src='@/assets/curso/tema1/img22.svg', style="width: 50px"  alt="").m-auto
      .col-11.p-3
        p.mb-3.text-white <b>¡Importante!</b>
        p.mb-3.text-white Estos alcances permitirán controlar internamente el desarrollo de las pruebas, así como manejar los acuerdos de servicio con terceros que pueden llegar a realizar estos procedimientos.
</template>

<script>
import SlyderF from '../components/SlyderF.vue'
export default {
  name: 'Tema2',
  components: { SlyderF },
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

<style lang="sass">
.slyder-f
  .slyder-f__main
    .horizontal-scroll__wrapper
      padding-top: 0rem !important
</style>
