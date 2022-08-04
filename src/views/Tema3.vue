<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Usos de <i>when</i> y <i>while</i>
    p(data-aos="fade-down") En el idioma inglés, existen ciertas palabras que se utilizan para unir o enlazar entre sí frases u oraciones, es decir, son conjunciones, las cuales sirven para dar más coherencia y significado a las ideas que se quieren expresar. Entre ellas, las conjunciones when y while, las cuales se utilizan en forma regular al escribir o hablar en idioma inglés. 
    .bg21    
      h5(data-aos="fade-down").text-center #[b #[i For example:]]
      .row.justify-content-center.align-items-stretch.my-5
        .col-lg-6(data-aos="fade-right").tarjeta.position-relative.rounded-0.bg19.p-4.brwhite
          img.img-t.img-a.mb-3(data-aos='zoom-in-up')(src='@/assets/curso/temas/img56.png', alt='')
          .p-2
            TarjetaAudio.color-acento-contenido.bg-white.mb-4(
              texto="When I was sleeping, they left the apartment."
              :audio="require('@/assets/curso/audio/3/1.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )     
            p(data-aos="fade-down") Cuando yo estaba durmiendo, ellos abandonaron el apartamento                 

        .col-lg-6(data-aos="fade-left").tarjeta.position-relative.rounded-0.bg20.p-4.brwhite
          img.img-t.img-a.mb-3(data-aos='zoom-in-up')(src='@/assets/curso/temas/img57.png', alt='')
          TarjetaAudio.color-acento-contenido.bg-white.mb-4(
            texto="While I was walking, I found a bill on the floor."
            :audio="require('@/assets/curso/audio/3/2.mp3')"
            @audio-hover="mostrarIndicadorTarjetaAudio = false"
          )     
          p(data-aos="fade-down") Mientras yo estaba caminando, encontré un billete en el piso.
             
      p(data-aos="fade-down").mb-5 En este orden de ideas, al usar 
        span.r #[b #[i when ]] 
        span (cuando) y 
        span.r #[b #[i while ]] 
        span (mientras), se está realizando una mezcla de dos tiempos verbales: el pasado simple y el pasado continuo, puesto que, al expresar una acción en progreso en el pasado, esta se cruza con otra acción que la interrumpe. Revise cada uno de sus usos:

      TabsA.color-acento-botones.mb-5
        .tarjeta.color-acento-botones--borde.p-4(titulo="<i>Uso de when +</i>")
          .row.justify-content-center.align-items-center
            .col-lg-11
              h5.r #[i Uso de when + ]
              p La palabra #[i when] es una conjunción, es decir, tiene la función de enlazar frases entre sí. Su significado en español es #[b cuando] y se usa porque una acción se ve interrumpida.

              p En líneas generales, la conjunción when se utiliza con las acciones que se cruzan o que interrumpen la primera acción, la acción continua o la acción que estaba en progreso. De esta manera, when se puede usar para acciones puntuales y esta acción se escribe en pasado simple. 
              h5(data-aos="fade-down").text-center.mb-4 #[b #[i For example:]] 
              .row.justify-content-center.align-items-center.mb-4
                .col-lg-3
                  img.img-a.img-t(src='@/assets/curso/temas/img58.png', alt='')
                .col-lg-9
                  TarjetaAudio.color-acento-contenido.bg-white.mb-4(
                    texto="I was washing the dishes when the phone rang."
                    :audio="require('@/assets/curso/audio/3.1/1.mp3')"
                    @audio-hover="mostrarIndicadorTarjetaAudio = false"
                  )     
                  p(data-aos="fade-down").mb-0 Yo estaba lavando los platos cuando el teléfono sonó.

              .row.justify-content-center.align-items-center
                .col-lg-3
                  img.img-a.img-t(src='@/assets/curso/temas/img59.png', alt='')
                .col-lg-9
                  TarjetaAudio.color-acento-contenido.bg-white.mb-4(
                    texto="When we were in the cinema, my sister called."
                    :audio="require('@/assets/curso/audio/3.1/2.mp3')"
                    @audio-hover="mostrarIndicadorTarjetaAudio = false"
                  )     
                  p(data-aos="fade-down").mb-0 Cuando estábamos en el cine, mi hermana llamó.

        .tarjeta.color-acento-botones--borde.p-4(titulo="<i>Uso de while +</i>")
          .row.justify-content-center.align-items-center
            .col-lg-11
              h5.r #[i Uso de while + ]
              p Otra conjunción que se utiliza mucho en inglés es #[i while], la cual significa #[b mientras]. En general, se usa  para indicar que, mientras se realizaba una acción, otra persona estaba realizando otra actividad o acción a la vez.

              p Básicamente, se usa con la primera acción o la acción que está en progreso, o la acción continua, pues se requiere poner énfasis en la duración de esta acción. De manera que esta acción (o verbo) se escribe en tiempo pasado continuo.

              h5(data-aos="fade-down").text-center.mb-4 #[b #[i For example:]] 
              .row.justify-content-center.align-items-center.mb-4
                .col-lg-3
                  img.img-a.img-t(src='@/assets/curso/temas/img60.png', alt='')
                .col-lg-9
                  TarjetaAudio.color-acento-contenido.bg-white.mb-4(
                    texto="I was studying while the maid cooked."
                    :audio="require('@/assets/curso/audio/3.2/1.mp3')"
                    @audio-hover="mostrarIndicadorTarjetaAudio = false"
                  )     
                  p(data-aos="fade-down").mb-0 Yo estaba estudiando mientras la criada cocinaba.

              .row.justify-content-center.align-items-center
                .col-lg-3
                  img.img-a.img-t(src='@/assets/curso/temas/img61.png', alt='')
                .col-lg-9
                  TarjetaAudio.color-acento-contenido.bg-white.mb-4(
                    texto="I was walking across the bridge while you were in the house"
                    :audio="require('@/assets/curso/audio/3.2/2.mp3')"
                    @audio-hover="mostrarIndicadorTarjetaAudio = false"
                  )     
                  p(data-aos="fade-down").mb-0 Yo estaba caminando por el puente mientras tú estabas en la casa.

    p(data-aos="fade-down").pt-5.text-center.mb-5 Ahora, practique lo aprendido, teniendo en cuenta el uso de cada una de las palabras en diferentes frases:

    Dialogo.color-primario.mb-5(:dialogo="dialogo")(data-aos="flip-down")
      template(#nombre-actividad) Arrastrar y Soltar
      template(#titulo-actividad) Completa la conversación.
      template(#descripcion-actividad) Arrastra y suelta el cada una de las palabras en el orden correcto.  

</template>

<script>
import Dialogo from '../components/Dialogo.vue'
export default {
  name: 'Tema3',
  components: {
    Dialogo,
  },
  data: () => ({
    dialogo: {
      personajes: [
        {
          nombre: 'language',
          img: require('@/assets/curso/temas/1.svg'),
        },
        {
          nombre: 'cousins',
          img: require('@/assets/curso/temas/2.svg'),
        },
        {
          nombre: 'cooking ',
          img: require('@/assets/curso/temas/3.svg'),
        },
        {
          nombre: 'resting ',
          img: require('@/assets/curso/temas/4.svg'),
        },
      ],
      dialogo: [
        {
          personaje: 'language',
          textoIng:
            '*** he was living in Oregon, Jim learned the English language.',
          textoEsp:
            '*** estaba viviendo en Oregon, Jim aprendió el idioma Inglés.',
          audio: require('@/assets/curso/audio/a1/1.mp3'),
          palabra: 'While',
        },
        {
          personaje: 'language',
          textoIng: '*** I was younger I liked to play with my cousins.',
          textoEsp: '*** era más joven, me gustaba jugar con mis primos..',
          audio: require('@/assets/curso/audio/a1/2.mp3'),
          palabra: 'When',
        },
        {
          personaje: 'language',
          textoIng:
            '*** I was cooking the lunch, the children played in the garden.',
          textoEsp:
            '*** yo estaba cocinando el almuerzo, los niños jugaban en el jardín.',
          audio: require('@/assets/curso/audio/a1/3.mp3'),
          palabra: 'While ',
        },
        {
          personaje: 'language',
          textoIng: 'You were resting on the sofa *** my father arrived.',
          textoEsp: 'Tú estabas descansando en el sofá *** mi padre llegó.',
          audio: require('@/assets/curso/audio/a1/4.mp3'),
          palabra: 'when ',
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
