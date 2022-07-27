<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Acciones cotidianas - <i>This is my day!</i>

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8
        p(data-aos="fade-down") En forma diaria, las personas realizan una serie de actividades en el hogar o en el trabajo, transformándose en rutinas, que pueden denominarse acciones cotidianas. Para describir estas actividades, se manejan ciertas estructuras y verbos que usualmente se utilizan para indicar cuáles son las acciones y cuándo o cómo se realizan.       
        .tarjeta.position-relative.rounded-0.bg1.p-3
          .row.justify-content-center.align-items-center
            .col-lg-2.col-5.mb-lg-0.mb-3
              .imagen-absolute
                img(data-aos='zoom-in-up')(src='@/assets/curso/temas/img1.png', alt='')
            .col-lg-10
              p(data-aos="fade-down").mb-0.p-2 Durante este primer tema, se presenta la rutina diaria de actividades en casa y la rutina diaria en el sitio de trabajo. Es importante que, al finalizar cada una, realice el ejercicio de sus propias rutinas.             
      .col-lg-4 
        img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img2.png', alt='')

    Separador 
    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 1.1  Reglas a cumplir con los conectores de secuencia
    p(data-aos="fade-down").mb-5 A continuación, se relaciona la rutina diaria, a través de una chica llamada Claire. Escuche cada audio, repita y memorice parte del vocabulario.
    .bg14
      PasosB.color-primario.mb-5(data-aos="fade-right")
        .row.justify-content-center.align-items-center.bg2.p-5.crd.crd--100(titulo="")
          .col-11
            .row.justify-content-center.align-items-center
              .col-lg-6
                img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img4.png', alt='')
              .col-lg-6.p-5
                .bgwhite.p-3
                  TraduccionAudio.color-primario(:dialogo="dialogo1")

        .row.justify-content-center.align-items-center.bg2.p-5.crd.crd--100(titulo="")
          .col-11
            .row.justify-content-center.align-items-center
              .col-lg-6
                img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img5.png', alt='')
              .col-lg-6.p-5
                .bgwhite.p-3
                  TraduccionAudio.color-primario(:dialogo="dialogo2")
        .row.justify-content-center.align-items-center.bg2.p-5.crd.crd--100(titulo="")
          .col-11
            .row.justify-content-center.align-items-center
              .col-lg-6.p-5
                .bgwhite.p-3
                  TraduccionAudio.color-primario(:dialogo="dialogo3")
              .col-lg-6
                img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img6.png', alt='')
        .row.justify-content-center.align-items-center.bg2.p-5.crd.crd--100(titulo="")
          .col-11
            .row.justify-content-center.align-items-center
              .col-lg-6
                img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img7.png', alt='')
              .col-lg-6.p-5
                .bgwhite.p-3
                  TraduccionAudio.color-primario(:dialogo="dialogo4")
        .row.justify-content-center.align-items-center.bg2.p-5.crd.crd--100(titulo="")
          .col-11
            .row.justify-content-center.align-items-center
              .col-lg-6.p-5
                .bgwhite.p-3
                  TraduccionAudio.color-primario(:dialogo="dialogo5")
              .col-lg-6
                img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img8.png', alt='')
        .row.justify-content-center.align-items-center.bg2.p-5.crd.crd--100(titulo="")
          .col-11
            .row.justify-content-center.align-items-center
              .col-lg-6
                img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img9.png', alt='')
              .col-lg-6.p-5
                .bgwhite.p-3
                  TraduccionAudio.color-primario(:dialogo="dialogo6")
        .row.justify-content-center.align-items-center.bg2.p-5.crd.crd--100(titulo="")
          .col-11
            .row.justify-content-center.align-items-center
              .col-lg-6.p-5
                .bgwhite.p-3
                  TraduccionAudio.color-primario(:dialogo="dialogo7")
              .col-lg-6
                img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img10.png', alt='') 

      p(data-aos="fade-down").mb-5 A partir de lo anterior, se presentan algunas preguntas, referidas a la rutina narrada anteriormente, con las posibles respuestas:
      .row.justify-content-center.align-items-center
        .col-lg-4
          img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img12.png', alt='') 

        .col-lg-8
          SlyderF(columnas="col-lg-6")(data-aos="fade-right")          
            .crd.crd--100.tarjeta.bg.bg--1
              TarjetaAudio.color-acento-contenido.bg-white.my-3.bot(
                texto="<i>What time does Claire wake up?</i>"
                :audio="require('@/assets/curso/audio/1/p/1.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
                a.boton.abot.color-acento-botones.indicador__container.text-white(@click="modal1 = true")
                  span #[b Answer]
                  .indicador--click(v-if="mostrarIndicador")
            .crd.crd--100.tarjeta.p-4.bg.bg--2
              TarjetaAudio.color-acento-contenido.bg-white.my-3.bot(
                texto="<i>What time does she get up? </i>"
                :audio="require('@/assets/curso/audio/1/p/2.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
                a.boton.abot.color-acento-botones.indicador__container.text-white(@click="modal2 = true")
                  span #[b Answer]
            .crd.crd--100.tarjeta.p-4.bg.bg--3
              TarjetaAudio.color-acento-contenido.bg-white.my-3.bot(
                texto="<i>What does she do when she gets up in the morning? </i>"
                :audio="require('@/assets/curso/audio/1/p/3.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
                a.boton.abot.color-acento-botones.indicador__container.text-white(@click="modal3 = true")
                  span #[b Answer]
            .crd.crd--100.tarjeta.p-4.bg.bg--4
              TarjetaAudio.color-acento-contenido.bg-white.my-3.bot(
                texto="<i>Who does prepare the breakfast?</i>"
                :audio="require('@/assets/curso/audio/1/p/4.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
                a.boton.abot.color-acento-botones.indicador__container.text-white(@click="modal4 = true")
                  span #[b Answer]
            .crd.crd--100.tarjeta.p-4.bg.bg--5
              TarjetaAudio.color-acento-contenido.bg-white.my-3.bot(
                texto="<i>What time does she eat breakfast?</i>"
                :audio="require('@/assets/curso/audio/1/p/5.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
                a.boton.abot.color-acento-botones.indicador__container.text-white(@click="modal5 = true")
                  span #[b Answer]
            .crd.crd--100.tarjeta.p-4.bg.bg--6
              TarjetaAudio.color-acento-contenido.bg-white.my-3.bot(
                texto="<i>What does she do after breakfast?</i>"
                :audio="require('@/assets/curso/audio/1/p/6.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
                a.boton.abot.color-acento-botones.indicador__container.text-white(@click="modal6 = true")
                  span #[b Answer]
            .crd.crd--100.tarjeta.p-4.bg.bg--7
              TarjetaAudio.color-acento-contenido.bg-white.my-3.bot(
                texto="<i>Does she like to prepare junk food?</i>"
                :audio="require('@/assets/curso/audio/1/p/7.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
                a.boton.abot.color-acento-botones.indicador__container.text-white(@click="modal7 = true")
                  span #[b Answer]
            .crd.crd--100.tarjeta.p-4.bg.bg--8
              TarjetaAudio.color-acento-contenido.bg-white.my-3.bot(
                texto="<i>Who does she have lunch with at noon?</i>"
                :audio="require('@/assets/curso/audio/1/p/8.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
                a.boton.abot.color-acento-botones.indicador__container.text-white(@click="modal8 = true")
                  span #[b Answer]
            .crd.crd--100.tarjeta.p-4.bg.bg--9
              TarjetaAudio.color-acento-contenido.bg-white.my-3.bot(
                texto="<i>What does she do in the afternoon?</i>"
                :audio="require('@/assets/curso/audio/1/p/9.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
                a.boton.abot.color-acento-botones.indicador__container.text-white(@click="modal9 = true")
                  span #[b Answer]
            .crd.crd--100.tarjeta.p-4.bg.bg--10
              TarjetaAudio.color-acento-contenido.bg-white.my-3.bot(
                texto="<i>What does she do on Saturday morning?</i>"
                :audio="require('@/assets/curso/audio/1/p/10.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
                a.boton.abot.color-acento-botones.indicador__container.text-white(@click="modal10 = true")
                  span #[b Answer]
            .crd.crd--100.tarjeta.p-4.bg.bg--11
              TarjetaAudio.color-acento-contenido.bg-white.my-3.bot(
                texto="<i>What time do they have dinner?</i>"
                :audio="require('@/assets/curso/audio/1/p/11.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
                a.boton.abot.color-acento-botones.indicador__container.text-white(@click="modal11 = true")
                  span #[b Answer]
            .crd.crd--100.tarjeta.p-4.bg.bg--12
              TarjetaAudio.color-acento-contenido.bg-white.my-3.bot(
                texto="<i>What do they do after dinner?</i>"
                :audio="require('@/assets/curso/audio/1/p/12.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
                a.boton.abot.color-acento-botones.indicador__container.text-white(@click="modal12 = true")
                  span #[b Answer]
            .crd.crd--100.tarjeta.p-4.bg.bg--13
              TarjetaAudio.color-acento-contenido.bg-white.my-3.bot(
                texto="<i>What time does she go to bed?</i>"
                :audio="require('@/assets/curso/audio/1/p/13.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
                a.boton.abot.color-acento-botones.indicador__container.text-white(@click="modal13 = true")
                  span #[b Answer]

      ModalA(:abrir-modal.sync="modal1")
        .row.justify-content-center.align-items-center
          .col-md-6
            TarjetaAudio.color-acento-contenido.bg-white.my-3(
              texto="<i>Every morning, Claire wakes up at 7:00. </i>"
              :audio="require('@/assets/curso/audio/1/p/1.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )
        
          .col-md-6
            img.img-a.img-t(src='@/assets/curso/temas/img11.png', alt='') 
      ModalA(:abrir-modal.sync="modal2")
        .row.justify-content-center.align-items-center
          .col-md-6
            TarjetaAudio.color-acento-contenido.bg-white.my-3(
              texto="<i>She gets up at 7:00.</i>"
              :audio="require('@/assets/curso/audio/1/p/2.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )
        
          .col-md-6
            img.img-a.img-t(src='@/assets/curso/temas/img13.png', alt='') 
      ModalA(:abrir-modal.sync="modal3")
        .row.justify-content-center.align-items-center
          .col-md-6
            TarjetaAudio.color-acento-contenido.bg-white.my-3(
              texto="<i>She goes to the bathroom, brushes her teeth, and takes a shower.</i>"
              :audio="require('@/assets/curso/audio/1/p/3.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )
        
          .col-md-6
            img.img-a.img-t(src='@/assets/curso/temas/img14.png', alt='') 
      ModalA(:abrir-modal.sync="modal4")
        .row.justify-content-center.align-items-center
          .col-md-6
            TarjetaAudio.color-acento-contenido.bg-white.my-3(
              texto="<i> Claire prepares breakfast.</i>"
              :audio="require('@/assets/curso/audio/1/p/4.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )
        
          .col-md-6
            img.img-a.img-t(src='@/assets/curso/temas/img15.png', alt='') 
      ModalA(:abrir-modal.sync="modal5")
        .row.justify-content-center.align-items-center
          .col-md-6
            TarjetaAudio.color-acento-contenido.bg-white.my-3(
              texto="<i>She eats breakfast at 8:00 a.m.</i>"
              :audio="require('@/assets/curso/audio/1/p/5.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )
        
          .col-md-6
            img.img-a.img-t(src='@/assets/curso/temas/img16.png', alt='')
      ModalA(:abrir-modal.sync="modal6")
        .row.justify-content-center.align-items-center
          .col-md-6
            TarjetaAudio.color-acento-contenido.bg-white.my-3(
              texto="<i>After breakfast, she washes the dishes, cleans the house and prepares the lunch.</i>"
              :audio="require('@/assets/curso/audio/1/p/6.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )
        
          .col-md-6
            img.img-a.img-t(src='@/assets/curso/temas/img17.png', alt='')
      ModalA(:abrir-modal.sync="modal7")
        .row.justify-content-center.align-items-center
          .col-md-6
            TarjetaAudio.color-acento-contenido.bg-white.my-3(
              texto="<i>No, she doesn’t like to prepare junk food. She likes to prepare healthy food.</i>"
              :audio="require('@/assets/curso/audio/1/p/7.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )
        
          .col-md-6
            img.img-a.img-t(src='@/assets/curso/temas/img18.png', alt='') 
      ModalA(:abrir-modal.sync="modal8")
        .row.justify-content-center.align-items-center
          .col-md-6
            TarjetaAudio.color-acento-contenido.bg-white.my-3(
              texto="<i>At noon, she has lunch with her family.</i>"
              :audio="require('@/assets/curso/audio/1/p/8.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )
        
          .col-md-6
            img.img-a.img-t(src='@/assets/curso/temas/img19.png', alt='')
      ModalA(:abrir-modal.sync="modal9")
        .row.justify-content-center.align-items-center
          .col-md-6
            TarjetaAudio.color-acento-contenido.bg-white.my-3(
              texto="<i>In the afternoon, she goes to the gym to exercise.</i>"
              :audio="require('@/assets/curso/audio/1/p/9.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )
        
          .col-md-6
            img.img-a.img-t(src='@/assets/curso/temas/img20.png', alt='')
      ModalA(:abrir-modal.sync="modal10")
        .row.justify-content-center.align-items-center
          .col-md-6
            TarjetaAudio.color-acento-contenido.bg-white.my-3(
              texto="<i>She goes to the laundry on Saturday morning.</i>"
              :audio="require('@/assets/curso/audio/1/p/10.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )
        
          .col-md-6
            img.img-a.img-t(src='@/assets/curso/temas/img21.png', alt='') 
      ModalA(:abrir-modal.sync="modal11")
        .row.justify-content-center.align-items-center
          .col-md-6
            TarjetaAudio.color-acento-contenido.bg-white.my-3(
              texto="<i>They have dinner at around 7:00 p.m.</i>"
              :audio="require('@/assets/curso/audio/1/p/11.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )
        
          .col-md-6
            img.img-a.img-t(src='@/assets/curso/temas/img22.png', alt='')
      ModalA(:abrir-modal.sync="modal12")
        .row.justify-content-center.align-items-center
          .col-md-6
            TarjetaAudio.color-acento-contenido.bg-white.my-3(
              texto="<i>After dinner, they watch TV until ten o’clock.</i>"
              :audio="require('@/assets/curso/audio/1/p/12.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )
        
          .col-md-6
            img.img-a.img-t(src='@/assets/curso/temas/img23.png', alt='') 
      ModalA(:abrir-modal.sync="modal13")
        .row.justify-content-center.align-items-center
          .col-md-6
            TarjetaAudio.color-acento-contenido.bg-white.my-3(
              texto="<i>She goes to bed at ten o’clock.</i>"
              :audio="require('@/assets/curso/audio/1/p/13.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )
        
          .col-md-6
            img.img-a.img-t(src='@/assets/curso/temas/img24.png', alt='') 

    .row.justify-content-center.align-items-end.my-5.pt-5
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

    Separador 
    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2 1.2   Rutina diaria de trabajo en la oficina 
    p(data-aos="fade-down").mb-5 Ahora, verá la rutina diaria de trabajo en la oficina a partir de un personaje llamado Frank. Lea, escuche y memorice el vocabulario para, enseguida, formalizar algunas preguntas orientadoras:  
    .bg15    
      PasosB.color-primario.mb-5(data-aos="fade-right")
        .row.justify-content-center.align-items-center.bg2.p-5.crd.crd--100(titulo="")
          .col-11
            .row.justify-content-center.align-items-center
              .col-lg-6
                img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img26.png', alt='')
              .col-lg-6.p-5
                .bgwhite.p-3
                  TraduccionAudio.color-primario(:dialogo="dialogo8") 
        .row.justify-content-center.align-items-center.bg2.p-5.crd.crd--100(titulo="")
          .col-11
            .row.justify-content-center.align-items-center
              .col-lg-6.p-5
                .bgwhite.p-3
                  TraduccionAudio.color-primario(:dialogo="dialogo9")
              .col-lg-6
                img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img27.png', alt='')
        .row.justify-content-center.align-items-center.bg2.p-5.crd.crd--100(titulo="")
          .col-11
            .row.justify-content-center.align-items-center
              .col-lg-6
                img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img28.png', alt='')
              .col-lg-6.p-5
                .bgwhite.p-3
                  TraduccionAudio.color-primario(:dialogo="dialogo10") 
        .row.justify-content-center.align-items-center.bg2.p-5.crd.crd--100(titulo="")
          .col-11
            .row.justify-content-center.align-items-center
              .col-lg-6.p-5
                .bgwhite.p-3
                  TraduccionAudio.color-primario(:dialogo="dialogo11")
              .col-lg-6
                img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img29.png', alt='')
        .row.justify-content-center.align-items-center.bg2.p-5.crd.crd--100(titulo="")
          .col-11
            .row.justify-content-center.align-items-center
              .col-lg-6
                img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img30.png', alt='')
              .col-lg-6.p-5
                .bgwhite.p-3
                  TraduccionAudio.color-primario(:dialogo="dialogo12") 
        .row.justify-content-center.align-items-center.bg2.p-5.crd.crd--100(titulo="")
          .col-11
            .row.justify-content-center.align-items-center
              .col-lg-6.p-5
                .bgwhite.p-3
                  TraduccionAudio.color-primario(:dialogo="dialogo13")
              .col-lg-6
                img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img31.png', alt='')
        .row.justify-content-center.align-items-center.bg2.p-5.crd.crd--100(titulo="")
          .col-11
            .row.justify-content-center.align-items-center
              .col-lg-6
                img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img32.png', alt='')
              .col-lg-6.p-5
                .bgwhite.p-3
                  TraduccionAudio.color-primario(:dialogo="dialogo14") 
        .row.justify-content-center.align-items-center.bg2.p-5.crd.crd--100(titulo="")
          .col-11
            .row.justify-content-center.align-items-center
              .col-lg-6.p-5
                .bgwhite.p-3
                  TraduccionAudio.color-primario(:dialogo="dialogo15")
              .col-lg-6
                img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img33.png', alt='')

      .row.justify-content-center.align-items-center
        .col-lg-4
          img.img-a.img-t(data-aos="zoom-in")(src='@/assets/curso/temas/img34.png', alt='') 

        .col-lg-8
          SlyderF(columnas="col-lg-6")(data-aos="fade-right")          
            .crd.crd--100.tarjeta.bg.bg--14
              TarjetaAudio.color-acento-contenido.bg-white.my-3.bot(
                texto="<i>What time does Frank wake up?</i>"
                :audio="require('@/assets/curso/audio/1.2/p/1.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
                a.boton.abot.color-acento-botones.indicador__container.text-white(@click="modal13 = true")
                  span #[b Answer]
                  .indicador--click(v-if="mostrarIndicador")
            .crd.crd--100.tarjeta.p-4.bg.bg--15
              TarjetaAudio.color-acento-contenido.bg-white.my-3.bot(
                texto="<i>What does he do when he gets up in the morning?</i>"
                :audio="require('@/assets/curso/audio/1.2/p/2.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
                a.boton.abot.color-acento-botones.indicador__container.text-white(@click="modal14 = true")
                  span #[b Answer]
            .crd.crd--100.tarjeta.p-4.bg.bg--16
              TarjetaAudio.color-acento-contenido.bg-white.my-3.bot(
                texto="<i>How does he go to work?</i>"
                :audio="require('@/assets/curso/audio/1.2/p/3.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
                a.boton.abot.color-acento-botones.indicador__container.text-white(@click="modal15 = true")
                  span #[b Answer]
            .crd.crd--100.tarjeta.p-4.bg.bg--17
              TarjetaAudio.color-acento-contenido.bg-white.my-3.bot(
                texto="<i>Where does Frank work?</i>"
                :audio="require('@/assets/curso/audio/1/p/4.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
                a.boton.abot.color-acento-botones.indicador__container.text-white(@click="modal16 = true")
                  span #[b Answer]
            .crd.crd--100.tarjeta.p-4.bg.bg--18
              TarjetaAudio.color-acento-contenido.bg-white.my-3.bot(
                texto="<i>What does he do in the office?</i>"
                :audio="require('@/assets/curso/audio/1.2/p/5.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
                a.boton.abot.color-acento-botones.indicador__container.text-white(@click="modal17 = true")
                  span #[b Answer]
            .crd.crd--100.tarjeta.p-4.bg.bg--19
              TarjetaAudio.color-acento-contenido.bg-white.my-3.bot(
                texto="<i>What time does Frank have lunch?</i>"
                :audio="require('@/assets/curso/audio/1.2/p/6.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
                a.boton.abot.color-acento-botones.indicador__container.text-white(@click="modal18 = true")
                  span #[b Answer]
            .crd.crd--100.tarjeta.p-4.bg.bg--20
              TarjetaAudio.color-acento-contenido.bg-white.my-3.bot(
                texto="<i>Where does Frank take lunch?</i>"
                :audio="require('@/assets/curso/audio/1.2/p/7.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
                a.boton.abot.color-acento-botones.indicador__container.text-white(@click="modal19 = true")
                  span #[b Answer]
            .crd.crd--100.tarjeta.p-4.bg.bg--21
              TarjetaAudio.color-acento-contenido.bg-white.my-3.bot(
                texto="<i>When does Frank get off work?</i>"
                :audio="require('@/assets/curso/audio/1.2/p/8.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
                a.boton.abot.color-acento-botones.indicador__container.text-white(@click="modal20 = true")
                  span #[b Answer]
            .crd.crd--100.tarjeta.p-4.bg.bg--22
              TarjetaAudio.color-acento-contenido.bg-white.my-3.bot(
                texto="<i>What does Frank do when he gets off work?</i>"
                :audio="require('@/assets/curso/audio/1.2/p/9.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
                a.boton.abot.color-acento-botones.indicador__container.text-white(@click="modal21 = true")
                  span #[b Answer]
            .crd.crd--100.tarjeta.p-4.bg.bg--23
              TarjetaAudio.color-acento-contenido.bg-white.my-3.bot(
                texto="<i>What does he do after that?</i>"
                :audio="require('@/assets/curso/audio/1.2/p/10.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
                a.boton.abot.color-acento-botones.indicador__container.text-white(@click="modal22 = true")
                  span #[b Answer]
            .crd.crd--100.tarjeta.p-4.bg.bg--24
              TarjetaAudio.color-acento-contenido.bg-white.my-3.bot(
                texto="<i>What time does Frank have dinner?</i>"
                :audio="require('@/assets/curso/audio/1.2/p/11.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
                a.boton.abot.color-acento-botones.indicador__container.text-white(@click="modal23 = true")
                  span #[b Answer]
            .crd.crd--100.tarjeta.p-4.bg.bg--25
              TarjetaAudio.color-acento-contenido.bg-white.my-3.bot(
                texto="<i>What time does Frank go to sleep?</i>"
                :audio="require('@/assets/curso/audio/1.2/p/12.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
                a.boton.abot.color-acento-botones.indicador__container.text-white(@click="modal24 = true")
                  span #[b Answer]

        ModalA(:abrir-modal.sync="modal13")
          .row.justify-content-center.align-items-center
            .col-md-6
              TarjetaAudio.color-acento-contenido.bg-white.my-3(
                texto="<i>Frank always wakes up at 6:00 o’clock in the morning.</i>"
                :audio="require('@/assets/curso/audio/1.2/p/1.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
          
            .col-md-6
              img.img-a.img-t(src='@/assets/curso/temas/img11.png', alt='') 
        ModalA(:abrir-modal.sync="modal14")
          .row.justify-content-center.align-items-center
            .col-md-6
              TarjetaAudio.color-acento-contenido.bg-white.my-3(
                texto="<i>He takes a shower and puts his clothes on. He doesn’t have breakfast.</i>"
                :audio="require('@/assets/curso/audio/1.2/p/2.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
          
            .col-md-6
              img.img-a.img-t(src='@/assets/curso/temas/img13.png', alt='') 
        ModalA(:abrir-modal.sync="modal15")
          .row.justify-content-center.align-items-center
            .col-md-6
              TarjetaAudio.color-acento-contenido.bg-white.my-3(
                texto="<i>He goes to work by bus.</i>"
                :audio="require('@/assets/curso/audio/1.2/p/3.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
          
            .col-md-6
              img.img-a.img-t(src='@/assets/curso/temas/img14.png', alt='') 
        ModalA(:abrir-modal.sync="modal16")
          .row.justify-content-center.align-items-center
            .col-md-6
              TarjetaAudio.color-acento-contenido.bg-white.my-3(
                texto="<i>He works in an office.</i>"
                :audio="require('@/assets/curso/audio/1.2/p/4.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
          
            .col-md-6
              img.img-a.img-t(src='@/assets/curso/temas/img15.png', alt='') 
        ModalA(:abrir-modal.sync="modal17")
          .row.justify-content-center.align-items-center
            .col-md-6
              TarjetaAudio.color-acento-contenido.bg-white.my-3(
                texto="<i>There, he writes letters and he must sort files and puts them in their folders.</i>"
                :audio="require('@/assets/curso/audio/1.2/p/5.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
          
            .col-md-6
              img.img-a.img-t(src='@/assets/curso/temas/img16.png', alt='')
        ModalA(:abrir-modal.sync="modal18")
          .row.justify-content-center.align-items-center
            .col-md-6
              TarjetaAudio.color-acento-contenido.bg-white.my-3(
                texto="<i>He has lunch at noon.</i>"
                :audio="require('@/assets/curso/audio/1.2/p/6.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
          
            .col-md-6
              img.img-a.img-t(src='@/assets/curso/temas/img17.png', alt='')
        ModalA(:abrir-modal.sync="modal19")
          .row.justify-content-center.align-items-center
            .col-md-6
              TarjetaAudio.color-acento-contenido.bg-white.my-3(
                texto="<i>He has lunch in the cafeteria with his colleagues.</i>"
                :audio="require('@/assets/curso/audio/1.2/p/7.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
          
            .col-md-6
              img.img-a.img-t(src='@/assets/curso/temas/img18.png', alt='') 
        ModalA(:abrir-modal.sync="modal20")
          .row.justify-content-center.align-items-center
            .col-md-6
              TarjetaAudio.color-acento-contenido.bg-white.my-3(
                texto="<i>Frank gets off work at 4:00 p.m.</i>"
                :audio="require('@/assets/curso/audio/1.2/p/8.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
          
            .col-md-6
              img.img-a.img-t(src='@/assets/curso/temas/img19.png', alt='')
        ModalA(:abrir-modal.sync="modal21")
          .row.justify-content-center.align-items-center
            .col-md-6
              TarjetaAudio.color-acento-contenido.bg-white.my-3(
                texto="<i>He meets his friends at the corner bar and drinks some beers there.</i>"
                :audio="require('@/assets/curso/audio/1.2/p/9.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
          
            .col-md-6
              img.img-a.img-t(src='@/assets/curso/temas/img20.png', alt='')
        ModalA(:abrir-modal.sync="modal22")
          .row.justify-content-center.align-items-center
            .col-md-6
              TarjetaAudio.color-acento-contenido.bg-white.my-3(
                texto="<i>He goes back his home.</i>"
                :audio="require('@/assets/curso/audio/1.2/p/10.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
          
            .col-md-6
              img.img-a.img-t(src='@/assets/curso/temas/img21.png', alt='') 
        ModalA(:abrir-modal.sync="modal23")
          .row.justify-content-center.align-items-center
            .col-md-6
              TarjetaAudio.color-acento-contenido.bg-white.my-3(
                texto="<i>He has dinner around 8:00 p.m.</i>"
                :audio="require('@/assets/curso/audio/1.2/p/11.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
          
            .col-md-6
              img.img-a.img-t(src='@/assets/curso/temas/img22.png', alt='')
        ModalA(:abrir-modal.sync="modal24")
          .row.justify-content-center.align-items-center
            .col-md-6
              TarjetaAudio.color-acento-contenido.bg-white.my-3(
                texto="<i>Frank goes to sleep around 11:00 p.m., after watching some movies on Netflix</i>"
                :audio="require('@/assets/curso/audio/1.2/p/12.mp3')"
                @audio-hover="mostrarIndicadorTarjetaAudio = false"
              )
          
            .col-md-6
              img.img-a.img-t(src='@/assets/curso/temas/img23.png', alt='')

</template>

<script>
import TraduccionAudio from '../components/TraduccionAudio.vue'
export default {
  name: 'Tema1',
  components: {
    TraduccionAudio,
  },
  data: () => ({
    mostrarIndicador: true,
    modal1: false,
    modal2: false,
    modal3: false,
    modal4: false,
    modal5: false,
    modal6: false,
    modal7: false,
    modal8: false,
    modal9: false,
    modal10: false,
    modal11: false,
    modal12: false,
    modal13: false,
    modal14: false,
    modal15: false,
    modal16: false,
    modal17: false,
    modal18: false,
    modal19: false,
    modal20: false,
    modal21: false,
    modal22: false,
    modal23: false,
    modal24: false,

    dialogo1: [
      {
        textoIng:
          'My name is Claire. Every morning I wake up at 7:00, I get up and go to the bathroom, brush my teeth and take a shower. ',
        textoEsp:
          'Mi nombre es Claire. Cada mañana, me despierto a las 7:00, me levanto y voy al baño, cepillo mis dientes y me baño.',
        audio: require('@/assets/curso/audio/1/1.mp3'),
      },
    ],
    dialogo2: [
      {
        textoIng:
          'After that, I get dressed and go down stairs to prepare breakfast. I eat breakfast at 8:00 a.m.',
        textoEsp:
          'MDespués, me visto y voy abajo a preparar el desayuno. Yo tomo el desayuno a las 8:00 a.m.',
        audio: require('@/assets/curso/audio/1/2.mp3'),
      },
    ],
    dialogo3: [
      {
        textoIng:
          'After breakfast, I wash the dishes, clean the house and prepare the lunch. I like to prepare healthy food.',
        textoEsp:
          'Después del desayuno, lavo los platos, limpio la casa y preparo el almuerzo. Me gusta preparar comida saludable.',
        audio: require('@/assets/curso/audio/1/3.mp3'),
      },
    ],
    dialogo4: [
      {
        textoIng: 'At noon, I have lunch with my family.',
        textoEsp: 'Al mediodía, almuerzo con mi familia. ',
        audio: require('@/assets/curso/audio/1/4.mp3'),
      },
    ],
    dialogo5: [
      {
        textoIng:
          'In the afternoon, I go to the gym to exercise. Then I walk and go home.',
        textoEsp:
          'En la tarde, voy al gimnasio a hacer ejercicio. Luego, camino y voy a casa.',
        audio: require('@/assets/curso/audio/1/5.mp3'),
      },
    ],
    dialogo6: [
      {
        textoIng: 'On Saturday morning,  I go to the laundry. ',
        textoEsp: 'Los sábados en la mañana, voy a la lavandería.',
        audio: require('@/assets/curso/audio/1/6.mp3'),
      },
    ],
    dialogo7: [
      {
        textoIng:
          'We have dinner at around 7:00 p.m and then we watch TV until ten o’clock. At that time, we go to bed.',
        textoEsp:
          'Cenamos a eso de las 7:00 p.m. y luego vemos la tele hasta las diez. A esa hora, nos vamos a la cama.',
        audio: require('@/assets/curso/audio/1/7.mp3'),
      },
    ],
    dialogo8: [
      {
        textoIng:
          'My name is Frank. I always wake up at 6:00 o’clock in the morning.',
        textoEsp:
          ' Mi nombre es Frank. Siempre me despierto a las 6:00 en punto de la mañana.',
        audio: require('@/assets/curso/audio/1.2/1.mp3'),
      },
    ],
    dialogo9: [
      {
        textoIng:
          'Then, I take a shower and put my clothes on. I don’t have breakfast',
        textoEsp: 'Luego, me baño y me pongo la ropa. No desayuno.',
        audio: require('@/assets/curso/audio/1.2/2.mp3'),
      },
    ],
    dialogo10: [
      {
        textoIng: 'I go to work by bus. I work in an office.',
        textoEsp: 'Voy al trabajo en autobús. Yo trabajo en una oficina.',
        audio: require('@/assets/curso/audio/1.2/3.mp3'),
      },
    ],
    dialogo11: [
      {
        textoIng:
          'There, I write letters, then I must sort files and put them in their folders.',
        textoEsp:
          'Allí, escribo cartas, luego debo ordenar archivos y guardarlos en sus carpetas.',
        audio: require('@/assets/curso/audio/1.2/4.mp3'),
      },
    ],
    dialogo12: [
      {
        textoIng: 'At noon, I have lunch in the cafeteria with my colleagues.',
        textoEsp: 'Al mediodía, almuerzo en la cafetería con mis compañeros.',
        audio: require('@/assets/curso/audio/1.2/5.mp3'),
      },
    ],
    dialogo13: [
      {
        textoIng:
          'I get off work at 4:00 p.m. and meet my friends at the corner bar. We have some beers there.',
        textoEsp:
          'Salgo de trabajar a las 4:00 p.m. y me reúno con mis amigos en el bar de la esquina. Allí tomamos unas cervezas.',
        audio: require('@/assets/curso/audio/1.2/6.mp3'),
      },
    ],
    dialogo14: [
      {
        textoIng: 'Then, I go back home. I have dinner around 8:00 p.m.',
        textoEsp: 'Luego, regreso a casa. Ceno a eso de las 8:00 p.m.',
        audio: require('@/assets/curso/audio/1.2/7.mp3'),
      },
    ],
    dialogo15: [
      {
        textoIng:
          'I go to sleep around 11:00 p.m., after watching some movies on Netflix.',
        textoEsp:
          ' Me voy a dormir a eso de las 11:00 p.m., luego de ver algunas películas en Netflix.',
        audio: require('@/assets/curso/audio/1.2/8.mp3'),
      },
    ],
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
