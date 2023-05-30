<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span.text-white
          i.fas.fa-info
      h1 Introducción
    .row.align-items-center.justify-content-center
      .col-lg-12
        p Aquí inicia el estudio del componente formativo #[span.txt-c1 “Auditorías a las estrategias de ciberseguridad”]. En este punto, visualice con atención el video que se muestra en seguida y comience esta experiencia de aprendizaje, en la que se le desean todos los éxitos.
        p #[span.txt-c1 ¡Adelante!]
    .row.justify-content-center.bg1
      .col-lg-12
        figure.p-5
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/tb-5JFFA22Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
          
            
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
