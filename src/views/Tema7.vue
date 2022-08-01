<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 7
      h1 Prácticas de pronunciación
    p(data-aos="fade-down").mb-5 A continuación, podrá realizar una práctica detallada de pronunciación. Para cada uno de los siguientes audios, escuche, repita, grabe su voz y escúchese, y si es necesario, repita el ejercicio: 

    .row.justify-content-center.align-items-stretch.mb-5
      .col-lg-4.bg33.p-5
        h4.text-center.mb-4 Práctica 1
        img.img-a.img-t.mb-5(data-aos="zoom-in")(src='@/assets/curso/temas/3.png', alt='')
        .row.justify-content-center.align-items-center
          .col-lg-4               
            Audio.color-acento-contenido.audio--big.mx-3(
              :audio="require('@/assets/curso/audio/7/1.mp3')"
              @audio-hover="mostrarIndicadorAudio = false"
            )
              .indicador--click(v-if="mostrarIndicadorAudio")
      .col-lg-4.bg33.p-5
        h4.text-center.mb-4 Práctica 2
        img.img-a.img-t.mb-5(data-aos="zoom-in")(src='@/assets/curso/temas/4.png', alt='')
        .row.justify-content-center.align-items-center
          .col-lg-4               
            Audio.color-acento-contenido.audio--big.mx-3(
              :audio="require('@/assets/curso/audio/7/2.mp3')")
      .col-lg-4.bg33.p-5
        h4.text-center.mb-4 Práctica 3
        img.img-a.img-t.mb-4(data-aos="zoom-in")(src='@/assets/curso/temas/5.png', alt='') 
        a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=mBGmCjxZua4 " target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg")
          .anexo__texto
            p #[b Enlace web.] INGLES PRONUNCIACION: LOS 3 SONIDOS DE LA VOCAL A

    p(data-aos="fade-down").mb-5 Adicionalmente puede consultar a través de los diccionarios en línea la pronunciación que tienen para los diferentes conceptos que encuentra: 

    .row.justify-content-center.align-items-end
      .col-lg-4
        img.img-a.img-t(data-aos='zoom-in-up')(src='@/assets/curso/temas/img25.png', alt='')
        .bgp.text-center.py-4
          h4.g(data-aos="fade-down").mb-0 Diccionario / Dictionary
      .col-lg-6
        p(data-aos="fade-down") Para verificar el significado y la pronunciación, puede hacer uso de herramientas en línea como
        .row.justify-content-center.align-items-center.mb-4
          .col-lg-6
            a.anexo.mb-4.mb-lg-0(href="https://www.linguee.es/" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-link.svg")
              .anexo__texto
                p #[b Enlace web.] Linguee                     
          .col-lg-6
            a.anexo.mb-4.mb-lg-0(href="https://www.wordreference.com/" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-link.svg")
              .anexo__texto
                p #[b Enlace web.] Wordreference                     
        p(data-aos="fade-down") que le permiten escuchar, definir y apropiar vocabulario en inglés.                      

</template>

<script>
export default {
  name: 'Tema7',
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
