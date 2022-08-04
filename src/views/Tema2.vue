<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Estructura gramatical del presente simple y presente progresivo
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-5
        img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img47.png', alt='')

      .col-lg-7
        .bg16.p-3(data-aos="flip-down").mb-4
          p(data-aos="fade-down").mb-0 Como se ha visto anteriormente, en inglés, el tiempo presente simple y presente progresivo de los verbos son bastante fáciles de utilizar, dado que se usan para hablar de la actualidad.
        p(data-aos="fade-down") Cabe resaltar que el presente simple se utiliza para hablar de acciones actuales, que no están limitadas a un momento específico; mientras que el presente progresivo (o continuo) enfatiza el desarrollo de la acción, es decir, indica que la acción se está desarrollando en ese momento en que se está especificando. Revise, en ambos tiempos, cada una de sus formas:

    TabsB.color-acento-botones.mb-5(data-aos="zoom-in")
      .py-4.py-md-5(titulo="Presente simple / <i>Simple present</i>" :icono="require('@/assets/curso/temas/img49.png')")
        .row.justify-content-center.align-items-center
          .col-11 
            .row.justify-content-center.align-items-center
              .col-lg-3
                img.img-a.img-t(src='@/assets/curso/temas/img48.png', alt='')
              .col-lg-9.bgwhite.p-4
                p.pur #[b Presente simple / #[i Simple present]]
 
                p Mediante la forma afirmativa, se habla de acciones que se realizan habitualmente. Una oración en forma afirmativa posee la siguiente estructura básica: 

                p
                  span.pur #[b Sujeto ]
                  span + 
                  span.r #[b Verbo principal ]
                  span + 
                  span.blu #[b Complemento ]
 
                p La forma del presente es muy parecida a la forma básica o verbo en infinitivo. En general, para los verbos regulares, la única diferencia es que se añade una -s a la forma básica en la tercera persona del singular (#[i he, she, it]). Por ejemplo:
                .row.justify-content-center.align-items-center
                  .col-lg-4
                    TarjetaAudio.color-acento-contenido.bg-white.mb-4(
                      texto="Marco takes the bus."
                      :audio="require('@/assets/curso/audio/2/1.mp3')"
                      @audio-hover="mostrarIndicadorTarjetaAudio = false"
                    )     
                    p.text-center Marco toma el autobús.
                  .col-lg-4
                    TarjetaAudio.color-acento-contenido.bg-white.mb-4(
                      texto="Celine sings very well."
                      :audio="require('@/assets/curso/audio/2/2.mp3')"
                      @audio-hover="mostrarIndicadorTarjetaAudio = false"
                    )     
                    p.text-center Celine canta muy bien. 
                  .col-lg-4
                    TarjetaAudio.color-acento-contenido.bg-white.mb-4(
                      texto="Mario walks in the park."
                      :audio="require('@/assets/curso/audio/2/3.mp3')"
                      @audio-hover="mostrarIndicadorTarjetaAudio = false"
                    )     
                    p.text-center Mario camina en el parque.

      .py-4.py-md-5(titulo="Presente continuo / <i>Present continuous</i>" :icono="require('@/assets/curso/temas/img51.png')")
        .row.justify-content-center.align-items-center
          .col-11 
            .row.justify-content-center.align-items-center
              .col-lg-3
                img.img-a.img-t(src='@/assets/curso/temas/img50.png', alt='')
              .col-lg-9.bgwhite.p-4
                p.pur #[b Presente continuo / #[i Present continuous]]
 
                p El presente continuo tiene una estructura donde se utiliza el verbo “to be” conjugado, como auxiliar, y se le añade el gerundio del verbo principal de la oración. La estructura del presente continuo utiliza la siguiente fórmula:

                p
                  span.pur #[b Sujeto ]
                  span + 
                  span.r #[b  verbo to be conjugado ]
                  span + 
                  span.pur2 #[b gerundio del verbo principal ]                  
                  span + 
                  span.blu #[b Complemento (si hay) ]
 
                p En cuanto al gerundio del verbo principal, debe indicarse que el mismo se forma con la forma básica del verbo principal, a la que se añade la terminación -ing. Como ejemplo, en presente continuo, se tiene:
                .row.justify-content-center.align-items-center
                  .col-lg-4
                    TarjetaAudio.color-acento-contenido.bg-white.mb-4(
                      texto="Marco is taking the bus."
                      :audio="require('@/assets/curso/audio/2/4.mp3')"
                      @audio-hover="mostrarIndicadorTarjetaAudio = false"
                    )     
                    p Marco está tomando el autobús.
                  .col-lg-4
                    TarjetaAudio.color-acento-contenido.bg-white.mb-4(
                      texto="They are singing very well."
                      :audio="require('@/assets/curso/audio/2/5.mp3')"
                      @audio-hover="mostrarIndicadorTarjetaAudio = false"
                    )     
                    p Ellos están cantando muy bien.
                  .col-lg-4
                    TarjetaAudio.color-acento-contenido.bg-white.mb-4(
                      texto="You are walking in the park."
                      :audio="require('@/assets/curso/audio/2/6.mp3')"
                      @audio-hover="mostrarIndicadorTarjetaAudio = false"
                    )     
                    p Tú estás caminando en el parque.                   

    Separador 
    #t_2_1.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 2.1  Forma afirmativa 
    .tarjeta.position-relative.rounded-0.bg17.p-3.mb-5
      .row.justify-content-center.align-items-center
        .col-lg-2.col-5.mb-lg-0.mb-3
          .imagen-absolute1
            img(data-aos='zoom-in-up')(src='@/assets/curso/temas/img52.png', alt='')
        .col-lg-10
          p(data-aos="fade-down").mb-0.p-3 Los tiempos presente simple y presente continuo pueden ser confundidos debido a ciertas similitudes que existen, dado que para hablar de una acción que están efectuando ahora se podría pensar en el uso del presente simple, pero el tiempo que se utiliza para esto es el presente continuo. Revise la forma afirmativa con el verbo <i>to talk</i> / hablar:

    TabsC.color-acento-botones.mb-5(data-aos="fade-left")
      .py-3.py-md-4(titulo="<i>Affirmative Simple Present</i>")
        .row.justify-content-center.align-items-center.p-3
          .col-lg-8     
            .tabla1.color-acento-botones
              table.text-center.w-100
                tbody
                  tr.bgt1header
                    td.t1br #[b Persona gramatical del sujeto]
                    td.t1br #[b Conjugación del Verbo]
                    td.t1br #[b Complemento]
                    td #[b Traducción]
                  tr
                    td(colspan='4') #[b Singular]

                  tr
                    td 1<sup>a</sup> persona: <i>I</i>
                    td.fst-italic talk
                    td.fst-italic with the teacher.
                    td Yo hablo con el profesor.
                  tr
                    td 2<sup>a</sup> persona: <i>You</i>
                    td.fst-italic talk
                    td.fst-italic with the teacher.
                    td Tú hablas con el profesor.
                  tr
                    td 3<sup>a</sup> persona: <i>He/She</i>
                    td.fst-italic talks
                    td.fst-italic with the teacher.
                    td Él/ella habla con el profesor.
                  tr
                    td(colspan='4') #[b Plural]
                  tr
                    td 1<sup>a</sup> persona: <i>We</i>
                    td.fst-italic talk
                    td.fst-italic with the teacher.
                    td Nosotros hablamos con el profesor.
                  tr
                    td 2<sup>a</sup> persona: <i>You</i>
                    td.fst-italic talk
                    td.fst-italic with the teacher.
                    td Ustedes hablan con el profesor.   
                  tr
                    td 3<sup>a</sup> persona: <i>They</i>
                    td.fst-italic talk
                    td.fst-italic with the teacher.
                    td Ellos/ellas  hablan con el profesor.                                 
        
          .col-lg-4 
            img.img-a.img-t(src='@/assets/curso/temas/img53.png', alt='')

      .py-3.py-md-4(titulo="<i>Affirmative Present Continuous</i>")
        .row.justify-content-center.align-items-center.p-3
          .col-lg-10     
            .tabla1.color-acento-botones
              table.text-center.w-100
                tbody
                  tr.bgt1header
                    td.t1br #[b Persona gramatical del sujeto]
                    td.t1br #[b V. Aux (#[i to be])]                    
                    td.t1br #[b Verbo principal (gerundio)]
                    td.t1br #[b Complemento]
                    td #[b Traducción]
                  tr
                    td(colspan='5') #[b Singular]

                  tr
                    td 1<sup>a</sup> persona: <i>I</i>
                    td.fst-italic Am 
                    td.fst-italic talking          
                    td.fst-italic with the teacher.
                    td Yo estoy hablando con el profesor.
                  tr
                    td 2<sup>a</sup> persona: <i>You</i>
                    td.fst-italic Are
                    td.fst-italic talking           
                    td.fst-italic with the teacher.
                    td Tú estás hablando con el profesor.
                  tr
                    td 3<sup>a</sup> persona: <i>He/She</i>
                    td.fst-italic Is 
                    td.fst-italic talking          
                    td.fst-italic with the teacher.
                    td Él/ella está hablando con el profesor.
                  tr
                    td(colspan='5') #[b Plural]
                  tr
                    td 1<sup>a</sup> persona: <i>We</i>
                    td.fst-italic Are
                    td.fst-italic talking           
                    td.fst-italic with the teacher.
                    td Nosotros estamos hablando con el profesor.
                  tr
                    td 2<sup>a</sup> persona: <i>You</i>
                    td.fst-italic Are
                    td.fst-italic talking           
                    td.fst-italic with the teacher.
                    td Ustedes están hablando con el profesor.   
                  tr
                    td 3<sup>a</sup> persona: <i>They</i>
                    td.fst-italic Are
                    td.fst-italic talking           
                    td.fst-italic with the teacher.
                    td Ellos/ellas  están hablando con el profesor.

    Separador 
    #t_2_2.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 2.2   Forma negativa

    p(data-aos="fade-down") Mediante la forma negativa, se habla de acciones que no se realizan habitualmente. Una oración en forma negativa posee la siguiente estructura básica y se conjuga de la siguiente manera:

    h5(data-aos="fade-down").r Sujeto + Verbo auxiliar + Negación + Verbo principal + Complemento

    img.img-a.img-t.my-5(data-aos="flip-down")(src='@/assets/curso/temas/img54.png', alt='')

    TabsC.color-acento-botones.mb-5(data-aos="fade-left")
      .py-3.py-md-4.bg18(titulo="<i>Negative Simple Present</i>")
        .row.justify-content-center.align-items-center.p-3
          .col-lg-10     
            .tabla1.color-acento-botones
              table.text-center.w-100
                tbody
                  tr.bgt1header
                    td.t1br #[b Persona gramatical del sujeto]
                    td.t1br #[b V. Aux (#[i to do])]
                    td.t1br #[b Negación]
                    td.t1br #[b Verbo principal] 
                    td.t1br #[b Complemento]
                    td #[b Traducción]
                  tr
                    td(colspan='6') #[b Singular]

                  tr
                    td 1<sup>a</sup> persona: <i>I</i>
                    td.fst-italic do
                    td.fst-italic not               
                    td.fst-italic talk                  
                    td.fst-italic with the teacher.
                    td Yo no hablo con el profesor.
                  tr
                    td 2<sup>a</sup> persona: <i>You</i>
                    td.fst-italic do
                    td.fst-italic not                
                    td.fst-italic talk                   
                    td.fst-italic with the teacher.
                    td Tú no hablas con el profesor.
                  tr
                    td 3<sup>a</sup> persona: <i>He/She</i>
                    td.fst-italic does
                    td.fst-italic not               
                    td.fst-italic talk                  
                    td.fst-italic with the teacher.
                    td Él/ella no habla con el profesor.
                  tr
                    td(colspan='6') #[b Plural]
                  tr
                    td 1<sup>a</sup> persona: <i>We</i>
                    td.fst-italic do
                    td.fst-italic not
                    td.fst-italic talk                   
                    td.fst-italic with the teacher.
                    td Nosotros no hablamos con el profesor.
                  tr
                    td 2<sup>a</sup> persona: <i>You</i>
                    td.fst-italic do
                    td.fst-italic not
                    td.fst-italic talk                   
                    td.fst-italic with the teacher.
                    td Ustedes no hablan con el profesor.  
                  tr
                    td 3<sup>a</sup> persona: <i>They</i>
                    td.fst-italic do
                    td.fst-italic not
                    td.fst-italic talk                   
                    td.fst-italic with the teacher.
                    td Ellos/ellas  no hablan con el profesor.

      .py-3.py-md-4.bg18(titulo="<i>Negative Present Continuous</i>")
        .row.justify-content-center.align-items-center.p-3
          .col-lg-10     
            .tabla1.color-acento-botones
              table.text-center.w-100
                tbody
                  tr.bgt1header
                    td.t1br #[b Persona gramatical del sujeto]
                    td.t1br #[b V. Aux (#[i to be])]
                    td.t1br #[b Negación]
                    td.t1br #[b Verbo principal (gerundio)] 
                    td.t1br #[b Complemento]
                    td #[b Traducción]
                  tr
                    td(colspan='6') #[b Singular]

                  tr
                    td 1<sup>a</sup> persona: <i>I</i>
                    td.fst-italic am
                    td.fst-italic not               
                    td.fst-italic talking               
                    td.fst-italic with the teacher.
                    td Yo no estoy hablando con el profesor.
                  tr
                    td 2<sup>a</sup> persona: <i>You</i>
                    td.fst-italic are
                    td.fst-italic not                
                    td.fst-italic talking               
                    td.fst-italic with the teacher.
                    td Tú no estás hablando con el profesor.
                  tr
                    td 3<sup>a</sup> persona: <i>He/She</i>
                    td.fst-italic is
                    td.fst-italic not               
                    td.fst-italic talking    
                    td.fst-italic with the teacher.
                    td Él/ella no está hablando con el profesor.

                  tr
                    td(colspan='6') #[b Plural]
                  tr
                    td 1<sup>a</sup> persona: <i>We</i>
                    td.fst-italic are
                    td.fst-italic not
                    td.fst-italic talking  
                    td.fst-italic with the teacher.
                    td Nosotros no estamos hablando con el profesor.
                  tr
                    td 2<sup>a</sup> persona: <i>You</i>
                    td.fst-italic are
                    td.fst-italic not
                    td.fst-italic talking
                    td.fst-italic with the teacher.
                    td Ustedes no están hablando con el profesor.
                  tr
                    td 3<sup>a</sup> persona: <i>They</i>
                    td.fst-italic are
                    td.fst-italic not
                    td.fst-italic talking
                    td.fst-italic with the teacher.
                    td Ellos/ellas no están hablando con el profesor.

    Separador 
    #t_2_3.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 2.3  Forma interrogativa

    p(data-aos="fade-down") Mediante la forma interrogativa, se hace una pregunta referida a la acción del verbo principal. Una oración en forma interrogativa posee la siguiente estructura básica:

    h5(data-aos="fade-down").r Verbo Auxiliar + Sujeto + Verbo principal + Complemento + ?

    img.img-a.img-t.my-5(data-aos="flip-down")(src='@/assets/curso/temas/img55.png', alt='')

    TabsC.color-acento-botones.mb-5(data-aos="fade-left")
      .py-3.py-md-4(titulo="<i>Interrogative Simple Present</i>")
        .row.justify-content-center.align-items-center.p-3
          .col-lg-10     
            .tabla1.color-acento-botones
              table.text-center.w-100
                tbody
                  tr.bgt1header
                    td.t1br #[b Persona gramatical del sujeto]
                    td.t1br #[b V. Aux (#[i to do])]
                    td.t1br #[b Sujeto]
                    td.t1br #[b Verbo principal] 
                    td.t1br #[b Complemento]
                    td #[b Traducción]
                  tr
                    td(colspan='6') #[b Singular]

                  tr
                    td 1<sup>a</sup> persona: <i>I</i>
                    td.fst-italic Do
                    td.fst-italic I
                    td.fst-italic talk                  
                    td.fst-italic with the teacher?
                    td ¿Hablo yo con el profesor?
                  tr
                    td 2<sup>a</sup> persona: <i>You</i>
                    td.fst-italic Do
                    td.fst-italic you      
                    td.fst-italic talk                   
                    td.fst-italic with the teacher?
                    td ¿Hablas tú con el profesor?
                  tr
                    td 3<sup>a</sup> persona: <i>He/She</i>
                    td.fst-italic Does
                    td.fst-italic he/she             
                    td.fst-italic talk                  
                    td.fst-italic with the teacher?
                    td ¿Habla él/ella con el profesor?
                  tr
                    td(colspan='6') #[b Plural]
                  tr
                    td 1<sup>a</sup> persona: <i>We</i>
                    td.fst-italic Do
                    td.fst-italic we
                    td.fst-italic talk                   
                    td.fst-italic with the teacher?
                    td ¿Hablamos nosotros con el profesor?
                  tr
                    td 2<sup>a</sup> persona: <i>You</i>
                    td.fst-italic Do
                    td.fst-italic you
                    td.fst-italic talk                   
                    td.fst-italic with the teacher?
                    td ¿Hablan ustedes con el profesor?
                  tr
                    td 3<sup>a</sup> persona: <i>They</i>
                    td.fst-italic Do
                    td.fst-italic they
                    td.fst-italic talk                   
                    td.fst-italic with the teacher?
                    td ¿Hablan ellos/ellas con el profesor?

      .py-3.py-md-4(titulo="<i>Interrogative Present Continuous</i>")
        .row.justify-content-center.align-items-center.p-3
          .col-lg-10     
            .tabla1.color-acento-botones
              table.text-center.w-100
                tbody
                  tr.bgt1header
                    td.t1br #[b Persona gramatical del sujeto]
                    td.t1br #[b V. Aux (#[i to be])]
                    td.t1br #[b Sujeto]
                    td.t1br #[b V. principal (gerundio)] 
                    td.t1br #[b Complemento]
                    td #[b Traducción]
                  tr
                    td(colspan='6') #[b Singular]

                  tr
                    td 1<sup>a</sup> persona: <i>I</i>
                    td.fst-italic am
                    td.fst-italic I
                    td.fst-italic talking                  
                    td.fst-italic with the teacher?
                    td ¿Estoy yo hablando con el profesor?
                  tr
                    td 2<sup>a</sup> persona: <i>You</i>
                    td.fst-italic are
                    td.fst-italic you              
                    td.fst-italic talking                   
                    td.fst-italic with the teacher?
                    td ¿Estás tú hablando con el profesor?
                  tr
                    td 3<sup>a</sup> persona: <i>He/She</i>
                    td.fst-italic is
                    td.fst-italic He/She           
                    td.fst-italic talking                  
                    td.fst-italic with the teacher?
                    td ¿Está él/ella hablando con el profesor?
                  tr
                    td(colspan='6') #[b Plural]
                  tr
                    td 1<sup>a</sup> persona: <i>We</i>
                    td.fst-italic are
                    td.fst-italic we
                    td.fst-italic talking                   
                    td.fst-italic with the teacher?
                    td ¿Estamos nosotros hablando con el profesor?
                  tr
                    td 2<sup>a</sup> persona: <i>You</i>
                    td.fst-italic are
                    td.fst-italic you
                    td.fst-italic talking                   
                    td.fst-italic with the teacher?
                    td ¿Están ustedes hablando con el profesor?
                  tr
                    td 3<sup>a</sup> persona: <i>They</i>
                    td.fst-italic are
                    td.fst-italic they
                    td.fst-italic talking                   
                    td.fst-italic with the teacher?
                    td ¿Están ellos/ellas hablando con el profesor?
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
