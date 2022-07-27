<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Adverbios de frecuencia
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-5
        img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img62.png', alt='')
      .col-lg-7
        p(data-aos="fade-down") Un adverbio es un tipo de palabra invariable, que actúa como núcleo del sintagma adverbial, complementando a un verbo, un adjetivo u otro adverbio. En general, es una palabra dotada de significado léxico y modifica el significado de varias categorías, principalmente, de un verbo, de un adjetivo, de una oración o de una palabra de la misma clase.
        .bg22.p-3(data-aos="flip-down").mb-4
          p(data-aos="fade-down").mb-0 Existen varias clases o tipos de adverbios, por ello, de acuerdo con su significado, se pueden clasificar como: adverbios de lugar, de tiempo, de duración, de frecuencia, de modo, entre otros.
        p(data-aos="fade-down") Los 
          span.r #[b #[i adverbios de frecuencia ]]
          span  son aquellos adverbios que se utilizan para expresar la periodicidad con la que se realiza una acción, es decir, cuando se quiere expresar la frecuencia con la que se realiza algo, o la frecuencia con la que algo sucede, y generalmente modifican al verbo de la oración que están formando.
    .bg23
      h5(data-aos="fade-down").text-center #[b For example:]
      .row.justify-content-center.align-items-center.my-5
        .col-lg-6(data-aos="fade-right")
          .tarjeta.position-relative.rounded-0.bg19.p-3
            .row.justify-content-center.align-items-center
              .col-lg-6.col-5.mb-lg-0.mb-3
                .imagen-absolute3
                  img(data-aos='zoom-in-up')(src='@/assets/curso/temas/img63.png', alt='')
              .col-lg-6
                .p-2
                  TarjetaAudio.color-acento-contenido.bg-white.mb-4(
                    texto="I always get up at 7:00 o’clock."
                    :audio="require('@/assets/curso/audio/4/1.mp3')"
                    @audio-hover="mostrarIndicadorTarjetaAudio = false"
                  )     
                  p(data-aos="fade-down").mb-0 Yo siempre me levanto a las siete en punto de la mañana.

            p(data-aos="fade-down").text-center.pt-2 #[b En este caso, modifica el verbo “#[i get up]”.]                 

        .col-lg-6(data-aos="fade-left")
          .tarjeta.position-relative.rounded-0.bg20.p-3
            .row.justify-content-center.align-items-center
              .col-lg-6
                .p-2
                  TarjetaAudio.color-acento-contenido.bg-white.mb-4(
                    texto="That girl never cries in front of you."
                    :audio="require('@/assets/curso/audio/4/2.mp3')"
                    @audio-hover="mostrarIndicadorTarjetaAudio = false"
                  )     
                  p(data-aos="fade-down").mb-4 Esa chica nunca llora enfrente de ti.                       
              .col-lg-6.col-5.mb-lg-0.mb-3
                .imagen-absolute4
                  img(data-aos='zoom-in-up')(src='@/assets/curso/temas/img64.png', alt='')

            p(data-aos="fade-down").text-center.pt-2 #[b En este caso, modifica el verbo “cries”.] 

    Separador 
    #t_4_1.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 4.1  Principales adverbios de frecuencia

    p(data-aos="fade-down").mb-5 Ahora, revise cada uno de los principales adverbios de frecuencia que servirán para, en adelante, expresar la regularidad con la que realiza sus acciones: 

    ImagenInfografica.color-acento-botones.mb-5
      template(v-slot:imagen)
        figure
          img.img-a.img-t(src='@/assets/curso/temas/img65.svg', alt='')


      .tarjeta.color-acento-contenido.p-3(x="56%" y="4.5%" numero="+")
        .h5.mb-2.text-center.r #[i Always]
        p.text-center Expresar la idea de siempre, para siempre, o muy frecuentemente.
        TarjetaAudio.color-acento-contenido.bg-white.mb-4(
          texto="She will always love you."
          :audio="require('@/assets/curso/audio/4.1/1.mp3')"
          @audio-hover="mostrarIndicadorTarjetaAudio = false"
        )     
        p(data-aos="fade-down").mb-4 Ella siempre te amará. 

      .tarjeta.color-acento-contenido.p-3(x="44%" y="14.5%" numero="+")
        .h5.mb-2.text-center #[i Usually]
        p.text-center Indicar que algo sucede normalmente. 
        TarjetaAudio.color-acento-contenido.bg-white.mb-4(
          texto="Usually, Charles is late."
          :audio="require('@/assets/curso/audio/4.1/2.mp3')"
          @audio-hover="mostrarIndicadorTarjetaAudio = false"
        )     
        p(data-aos="fade-down").mb-4 Usualmente, Charles llega tarde.

      .tarjeta.color-acento-contenido.p-3(x="56%" y="24.5%" numero="+")
        .h5.mb-2.text-center #[i Often]
        p.text-center Indicar acciones que suceden en muchas ocasiones.
        TarjetaAudio.color-acento-contenido.bg-white.mb-4(
          texto="I often eat hot dogs for dinner."
          :audio="require('@/assets/curso/audio/4.1/3.mp3')"
          @audio-hover="mostrarIndicadorTarjetaAudio = false"
        )     
        p(data-aos="fade-down").mb-4 A menudo, como perros calientes para la cena.  

      .tarjeta.color-acento-contenido.p-3(x="44%" y="34.5%" numero="+")
        .h5.mb-2.text-center #[i Frequently]
        p.text-center Señalar que algo sucede frecuentemente. 
        TarjetaAudio.color-acento-contenido.bg-white.mb-4(
          texto="He frequently goes to the gym."
          :audio="require('@/assets/curso/audio/4.1/4.mp3')"
          @audio-hover="mostrarIndicadorTarjetaAudio = false"
        )     
        p(data-aos="fade-down").mb-4 Él frecuentemente va al gimnasio.

      .tarjeta.color-acento-contenido.p-3(x="56%" y="44%" numero="+")
        .h5.mb-2.text-center #[i Sometimes]
        p.text-center Decir que algo sucede algunas veces.
        TarjetaAudio.color-acento-contenido.bg-white.mb-4(
          texto="On weekends, sometimes we go to the beach."
          :audio="require('@/assets/curso/audio/4.1/5.mp3')"
          @audio-hover="mostrarIndicadorTarjetaAudio = false"
        )     
        p(data-aos="fade-down").mb-4 Los fines de semana, a veces, vamos a la playa.

      .tarjeta.color-acento-contenido.p-3(x="44%" y="54%" numero="+")
        .h5.mb-2.text-center #[i Occasionally]
        p.text-center Indicar que algo sucede algunas veces, pero no con frecuencia.
        TarjetaAudio.color-acento-contenido.bg-white.mb-4(
          texto="Occasionally, I go to that barbershop."
          :audio="require('@/assets/curso/audio/4.1/6.mp3')"
          @audio-hover="mostrarIndicadorTarjetaAudio = false"
        )     
        p(data-aos="fade-down").mb-4 Ocasionalmente, voy a esa barbería.

      .tarjeta.color-acento-contenido.p-3(x="56%" y="63%" numero="+")
        .h5.mb-2.text-center #[i Seldom]
        p.text-center Se utiliza de forma muy similar a rarely.
        TarjetaAudio.color-acento-contenido.bg-white.mb-4(
          texto="The old woman seldom buys used clothes."
          :audio="require('@/assets/curso/audio/4.1/7.mp3')"
          @audio-hover="mostrarIndicadorTarjetaAudio = false"
        )     
        p(data-aos="fade-down").mb-4 La anciana rara vez compra ropa usada.

      .tarjeta.color-acento-contenido.p-3(x="44%" y="73%" numero="+")
        .h5.mb-2.text-center #[i Rarely]
        p.text-center Decir que algo no sucede a menudo.
        TarjetaAudio.color-acento-contenido.bg-white.mb-4(
          texto="She rarely eats chicken for breakfast."
          :audio="require('@/assets/curso/audio/4.1/8.mp3')"
          @audio-hover="mostrarIndicadorTarjetaAudio = false"
        )     
        p(data-aos="fade-down").mb-4 Ella rara vez come pollo para el desayuno.

      .tarjeta.color-acento-contenido.p-3(x="55%" y="83%" numero="+")
        .h5.mb-2.text-center #[i Hardly ever]
        p.text-center Decir que algo sucede de forma casi excepcional.
        TarjetaAudio.color-acento-contenido.bg-white.mb-4(
          texto="Your child hardly ever eats vegetables."
          :audio="require('@/assets/curso/audio/4.1/9.mp3')"
          @audio-hover="mostrarIndicadorTarjetaAudio = false"
        )     
        p(data-aos="fade-down").mb-4 Tu hijo casi nunca come vegetales.

      .tarjeta.color-acento-contenido.p-3(x="50%" y="98%" numero="+")
        .h5.mb-2.text-center #[i Never]
        p.text-center Expresar que algo no ha sucedido en ninguna ocasión.
        TarjetaAudio.color-acento-contenido.bg-white.mb-4(
          texto="I’ve never gone to that city."
          :audio="require('@/assets/curso/audio/4.1/10.mp3')"
          @audio-hover="mostrarIndicadorTarjetaAudio = false"
        )     
        p(data-aos="fade-down").mb-4 Nunca he ido a esa ciudad.

    Separador 
    #t_4_2.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 4.2   Reglas para ubicar el adverbio de frecuencia en la oración

    p(data-aos="fade-down").mb-5 Son reglas bastante sencillas las que hay que seguir para ubicar un adverbio en la oración, porque no debe colocarse en cualquier lugar. En general, va a depender del verbo que se está utilizando en la frase u oración. Revise cada una de las reglas de los adverbios de frecuencia: 

    .row.justify-content-center.align-items-center
      .col-lg-4 
        img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img66.png', alt='')       

      .col-lg-8.bg24.p-5.bradius(data-aos="fade-left")    
        SlyderA(tipo="b").pt-5.px-3.bg-white.bradius.pb-2
          .row.justify-content-center.align-items-center
            .col-11
              h5.r Delante del verbo
              p En el caso de los adverbios de frecuencia, se colocan delante del verbo. Su estructura es la siguiente:
              p 
                span #[b Sujeto] 
                span + 
                span.blu #[b Adverbio ]
                span + 
                span.pur #[b Verbo principal ]
                span + 
                span.r #[b Complemento ]

              h5.text-center #[i For example]
              .row.justify-content-center.align-items-center
                .col-lg-4 
                  img.img-a.img-t(src='@/assets/curso/temas/img68.png', alt='')               
                .col-lg-6           
                  TarjetaAudio.color-acento-contenido.bg-white.mb-3(
                    texto="Mary never eats meat."
                    :audio="require('@/assets/curso/audio/4.2/1.mp3')"
                    @audio-hover="mostrarIndicadorTarjetaAudio = false"
                  )            
                  p.mb-0  Mary nunca come carne.
                  
          .row.justify-content-center.align-items-center
            .col-11
              h5.r Después del verbo to be
              p Si el adverbio de frecuencia está acompañando al verbo to be, se colocará después de este. 

              h5.text-center #[i For example]
              .row.justify-content-center.align-items-center.mb-4
                .col-lg-4 
                  img.img-a.img-t(src='@/assets/curso/temas/img69.png', alt='')               
                .col-lg-6            
                  TarjetaAudio.color-acento-contenido.bg-white.mb-3(
                    texto="Carmen is always smiling."
                    :audio="require('@/assets/curso/audio/4.2/2.mp3')"
                    @audio-hover="mostrarIndicadorTarjetaAudio = false"
                  )            
                  p.mb-0  Carmen está siempre sonriente. 
              .row.justify-content-center.align-items-center
                .col-lg-4 
                  img.img-a.img-t(src='@/assets/curso/temas/img70.png', alt='')               
                .col-lg-6            
                  TarjetaAudio.color-acento-contenido.bg-white.mb-3(
                    texto="Bill was never on time."
                    :audio="require('@/assets/curso/audio/4.2/3.mp3')"
                    @audio-hover="mostrarIndicadorTarjetaAudio = false"
                  )            
                  p.mb-0  Bill nunca estaba a tiempo.

          .row.justify-content-center.align-items-center
            .col-11
              h5.r Delante del verbo principal
              p Si el adverbio está acompañando a un verbo modal u otro auxiliar, se incluye delante del verbo principal.

              h5.text-center #[i For example]
              .row.justify-content-center.align-items-center.mb-4
                .col-lg-4 
                  img.img-a.img-t(src='@/assets/curso/temas/img71.png', alt='')               
                .col-lg-6            
                  TarjetaAudio.color-acento-contenido.bg-white.mb-3(
                    texto="Carol has never seen the sea."
                    :audio="require('@/assets/curso/audio/4.2/4.mp3')"
                    @audio-hover="mostrarIndicadorTarjetaAudio = false"
                  )            
                  p.mb-0  Carol nunca ha visto el mar.

          .row.justify-content-center.align-items-center
            .col-11
              h5.r Adverbios al principio 
              p En cuanto a los adverbios de frecuencia: usually, frequently, sometimes, often y occasionally, debe señalarse que #[b pueden ser ubicados al principio o al final de la frase u oración.]

              h5.text-center #[i For example]
              .row.justify-content-center.align-items-center.mb-4
                .col-lg-4 
                  img.img-a.img-t(src='@/assets/curso/temas/img72.png', alt='')               
                .col-lg-6            
                  TarjetaAudio.color-acento-contenido.bg-white.mb-3(
                    texto="Sometimes, I get up very late. -  I get up very late, sometimes."
                    :audio="require('@/assets/curso/audio/4.2/5.mp3')"
                    @audio-hover="mostrarIndicadorTarjetaAudio = false"
                  )            
                  p.mb-0 A veces, me levanto muy tarde. -  Me levanto muy tarde, a veces.
    p(data-aos="fade-down").my-5 Existen, además, ciertas expresiones que permiten expresar una frecuencia que generalmente se traduce como “de vez en cuando”. Estas expresiones son:
    .row.justify-content-center.mb-5.g-3(data-aos="zoom-in-up")
      .col-lg-4.mb-lg-0.mb-3
        .tarjeta.tarjeta-ribbon.bgcard1.p-3.h-100
          .tarjeta-ribbon_texto.p-2
            h4.mb-0.text-white From time to time
          .p-3
            img.img-a.img-t.mb-4(data-aos="zoom-in")(src='@/assets/curso/temas/img73.svg', alt='')
            TarjetaAudio.color-acento-contenido.bg-white.mb-3(
              texto="From time to time, I go to my parent’s house. "
              :audio="require('@/assets/curso/audio/4.2/6.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )            
            p(data-aos="fade-down") De vez en cuando, yo voy a la casa de mis padres.

      .col-lg-4.mb-lg-0.mb-3
        .tarjeta.tarjeta-ribbon.bgcard1.p-3.h-100
          .tarjeta-ribbon_texto.p-2
            h4.mb-0.text-white Once in a while
          .p-3
            img.img-a.img-t.mb-4(data-aos="zoom-in")(src='@/assets/curso/temas/img74.svg', alt='')
            TarjetaAudio.color-acento-contenido.bg-white.mb-3(
              texto="Once in a while, I call you at work"
              :audio="require('@/assets/curso/audio/4.2/7.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )            
            p(data-aos="fade-down") De vez en cuando, yo te llamo al trabajo.

      .col-lg-4.mb-lg-0.mb-3
        .tarjeta.tarjeta-ribbon.bgcard1.p-3.h-100
          .tarjeta-ribbon_texto.p-2
            h4.mb-0.text-white Every now and then
          .p-3
            img.img-a.img-t.mb-4(data-aos="zoom-in")(src='@/assets/curso/temas/img75.svg', alt='')
            TarjetaAudio.color-acento-contenido.bg-white.mb-3(
              texto="Every now and then, you sing in the shower."
              :audio="require('@/assets/curso/audio/4.2/8.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )            
            p(data-aos="fade-down") De vez en cuando, cantas en la ducha.

    p(data-aos="fade-down").mb-5 Además, se presentan otras expresiones de frecuencia, como: every day, monthly, once, twice a week, every month, entre otras. De allí que puede preguntarse “How often” y utilizar la expresión de frecuencia requerida por la situación. Revise los diálogos:

    .row.justify-content-center.align-items-center
      .col-lg-4 
        img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img76.png', alt='')       

      .col-lg-8.bg25.p-5.bradius(data-aos="fade-left")    
        SlyderA(tipo="b").pt-5.px-3.bg-white.bradius.pb-2
          .row.justify-content-center.align-items-center
            .col-11
              .row.justify-content-center.align-items-center              
                .col-lg-6           
                  TarjetaAudio.color-acento-contenido.bg-white.mb-3(
                    texto="How often do you go to school? <br> I go to school every day."
                    :audio="require('@/assets/curso/audio/4.2/d/1.mp3')"
                    @audio-hover="mostrarIndicadorTarjetaAudio = false"
                  )            
                  p.mb-0 ¿Qué tan seguido vas a la escuela? <br> Yo voy a la escuela todos los días.
                .col-lg-4 
                  img.img-a.img-t(src='@/assets/curso/temas/img77.png', alt='')  
          .row.justify-content-center.align-items-center
            .col-11
              .row.justify-content-center.align-items-center              
                .col-lg-6           
                  TarjetaAudio.color-acento-contenido.bg-white.mb-3(
                    texto="How often does Mike go to the dentist? <br> Mike goes to the dentist once a year. "
                    :audio="require('@/assets/curso/audio/4.2/d/2.mp3')"
                    @audio-hover="mostrarIndicadorTarjetaAudio = false"
                  )            
                  p.mb-0 ¿Qué tan seguido va Mike al dentista? <br> Mike va al dentista una vez al año.
                .col-lg-4 
                  img.img-a.img-t(src='@/assets/curso/temas/img78.png', alt='')  
          .row.justify-content-center.align-items-center
            .col-11
              .row.justify-content-center.align-items-center              
                .col-lg-6           
                  TarjetaAudio.color-acento-contenido.bg-white.mb-3(
                    texto="How often does Sue eat meat? <br> Sue eats meat twice a week. "
                    :audio="require('@/assets/curso/audio/4.2/d/3.mp3')"
                    @audio-hover="mostrarIndicadorTarjetaAudio = false"
                  )            
                  p.mb-0 ¿Qué tan seguido Sue come carne? <br> Sue come carne dos veces a la semana.
                .col-lg-4 
                  img.img-a.img-t(src='@/assets/curso/temas/img79.png', alt='')  
          .row.justify-content-center.align-items-center
            .col-11
              .row.justify-content-center.align-items-center              
                .col-lg-6           
                  TarjetaAudio.color-acento-contenido.bg-white.mb-3(
                    texto="How often does Luis pay the phone bill? <br> Luis pays the phone bill monthly."
                    :audio="require('@/assets/curso/audio/4.2/d/4.mp3')"
                    @audio-hover="mostrarIndicadorTarjetaAudio = false"
                  )            
                  p.mb-0 ¿Qué tan seguido paga Luis la factura del teléfono? <br> Luis paga la factura del teléfono mensualmente.
                .col-lg-4 
                  img.img-a.img-t(src='@/assets/curso/temas/img80.png', alt='')                                                                                     
</template>

<script>
export default {
  name: 'Tema4',
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
