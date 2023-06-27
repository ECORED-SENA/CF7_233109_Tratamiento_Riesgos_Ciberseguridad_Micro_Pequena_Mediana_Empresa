<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 La auditoría cibernética
    .bg1
      .row.mb-5.justify-content-center.align-items-center(data-aos="fade-left")#tema_1_0
        .col-lg-12
          p #[span.txt-c1 A medida que las organizaciones adoptan nuevas tecnologías digitales, aumenta el riesgo de ser objeto de ciberataques]. La mayor complejidad de la red que surge como resultado de la innovación digital, a menudo crea nuevas brechas en la red para que las exploten los ciberadversarios.
        .col-lg-4
          figure
            img.img-t(src='@/assets/curso/tema1/img1.png', style="width: 400px" alt="").m-auto
        .col-lg-8
          .row
            .col-12.p-4.bg2.mb-3
              .row.align-items-center
                .col
                  p.mb-0 Si no se controlan, estos riesgos pueden socavar los objetivos organizacionales, por lo que es fundamental que las empresas cuenten con programas efectivos de ciberseguridad.
                .col-lg-auto
                  figure
                    img(src='@/assets/curso/tema1/img2.svg', style="width: 60px" alt="").m-auto
          p Se debe tener presente que:
          SlyderF(columnas="col-lg-6 col-xl-6")
            .tarjeta-avatar
              img.img70(src='@/assets/curso/tema1/img7.svg'  alt="")
              .tarjeta.bg3
                .p-4
                  p.mb-0.text-white Un componente clave para el éxito de estos programas es la administración de auditorías de ciberseguridad.
            .tarjeta-avatar
              img(src='@/assets/curso/tema1/img8.svg'  alt="")
              .tarjeta.bg4
                .p-4
                  p.mb-0.text-white La administración periódica de auditorías de ciberseguridad ayuda a las organizaciones a identificar brechas en su infraestructura de ciberseguridad.
            .tarjeta-avatar
              img(src='@/assets/curso/tema1/img9.svg'  alt="")
              .tarjeta.bg3
                .p-4
                  pmb-0.text-white Las organizaciones también pueden utilizar las auditorías para evaluar su cumplimiento de diversas leyes y reglamentos.
            .tarjeta-avatar
              img(src='@/assets/curso/tema1/img10.svg'  alt="")
              .tarjeta.bg4
                .p-4
                  p.mb-0.text-white Con un programa de auditoría de seguridad cibernética establecido, las empresas pueden monitorear de manera efectiva su postura de seguridad a medida que sus redes crecen y se vuelven más complejas.
    Separador
    #t_1_1
    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.1 Técnicas de auditoría
    .row.justify-content-center.ps-3
      .col-lg-12
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-4
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema1/img6.png')})`}"
          )(data-aos="fade-right")
          .bloque-texto-g__texto.p-4(data-aos="fade-left")
            p.mb-0 Las auditorías son un #[span.txt-c1 “proceso sistemático, independiente y documentado para obtener evidencias y evaluarlas, de manera objetiva, con el fin de determinar el grado en que se cumplen los criterios de auditoría”] (ISO, 2018). Las auditorías se convierten en el proceso mediante el cual se valida y corrobora, con algún proceso de observación, indagación o verificación, si un criterio de evaluación se está cumpliendo, de acuerdo a los parámetros establecidos.
    Separador
    #t_1_2
    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.2 Tipos de auditoría
    .row.justify-content-center.mb-4
      .col-lg-2
        figure
          img.img-t.m-auto.img_position(src='@/assets/curso/tema1/img11.svg' alt="")
      .col-lg-10
        .bg5.p-4.pt-5
          .row.justify-content-center
            .col-lg-9.pt-lg-3.pt-0
              p De acuerdo al momento en que se realiza la auditoría, del alcance de la misma y del auditor que la realiza, estas se pueden clasificar en 3 tipos: de primera parte, de segunda parte o de tercera parte.

    br

    .titulo-sexto.color-acento-contenido(data-aos="fade-right").my-4
      h5 Tabla 1.
      span Tipos de auditoría

    .row.justify-content-center
      .col-lg-12
        .tabla-a.color-primario.mb-5
          table
            caption  Nota: tomado de ISO, 2018.
            thead
              tr.bg_color1
                td.h4.text-center(colspan="4") Auditoría de primera parte
                td.h4.text-center(colspan="4") Auditoría de segunda parte
                td.h4.text-center(colspan="4") Auditoría de tercera parte
            tbody
              tr

                td.text-center(colspan="4") Auditoría interna
                td.text-center(colspan="4") Auditoría externa de proveedor.
                td.text-center(colspan="4") Auditoría de certificación y/o Acreditación.
              tr
                td(colspan="4")
                td.text-center(colspan="4") Otra auditoría externa de parte interesada.
                td.text-center(colspan="4") Auditoría legal, reglamentaria o similar.
    p.mb-5 Pero, #[span.txt-c1 ¿cuáles son las especificidades de cada tipo de auditoría?] Aquí se los presentamos; explore el recurso que se muestra enseguida y descúbralo; le sugerimos tomar nota de ello en su libreta personal de apuntes. #[span.txt-c1 ¡Adelante!]

    .row.justify-content-center
      .col-lg-12
        ImagenInfografica.d-none.d-sm-flex.color-acento-botones.mb-5
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/tema1/img13.svg',  alt="Esta infografía presenta las especificidades de cada tipo de auditoría.")(data-aos="fade-right")
          .tarjeta.color-cuarto.p-3(x="50%" y="16.6%" numero="+")
            p <b>Los tipos de auditoría</b>
            p.mb-0 Las auditorías son de un tipo o de otro, según el momento en que se realiza, según el alcance que esta tiene y según el auditor que la realiza.
          .tarjeta.color-cuarto.p-3(x="72.9%" y="40.8%" numero="+")
            p <b>Auditoría de tercera parte</b>
            p.mb-0 Son las auditorías realizadas por partes externas con fines de certificación y/o acreditación, aunque también se pueden dar para verificación de cumplimiento legal, reglamentario entre otras.
          .tarjeta.color-cuarto.p-3(x="77.2%" y="70.6%" numero="+")
            p <b>Enfoque en su organización</b>
            p.mb-0 En este componente formativo, se enfocará la mirada hacia las <b>auditorías de primera parte o auditorías internas</b>, ya que la demás auditorías son realizadas por terceros. Con este énfasis, usted se fortalecerá en la identificación de aspectos clave del proceso de evaluación de estrategias de seguridad para su propia organización.
          .tarjeta.color-cuarto.p-3(x="22.5%" y="70.6%" numero="+")
            p <b>Auditoría de primera parte</b>
            p.mb-0 Estas son realizadas por la misma organización o también llamadas #[strong Auditorías Internas]. Buscan verificar que se estén aplicando y cumpliendo los requisitos establecidos en la estrategia de seguridad.
          .tarjeta.color-cuarto.p-3(x="27%" y="40.8%" numero="+")
            p <b>Auditoría de segunda parte</b>
            p.mb-0 Se denominan también auditorías externas; este tipo de auditoría externa es la que evalúa que se estén cumpliendo los requisitos con los proveedores, en relación al cumplimiento de la estrategia de seguridad.
    .row.justify-content-center
      .col-lg-6
        ImagenInfografica.d-flex.d-sm-none.color-acento-botones.mb-5
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/tema1/img14.svg',  alt="")(data-aos="fade-right")
          .tarjeta.color-cuarto.p-3(x="50%" y="53.6%" numero="+")
            p <b>Los tipos de auditoría</b>
            p.mb-0 Las auditorías son de un tipo o de otro, según el momento en que se realiza, según el alcance que esta tiene y según el auditor que la realiza.
          .tarjeta.color-cuarto.p-3(x="50.6%" y="73%" numero="+")
            p <b>Auditoría de tercera parte</b>
            p.mb-0 Son las auditorías realizadas por partes externas con fines de certificación o acreditación, aunque también se pueden dar para verificación de cumplimiento legal, reglamentario entre otras.
          .tarjeta.color-cuarto.p-3(x="50.4%" y="92.8%" numero="+")
            p <b>Enfoque en su organización</b>
            p.mb-0 En este componente formativo, se enfocará la mirada hacia las <b>auditorías de primera parte o auditorías internas</b>, ya que la demás auditorías son realizadas por terceros. Con este énfasis, usted se fortalecerá en la identificación de aspectos clave del proceso de evaluación de estrategias de seguridad para su propia organización.
          .tarjeta.color-cuarto.p-3(x="49.5%" y="15.6%" numero="+")
            p <b>Auditoría de primera parte</b>
            p.mb-0 Estas son realizadas por la misma organización o también llamadas Auditorías Internas. buscan verificar que se estén aplicando y cumpliendo los requisitos establecidos en la estrategia de seguridad.
          .tarjeta.color-cuarto.p-3(x="50%" y="33.8%" numero="+")
            p <b>Auditoría de segunda parte</b>
            p.mb-0 Se denominan también auditorías externas; este tipo de auditoría externa es la que evalúa que se estén cumpliendo los requisitos con los proveedores, en relación al cumplimiento de la estrategia de seguridad.

    Separador
    #t_1_3
    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.3 Definiciones y elementos fundamentales de la auditoría
    .row.mb-5.justify-content-center.align-items-center(data-aos="fade-left")
      .col-lg-8
        .row
          .col-12.p-4.bg2.mb-2
            .row.align-items-center
              .col
                p.mb-0 Para establecer o entender un ejercicio de auditoría es necesario referirse a la norma GTC-ISO 19011:2018, la cual establece las directrices para la auditoría de los sistemas de gestión.
              .col-lg-auto
                figure
                  img(src='@/assets/curso/tema1/img16.svg', style="width: 60px" alt="").m-auto
        p Entérese de algunas definiciones y lineamientos que da la norma y que aseguran que el proceso de evaluación y auditoría del sistema de gestión de seguridad de información, en las organizaciones, sea efectivo:

      .col-lg-4
        figure
          img.img-t(src='@/assets/curso/tema1/img15.png', style="width: 320px" alt="").m-auto
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/_XH1XmhtXIk" title="Definiciones y elementos fundamentales de la auditoría" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video. Definiciones y elementos fundamentales de la auditoría

    Separador
    #t_1_4
    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.4 Consideraciones importantes para una auditoría
    .row.mb-5.justify-content-center.align-items-center(data-aos="fade-left")
      .col-lg-4
        figure
          img.img-t(src='@/assets/curso/tema1/img18.png', style="width: 320px" alt="").m-auto
      .col-lg-8
        .row
          .col-12.p-4.bg6.mb-2
            .row.align-items-center
              .col
                p.mb-0 De acuerdo a la norma GTC-ISO 19011:2018, una auditoría de sistemas de gestión se debe establecer bajo ciertas condiciones que permitan la construcción y desarrollo de la misma, en la organización.
              .col-lg-auto
                figure
                  img(src='@/assets/curso/tema1/img19.svg', style="width: 60px" alt="").m-auto
        p Le invitamos a revisar con especial atención las consideraciones, sobre la auditoría, contenidas en el siguiente video.
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/NUL5Hc5nbYA" title="Consideraciones importantes para la auditoría" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video. Consideraciones importantes para la auditoría

    Separador
    #t_1_5
    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.5 Principios de la auditoría
    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-right")
      .col-lg-12
        .dual-txt-deco
          p(style="position: relative; z-index: 1;") Entiéndase como principios de auditoría a los elementos y aspectos fundamentales, para desarrollar un ejercicio de auditoría y obtener resultados confiables, objetivos, pertinentes y suficientes para que la organización tome las decisiones apropiadas en el futuro.
    .row.align-items-center.mb-5
      .col-lg-8(data-aos="fade-right").mb-4
        p Adicional de las técnicas, tipos, definiciones y consideraciones, relacionadas con el proceso de auditoría, #[span.txt-c1 hay que tener en cuenta que toda acción en pos de la auditoría, ha de estar orientada por estos principios.] Conózcalos a continuación:
        LineaTiempoD.color-acento-contenido.mb-5
          .row(numero="1" titulo="Integridad").p-3
            .col-md-8.mb-4.mb-md-0
              p El auditor debe realizar el ejercicio a partir de su honestidad, imparcialidad, diligencia y responsabilidad, durante toda la auditoría.

          .row(numero="2" titulo="Presentación ecuánime").p-3
            .col-md-8.mb-4.mb-md-0
              p Los resultados de la auditoría deben reflejar la veracidad y exactitud de la información que se pudo evaluar durante la auditoría.

          .row(numero="3" titulo="Debido cuidado profesional").p-3
            .col-md-8.mb-4.mb-md-0
              p El auditor debe tener la capacidad de formular juicios de valor razonables durante toda la auditoría.

          .row(numero="4" titulo="Confidencialidad").p-3
            .col-md-8.mb-4.mb-md-0
              p La seguridad de la información, durante el ejercicio de la auditoría, es un factor de sumo cuidado. Se debe garantizar que la información, su uso y protección, serán aplicados de manera apropiada.

          .row(numero="5" titulo="Independencia").p-3
            .col-md-8.mb-4.mb-md-0
              p El auditor se debe considerar y sentir independiente y libre de sesgo y conflicto de intereses, durante todo el ejercicio de la auditoría, lo cual permite realizar una evaluación objetiva.

          .row(numero="6" titulo="Enfoque basado en la evidencia").p-3
            .col-md-12.mb-4.mb-md-0
              p Los criterios evaluados deben contar con la presentación y verificación de las evidencias correspondientes, lo cual da fe del ejercicio de auditoría dando fiabilidad a esta.

      .col-lg-4
        figure.d-flex.justify-content-center
          img.img-t.mx-auto(src='@/assets/curso/tema1/img20.png',  alt="")
    .row.bg7
      .col-1.px-0.d-flex.align-items-center
        figure
          img(src='@/assets/curso/tema1/img22.svg', style="width: 50px" alt="").m-auto
      .col-11.p-3
        p.mb-3.text-white <b>¡Importante!</b>
        p.mb-3.text-white Con los anteriores principios, se busca objetividad, confianza y contar con un insumo para identificar el rendimiento de la estrategia de seguridad de la información y poder tomar decisiones.
    Separador
    #t_1_6
    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.6 Fases de la auditoría
    .row.mb-3.justify-content-center.align-items-center(data-aos="fade-left")
      .col-lg-12
        .row
          .col-12.p-4.bg2.mb-2
            .row.align-items-center
              .col
                p.mb-0 De acuerdo al diagrama de flujo presentado por la metodología de la norma GTC-ISO 19011:2018, se pueden establecer tres fases para el desarrollo de una auditoría: la planeación, la implementación y el monitoreo de la misma.

              .col-lg-auto
                figure
                  img(src='@/assets/curso/tema1/img23.svg', style="width: 60px" alt="").m-auto
    p.mb-5 Explore el recurso didáctico que se muestra a continuación y profundice en las fases de la auditoría. Le recordamos que puede llevar registro de los aspectos más destacados, en su libreta personal de apuntes.
    .row.align-items-center.mb-5(data-aos="fade-right")
      .col-lg-4
        figure.d-flex.justify-content-center.mb-3
          img.img-t.mx-auto(src='@/assets/curso/tema1/img24.svg',  alt="")
      .col-lg-8
        AcordionA(tipo="b" clase-tarjeta="tarjeta tarjeta--azul")
          .row(titulo="Planeación de la auditoría")
            .col-12
              .row.align-items-center
                .col-lg-12
                  ul.lista-ul--color
                    li
                      i.fas.fa-check-circle(style="color:#583AE2")
                      span La auditoría debe ser programada, aprobada e informada a todos los líderes de procesos e interesados con tiempo de antelación.
                    li
                      i.fas.fa-check-circle(style="color:#583AE2")
                      span Para las auditorías, es necesario que todos los líderes de procesos y equipos estén informados y alineados en atención a los requerimientos de los auditores, de tal manera que pueda ser presentada cualquier evidencia o requerimiento que sea solicitado por el auditor.
                    li
                      i.fas.fa-check-circle(style="color:#583AE2")
                      span De acuerdo con el ciclo PHVA, las auditorías deben de realizarse por lo menos una vez en el año, aunque si la organización considera, debido a la criticidad de sus procesos, o con el fin de determinar alguna verificación, que deban hacer más en este periodo de tiempo, también es válido; esto ayudaría a evaluar e identificar falencias en los criterios de auditoría.
                    li
                      i.fas.fa-check-circle(style="color:#583AE2")
                      span Para cada auditoría se debe contar con los informes de las auditorías anteriores, tanto internas como externas, y revisiones de la alta dirección. Además, estas auditorías deben realizarse antes de las auditorías de certificación y/o acreditación, ya que estas auditorías internas pueden detectar falencias que pueden corregirse para dicha evaluación.

          .row(titulo="Implementación de la auditoría")
            .col-12
              .row.align-items-center
                .col-lg-12
                  ul.lista-ul--color
                    li
                      i.fas.fa-check-circle(style="color:#583AE2")
                      span En este evento se realiza la apertura de la auditoría en la cual se presenta la metodología, tiempos, procesos, sistemas o cualquier detalle que permita identificar el alcance de la misma, se hace entrega de la información existente o de auditorías anteriores, y se da inicio al ejercicio de acuerdo a la programación establecida.
                    li
                      i.fas.fa-check-circle(style="color:#583AE2")
                      span Una vez se finalice el ejercicio, el auditor realiza el informe, el cual es presentado durante el cierre de la auditoría.
                    li
                      i.fas.fa-check-circle(style="color:#583AE2")
                      span Con el informe del auditor,  la alta dirección establecerá las acciones de mejora a futuro, a través de un plan de mejoramiento; estas acciones pueden ser correctivas, preventivas o de mejora.

          .row(titulo="Monitoreo a la auditoría")
            .col-12
              .row.align-items-center
                .col-lg-12
                  ul.lista-ul--color
                    li
                      i.fas.fa-check-circle(style="color:#583AE2")
                      span En esta fase, se busca realizar el seguimiento a las acciones establecidas en el último ejercicio, con el fin de validar su efectividad en la corrección de falencias o la adecuada implementación de nuevos controles.
                    li
                      i.fas.fa-check-circle(style="color:#583AE2")
                      span Este seguimiento debe realizarse de manera permanente con el fin de reportar avances y fortalecer aquellas acciones que pueden retrasar el cumplimiento de los objetivos

</template>

<script>
import SlyderF from '../components/SlyderF.vue'
export default {
  name: 'Tema1',
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

#tema_1_0
  .horizontal-scroll
    padding-top: 0 !important
    padding-bottom: 0 !important
</style>
