<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title class="ion-title-left">Demon Slayer: (Kimetsu no Yaiba)</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content>
      <ion-accordion-group>
        <ion-accordion value="first">
          <ion-item slot="header" color="light">
            <ion-label>Personajes</ion-label>
          </ion-item>
          <div class="ion-padding" slot="content">
            <ion-accordion-group expand="compact">
              <ion-accordion value="fisrt" :toggle-icon="caretDownCircle" toggle-icon-slot="end">
                <ion-item slot="header" color="light">
                  <ion-thumbnail slot="start">
                    <img alt="Silhouette of mountains" src="../../assets/Images/Tanjiro_Anime_Profile.jpg" />
                  </ion-thumbnail>
                  <ion-label>Tanjiro Kamado</ion-label>
                </ion-item>
                <div class="ion-padding" slot="content">
                  <ion-img
                    src="https://preview.redd.it/made-this-thing-v0-x10h5v7yt55b1.jpg?width=799&format=pjpg&auto=webp&v=enabled&s=b188e5d2d05a32a5b7d7ec93b51009ed84518956"></ion-img>
                  <p><strong>Tanjiro Kamado</strong>
                    (竈門かまど 炭たん治じ郎ろう, Kamado Tanjirō?) es el protagonista principal de Kimetsu no Yaiba. Es un cazador de
                    Demonios cuyo principal objetivo es encontrar al responsable de haber matado a su familia y convertido
                    a su hermana Nezuko en una Demonio y luego juró derrotar a Muzan Kibutsuji, el Rey de los Demonios,
                    para evitar que otros sufran el mismo destino que él.

                    Antes de convertirse en un Cazador de Demonios, Tanjiro era un quemador de carbón antes de que Muzan
                    matara a toda su familia mientras que su hermana menor, Nezuko, se convirtió en una demonio.</p>

                  <a href="https://kimetsu-no-yaiba.fandom.com/es/wiki/Tanjiro_Kamado">Toca aquí para ver mas info en la
                    web</a>
                </div>
              </ion-accordion>
              <ion-accordion value="second" :toggle-icon="caretDownCircle" toggle-icon-slot="end">
                <ion-item slot="header" color="light">
                  <ion-thumbnail slot="start">
                    <img alt="Silhouette of mountains" src="../../assets/Images/Kyojuro_Anime_Profile.jpg" />
                  </ion-thumbnail>
                  <ion-label>Kyojuro Rengoku</ion-label>
                </ion-item>
                <div class="ion-padding" slot="content">
                  <ion-img
                    src="https://static.wikia.nocookie.net/kimetsu-no-yaiba/images/f/fd/Kyojuro_anime.png"></ion-img>
                  <p><strong>Kyojuro Rengoku</strong>
                    (煉れん獄ごく 杏きょう寿じゅ郎ろう, Rengoku Kyōjurō)
                    <br />
                    Fue un cazador de Demonios y el Pilar de la Llama (炎えん柱ばしら, En Bashira?). del Cuerpo de Exterminio de
                    Demonios.
                  </p>

                  <a href="https://kimetsu-no-yaiba.fandom.com/es/wiki/Kyojuro_Rengoku">Toca aquí para ver mas info en la
                    web</a>
                </div>
              </ion-accordion>
              <ion-accordion value="third" :toggle-icon="caretDownCircle" toggle-icon-slot="end">
                <ion-item slot="header" color="light">
                  <ion-thumbnail slot="start">
                    <img alt="Silhouette of mountains" src="../../assets/Images/Zenitsu_Anime_Profile.jpg" />
                  </ion-thumbnail>
                  <ion-label>Zenitsu Agatsuma</ion-label>
                </ion-item>
                <div class="ion-padding" slot="content">
                  <ion-img
                    src="https://static.wikia.nocookie.net/kimetsu-no-yaiba/images/6/66/Zenitsu_anime.png"></ion-img>
                  <p><strong>Zenitsu Agatsuma</strong>
                    (我あが妻つま善ぜん逸いつ, Agatsuma Zen'itsu?) es un Cazador de Demonios y un compañero de viaje de Tanjiro
                    Kamado. A su vez es uno de los personajes principales de Kimetsu no Yaiba.
                  </p>

                  <a href="https://kimetsu-no-yaiba.fandom.com/es/wiki/Zenitsu_Agatsuma">Toca aquí para ver mas info en la
                    web</a>
                </div>
              </ion-accordion>
            </ion-accordion-group>
          </div>
        </ion-accordion>
        <ion-accordion value="second">
          <ion-item slot="header" color="light">
            <ion-label>Momentos</ion-label>
          </ion-item>
          <div class="ion-padding" slot="content">
            <ion-accordion-group>
              <ion-accordion value="fisrt">
                <ion-item slot="header" color="light">
                  <ion-label>Kyojuro vs Akaza</ion-label>
                </ion-item>
                <div class="ion-padding" slot="content">
                  <iframe src="https://www.youtube.com/embed/rk_FqgkVFdM" width="100%" height="315" frameborder="0"
                    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                    allowfullscreen></iframe>
                </div>
              </ion-accordion>
              <ion-accordion value="second">
                <ion-item slot="header" color="light">
                  <ion-label>Tanjiro vs Rui</ion-label>
                </ion-item>
                <div class="ion-padding" slot="content">
                  <iframe src="https://www.youtube.com/embed/wCmLTL_kRCE" width="100%" height="315" frameborder="0"
                    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                    allowfullscreen></iframe>
                </div>
              </ion-accordion>
              <ion-accordion value="third">
                <ion-item slot="header" color="light">
                  <ion-label>Tanjiro vs Hantengu</ion-label>
                </ion-item>
                <div class="ion-padding" slot="content">
                  <iframe src="https://www.youtube.com/embed/nDcrZ9lETCI" width="100%" height="315" frameborder="0"
                    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                    allowfullscreen></iframe>
                </div>
              </ion-accordion>
            </ion-accordion-group>
          </div>
        </ion-accordion>
        <ion-accordion value="third">
          <ion-item slot="header" color="light">
            <ion-label>En mi vida</ion-label>
          </ion-item>
          <div class="ion-padding" slot="content">
                <h2>¿Por qué me gusta?</h2>
               
                <p>Transmite varios mensajes significativos para la vida. A continuación, te presento algunos de los
                  mensajes clave que se pueden extraer de la serie:</p>
  
                <h3>Determinación y perseverancia:</h3>
                <p>Demon Slayer muestra la importancia de tener determinación y perseverancia en la vida. Los personajes
                  principales, como Tanjiro Kamado, enfrentan numerosos desafíos y obstáculos, pero siguen adelante con
                  valentía y nunca se rinden. Este mensaje nos recuerda la importancia de superar las dificultades y nunca
                  perder la esperanza.</p>
  
                <h3>La importancia de los lazos familiares y de amistad:</h3>
                <p>La serie resalta el valor de los lazos familiares y de amistad. Tanjiro tiene una fuerte conexión con
                  su hermana Nezuko y se esfuerza por protegerla. Además, a medida que avanza la historia, se forma un
                  equipo de cazadores de demonios que desarrollan una profunda amistad y se apoyan mutuamente en momentos
                  difíciles. Demon Slayer nos enseña que tener personas cercanas en nuestras vidas puede brindarnos fuerza
                  y apoyo.</p>
  
                <h3>Empatía y compasión:</h3>
                <p>A lo largo del anime, Tanjiro muestra una gran empatía y compasión hacia los demonios que se encuentran
                  en su camino. En lugar de simplemente exterminarlos, intenta comprender su dolor y sufrimiento, buscando
                  una solución pacífica siempre que sea posible. Este mensaje nos insta a tratar de entender a los demás y
                  a no juzgar rápidamente, fomentando la compasión y la empatía hacia los demás.</p>
  
                <h3>Superación personal:</h3>
                <p>Demon Slayer resalta la importancia de la superación personal y el crecimiento. Los personajes se
                  enfrentan a sus propios miedos, limitaciones y debilidades, y a medida que avanzan en su viaje, se
                  vuelven más fuertes tanto física como emocionalmente. Esto nos inspira a enfrentar nuestros propios
                  desafíos y trabajar para mejorar constantemente.</p>
                  
          </div>
        </ion-accordion>
      </ion-accordion-group>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import {
  IonPage,
  IonToolbar,
  IonContent,
  IonAccordion,
  IonItemGroup,
  IonAccordionGroup,
  IonHeader,
  IonItem,
  IonTitle,
  IonLabel,
  IonItemDivider,
  IonImg,
  IonThumbnail,
  IonCard,
  IonCardContent,
  IonCardHeader,
  IonCardTitle,
  IonText,
} from "@ionic/vue";

import { caretDownCircle } from "ionicons/icons";
import { defineComponent } from "vue";

export default defineComponent({
  components: {
    IonItemGroup,
    IonToolbar,
    IonContent,
    IonPage,
    IonAccordion,
    IonThumbnail,
    IonAccordionGroup,
    IonItem,
    IonLabel,
    IonItemDivider,
    IonHeader,
    IonTitle,
    IonImg,
    IonCard,
    IonCardContent,
    IonCardHeader,
    IonCardTitle,
    IonText,
  },
  setup() {
    return { caretDownCircle };
  },
});
</script>
<style scoped>
ion-toolbar {
  --background: #790000cb;
  --color: #fff;
  --padding-top: 10px;
  --padding-bottom: 10px;
  --padding-start: 20px;
  --padding-end: 20px;
  --text-align: left;
}

.ion-title-left {
  text-align: left;
}

ion-img {
  width: 150px;
}</style>
