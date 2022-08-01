<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-tasks" titulo="Actividad didáctica")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .row.mb-5.justify-content-center.align-items-center.align-items-lg-stretch
      .col-6.col-md-4.col-lg-3.mb-4.mb-md-0
        .tarjeta.h-100.d-flex.align-items-center.p-4
          figure
            img(src="@/assets/template/seleccion-multiple.svg", alt="")
      .col-12.col-md-8.col-lg-9
        .titulo-segundo
          h2 #[i Daily activities] / Actividades diarias
        p.mb-4 Indicar actividades en el hogar y en el trabajo.
        .tarjeta.actividad.p-3
          .row.justify-content-around.align-items-center            
            .col-sm.mb-3.mb-sm-0
              p.fw-bold.mb-0 Clasificar frases
            .col-auto
              a.boton.boton--b(:href="obtenerLink('/actividades/01/index.html')" target="_blank")
                span Realizar
                i.fas.fa-puzzle-piece

    hr.my-5  

    
    .row.mb-5.justify-content-center.align-items-center.align-items-lg-stretch
      .col-6.col-md-4.col-lg-3.mb-4.mb-md-0
        .tarjeta.h-100.d-flex.align-items-center.p-4
          figure
            img(src="@/assets/template/seleccion-multiple.svg", alt="")
      .col-12.col-md-8.col-lg-9
        .titulo-segundo
          h2 Oraciones en Presente simple y Presente Progresivo
        p.mb-4 Reconocer el tiempo verbal de las oraciones.
        .tarjeta.actividad.p-3
          .row.justify-content-around.align-items-center            
            .col-sm.mb-3.mb-sm-0
              p.fw-bold.mb-0 Clasificar frases
            .col-auto
              a.boton.boton--b(:href="obtenerLink('/actividades/02/index.html')" target="_blank")
                span Realizar
                i.fas.fa-puzzle-piece

    hr.my-5   

    
    .row.mb-5.justify-content-center.align-items-center.align-items-lg-stretch
      .col-6.col-md-4.col-lg-3.mb-4.mb-md-0
        .tarjeta.h-100.d-flex.align-items-center.p-4
          figure
            img(src="@/assets/template/seleccion-multiple.svg", alt="")
      .col-12.col-md-8.col-lg-9
        .titulo-segundo
          h2 #[i Linking phrases ]/ Enlazando frases
        p.mb-4 Enlazar frases u oraciones utilizando las conjunciones “#[i when]” y “#[i while]”
        .tarjeta.actividad.p-3
          .row.justify-content-around.align-items-center            
            .col-sm.mb-3.mb-sm-0
              p.fw-bold.mb-0 Opción múltiple
            .col-auto
              a.boton.boton--b(:href="obtenerLink('/actividades/03/index.html')" target="_blank")
                span Realizar
                i.fas.fa-puzzle-piece

    hr.my-5   

    
    .row.mb-5.justify-content-center.align-items-center.align-items-lg-stretch
      .col-6.col-md-4.col-lg-3.mb-4.mb-md-0
        .tarjeta.h-100.d-flex.align-items-center.p-4
          figure
            img(src="@/assets/template/arrastrar.svg", alt="")
      .col-12.col-md-8.col-lg-9
        .titulo-segundo
          h2 #[i How often is it?] / ¿Con qué frecuencia es?
        p.mb-4 Reconocer los adverbios de frecuencia, tiempo y duración en el idioma Inglés.
        .tarjeta.actividad.p-3
          .row.justify-content-around.align-items-center            
            .col-sm.mb-3.mb-sm-0
              p.fw-bold.mb-0 Arrastrar y soltar
            .col-auto
              a.boton.boton--b(:href="obtenerLink('/actividades/04/index.html')" target="_blank")
                span Realizar
                i.fas.fa-puzzle-piece

    hr.my-5   

    
    .row.mb-5.justify-content-center.align-items-center.align-items-lg-stretch
      .col-6.col-md-4.col-lg-3.mb-4.mb-md-0
        .tarjeta.h-100.d-flex.align-items-center.p-4
          figure
            img(src="@/assets/template/completar-espacios.svg", alt="")
      .col-12.col-md-8.col-lg-9
        .titulo-segundo
          h2 #[i Sequence connectors] / Conectores de secuencia
        p.mb-4 Vincular frases u oraciones utilizando los conectores de secuencia.
        .tarjeta.actividad.p-3
          .row.justify-content-around.align-items-center            
            .col-sm.mb-3.mb-sm-0
              p.fw-bold.mb-0 Completar frases
            .col-auto
              a.boton.boton--b(:href="obtenerLink('/actividades/05/index.html')" target="_blank")
                span Realizar
                i.fas.fa-puzzle-piece

    hr.my-5   

    
    .row.mb-5.justify-content-center.align-items-center.align-items-lg-stretch
      .col-6.col-md-4.col-lg-3.mb-4.mb-md-0
        .tarjeta.h-100.d-flex.align-items-center.p-4
          figure
            img(src="@/assets/template/completar-espacios.svg", alt="")
      .col-12.col-md-8.col-lg-9
        .titulo-segundo
          h2 #[i Dictation practice ]/ Práctica de dictado
        p.mb-4 Escuchar con atención las palabras que se enuncian en el audio y escribirlas en el lugar indicado.
        .tarjeta.actividad.p-3
          .row.justify-content-around.align-items-center            
            .col-sm.mb-3.mb-sm-0
              p.fw-bold.mb-0 Escuchar y escribir palabras
            .col-auto
              a.boton.boton--b(:href="obtenerLink('/actividades/06/index.html')" target="_blank")
                span Realizar
                i.fas.fa-puzzle-piece
                
</template>

<script>
export default {
  name: 'Actividad',
}
</script>

<style lang="sass"></style>
