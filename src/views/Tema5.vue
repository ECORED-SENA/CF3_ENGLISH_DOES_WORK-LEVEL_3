<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Adverbios de tiempo y adverbios de duración

    .tarjeta.position-relative.rounded-0.bg26.p-3
      .row.justify-content-center.align-items-center
        .col-lg-2.col-5.mb-lg-0.mb-3
          .imagen-absolute
            img(data-aos='zoom-in-up')(src='@/assets/curso/temas/img82.png', alt='')
        .col-lg-10
          p(data-aos="fade-down").mb-0.p-2 Los adverbios son palabras que añaden información circunstancial respecto a una oración o palabra, generalmente acompañando o modificando el verbo. En este caso, se hace referencia a los adverbios de tiempo y de duración. 

    Separador 
    #t_5_1.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 5.1  Adverbios de tiempo

    p(data-aos="fade-down").mb-5 En líneas generales, los adverbios de tiempo son aquellos que agregan información temporal a la oración de la cual forman parte. Estos adverbios aportan, por lo tanto, datos que permiten responder una pregunta sobre cuándo se desarrolló, se desarrolla o se desarrollará una acción. A continuación, se presentan los adverbios de tiempo más utilizados:

    .row.justify-content-center.align-items-center
      .col-lg-4 
        img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img83.png', alt='')       

      .col-lg-8.bg24.p-5.bradius(data-aos="fade-left")     
        SlyderF(columnas="col-lg-6")(data-aos="fade-right")
          .crd.crd--100.tarjeta.color-primario.p-4.bg-white
            p.text-center #[b #[i Now] / ahora]
            .row.justify-content-center.mb-3
              .col-8
                img.img-a.img-t(src='@/assets/curso/temas/img84.png' alt='')

            TarjetaAudio.color-acento-contenido.bg-white.my-3(
              texto="<i>Let’s go now.</i>"
              :audio="require('@/assets/curso/audio/5/1.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0.text-center Vamos ahora.

          .crd.crd--100.tarjeta.color-primario.p-4.bg-white
            p.text-center #[b #[i Today] / hoy]
            .row.justify-content-center.mb-3
              .col-8
                img.img-a.img-t(src='@/assets/curso/temas/img85.png' alt='')

            TarjetaAudio.color-acento-contenido.bg-white.my-3(
              texto="<i>Today is Mother’s day.</i>"
              :audio="require('@/assets/curso/audio/5/2.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0.text-center Hoy es Día de las Madres.

          .crd.crd--100.tarjeta.color-primario.p-4.bg-white
            p.text-center #[b #[i Tomorrow] / mañana ]
            .row.justify-content-center.mb-3
              .col-8
                img.img-a.img-t(src='@/assets/curso/temas/img86.png' alt='')

            TarjetaAudio.color-acento-contenido.bg-white.my-3(
              texto="<i>You’re going to travel tomorrow.</i>"
              :audio="require('@/assets/curso/audio/5/3.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0.text-center Tú vas a viajar mañana.

          .crd.crd--100.tarjeta.color-primario.p-4.bg-white
            p.text-center #[b #[i Tonight] / esta noche ]
            .row.justify-content-center.mb-3
              .col-8
                img.img-a.img-t(src='@/assets/curso/temas/img87.png' alt='')

            TarjetaAudio.color-acento-contenido.bg-white.my-3(
              texto="<i>Felix will come tonight.</i>"
              :audio="require('@/assets/curso/audio/5/4.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0.text-center Felix vendrá esta noche.

          .crd.crd--100.tarjeta.color-primario.p-4.bg-white
            p.text-center #[b #[i Yesterday] / ayer ]
            .row.justify-content-center.mb-3
              .col-8
                img.img-a.img-t(src='@/assets/curso/temas/img88.png' alt='')

            TarjetaAudio.color-acento-contenido.bg-white.my-3(
              texto="<i>Yesterday, you went to the disco.</i>"
              :audio="require('@/assets/curso/audio/5/5.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0.text-center Ayer, fuiste a la discoteca.

          .crd.crd--100.tarjeta.color-primario.p-4.bg-white
            p.text-center #[b #[i Later] / luego ]
            .row.justify-content-center.mb-3
              .col-8
                img.img-a.img-t(src='@/assets/curso/temas/img89.png' alt='')

            TarjetaAudio.color-acento-contenido.bg-white.my-3(
              texto="<i>I’ll call you later. </i>"
              :audio="require('@/assets/curso/audio/5/6.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0.text-center Te llamaré más tarde.

          .crd.crd--100.tarjeta.color-primario.p-4.bg-white
            p.text-center #[b #[i Last month] / el mes pasado ]
            .row.justify-content-center.mb-3
              .col-8
                img.img-a.img-t(src='@/assets/curso/temas/img90.png' alt='')

            TarjetaAudio.color-acento-contenido.bg-white.my-3(
              texto="<i>You won the prize last month.</i>"
              :audio="require('@/assets/curso/audio/5/7.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )                    
            p.mb-0.text-center Tú ganaste el premio el mes pasado.

    p(data-aos="fade-down").my-5 En este caso, para realizar una pregunta, se utiliza el pronombre interrogativo “when” y se debe utilizar la expresión de frecuencia o adverbio de tiempo para responder. Practique un poco:

    Dialogo.color-primario.mb-5(:dialogo="dialogo")(data-aos="fade-left")
      template(#nombre-actividad) Arrastrar y Soltar
      template(#titulo-actividad) Titulo de actividad - Completa la conversación.
      template(#descripcion-actividad) Arrastra y suelta el cada una de las palabras en el orden correcto.

    Separador 
    #t_5_2.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 5.2 Adverbios de duración
    p(data-aos="fade-down").mb-5 Son los adverbios que indican durante cuánto tiempo sucede algo. Se ubican al final de la frase. Entre ellos están: #[i for] y #[i since]:
    .row.justify-content-center.align-items-stretch
      .col-lg-6.up.bg27.p-5(data-aos="fade-left")
        p(data-aos="fade-down").my-4 * Cuando se utiliza 
          span.r #[b #[i for]], 
          span este debe ir seguido por una expresión que aluda a un periodo de tiempo (#[i a year, a week, a month, a moment], entre otros). #[b #[i For example:]]
        .bg29.p-5.position-relative
          .bg-white.bradius.py-5.px-3
            .row.justify-content-end.align-items-center
              .col-lg-2.col-5.mb-lg-0.mb-3.d-none.d-lg-block
                .imagen-absolute6
                  img.img-t(data-aos='zoom-in-up')(src='@/assets/curso/temas/img91.png', alt='')                 
              .col-lg-9
                SlyderE(indicadores="derecha").p-3
                  .row.justify-content-end.align-items-center
                    .col-lg-10.pe-3
                        TarjetaAudio.color-acento-contenido.bg-white.my-3(
                          texto="<i>Gabriel stayed in Miami for six months.</i>"
                          :audio="require('@/assets/curso/audio/5.2/1.mp3')"
                          @audio-hover="mostrarIndicadorTarjetaAudio = false"
                        )                    
                        p Gabriel se quedó en Miami durante seis meses.
                  .row.justify-content-end.align-items-center
                    .col-lg-10.pe-3
                        TarjetaAudio.color-acento-contenido.bg-white.my-3(
                          texto="<i>I worked there for two years.</i>"
                          :audio="require('@/assets/curso/audio/5.2/2.mp3')"
                          @audio-hover="mostrarIndicadorTarjetaAudio = false"
                        )                    
                        p Yo trabajé allí por dos años.
                  .row.justify-content-end.align-items-center
                    .col-lg-10.pe-3
                        TarjetaAudio.color-acento-contenido.bg-white.my-3(
                          texto="<i>You have been waiting for a week.</i>"
                          :audio="require('@/assets/curso/audio/5.2/3.mp3')"
                          @audio-hover="mostrarIndicadorTarjetaAudio = false"
                        )                    
                        p Tú has estado esperando por una semana.
                  .row.justify-content-end.align-items-center
                    .col-lg-10.pe-3
                        TarjetaAudio.color-acento-contenido.bg-white.my-3(
                          texto="<i>They were imprisoned for a decade.</i>"
                          :audio="require('@/assets/curso/audio/5.2/4.mp3')"
                          @audio-hover="mostrarIndicadorTarjetaAudio = false"
                        )                    
                        p Ellos estuvieron presos por una década.
                  .row.justify-content-end.align-items-center
                    .col-lg-10.pe-3
                        TarjetaAudio.color-acento-contenido.bg-white.my-3(
                          texto="<i>The doctor held his head for several minutes.</i>"
                          :audio="require('@/assets/curso/audio/5.2/5.mp3')"
                          @audio-hover="mostrarIndicadorTarjetaAudio = false"
                        )                    
                        p El doctor sostuvo su cabeza por algunos minutos.
                  .row.justify-content-end.align-items-center
                    .col-lg-10.pe-3
                        TarjetaAudio.color-acento-contenido.bg-white.my-3(
                          texto="<i>Marian was in a coma for a day. </i>"
                          :audio="require('@/assets/curso/audio/5.2/6.mp3')"
                          @audio-hover="mostrarIndicadorTarjetaAudio = false"
                        )                    
                        p Marian estuvo en coma por un día.
                  .row.justify-content-end.align-items-center
                    .col-lg-10.pe-3
                        TarjetaAudio.color-acento-contenido.bg-white.my-3(
                          texto="<i>The baby was sleeping for a long time.</i>"
                          :audio="require('@/assets/curso/audio/5.2/7.mp3')"
                          @audio-hover="mostrarIndicadorTarjetaAudio = false"
                        )                    
                        p El bebé estuvo durmiendo por mucho tiempo.
                  .row.justify-content-end.align-items-center
                    .col-lg-10.pe-3
                        TarjetaAudio.color-acento-contenido.bg-white.my-3(
                          texto="<i>Kris studied English for a semester. </i>"
                          :audio="require('@/assets/curso/audio/5.2/8.mp3')"
                          @audio-hover="mostrarIndicadorTarjetaAudio = false"
                        )                    
                        p Kris estudió inglés durante un semestre.
      .col-lg-6.up.bg28.p-5(data-aos="fade-right")
        p(data-aos="fade-down").my-4.mb-5 * Cuando se utiliza 
          span.r #[b #[i since]], 
          span este debe ir seguido por una expresión que aluda a un momento concreto en el tiempo. #[b #[i For example:]]
        .bg29.p-5.pe-5.position-relative
          .bg-white.bradius.py-5.px-3
            .row.justify-content-start.align-items-center
              .col-lg-9
                SlyderE(indicadores="derecha").p-3
                  .row.justify-content-start.align-items-center
                    .col-lg-10
                        TarjetaAudio.color-acento-contenido.bg-white.my-3(
                          texto="<i>Betty has been living in that house since 2012.</i>"
                          :audio="require('@/assets/curso/audio/5.2/1.mp3')"
                          @audio-hover="mostrarIndicadorTarjetaAudio = false"
                        )                    
                        p Betty ha estado viviendo en esa casa desde 2012.
  
                  .row.justify-content-start.align-items-center
                    .col-lg-10
                        TarjetaAudio.color-acento-contenido.bg-white.my-3(
                          texto="<i>You haven’t come home since Thursday.</i>"
                          :audio="require('@/assets/curso/audio/5.2/10.mp3')"
                          @audio-hover="mostrarIndicadorTarjetaAudio = false"
                        )                    
                        p Tú no has venido a casa desde el jueves.
  
                  .row.justify-content-start.align-items-center
                    .col-lg-10
                        TarjetaAudio.color-acento-contenido.bg-white.my-3(
                          texto="<i>Dylan hasn't been back to work since January.</i>"
                          :audio="require('@/assets/curso/audio/5.2/11.mp3')"
                          @audio-hover="mostrarIndicadorTarjetaAudio = false"
                        )                    
                        p Dylan no ha vuelto a trabajar desde enero.

                  .row.justify-content-start.align-items-center
                    .col-lg-10
                        TarjetaAudio.color-acento-contenido.bg-white.my-3(
                          texto="<i>Katy hasn’t eaten since this morning.</i>"
                          :audio="require('@/assets/curso/audio/5.2/12.mp3')"
                          @audio-hover="mostrarIndicadorTarjetaAudio = false"
                        )                    
                        p Katy no ha comido desde esta mañana.
              .col-lg-2.col-5.mb-lg-0.mb-3.d-none.d-lg-block
                .imagen-absolute5
                  img.img-t(data-aos='zoom-in-up')(src='@/assets/curso/temas/img92.png', alt='')
    .row.mt-5.justify-content-center.align-items-center.align-items-lg-stretch
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
</template>

<script>
export default {
  name: 'Tema5',
  data: () => ({
    dialogo: {
      personajes: [
        {
          nombre: 'Paula',
          img: require('@/assets/curso/temas/Sue.svg'),
        },
        {
          nombre: 'Matthew',
          img: require('@/assets/curso/temas/Jim.svg'),
        },
      ],
      dialogo: [
        {
          personaje: 'Paula',
          textoIng: 'When are you going to prepare my lunch?',
          textoEsp: '¿Cuándo vas a preparar mi almuerzo?',
          audio: require('@/assets/curso/audio/5/a2/1.mp3'),
        },
        {
          personaje: 'Matthew',
          textoIng: 'I’m going to prepare it ***.',
          textoEsp: 'voy a prepararlo ***.',
          audio: require('@/assets/curso/audio/5/a2/2.mp3'),
          palabra: 'now',
        },
        {
          personaje: 'Paula',
          textoIng: 'When is Mike’s graduation?',
          textoEsp: '¿Cuándo es la graduación de Mike?',
          audio: require('@/assets/curso/audio/5/a2/3.mp3'),
        },
        {
          personaje: 'Matthew',
          textoIng: '*** is Mike’s graduation.',
          textoEsp: '*** es la graduación de Mike.',
          audio: require('@/assets/curso/audio/5/a2/4.mp3'),
          palabra: 'Today',
        },
      ],
    },
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
