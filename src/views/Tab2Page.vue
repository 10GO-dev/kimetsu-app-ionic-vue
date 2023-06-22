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
                  <ion-img src="https://preview.redd.it/made-this-thing-v0-x10h5v7yt55b1.jpg?width=799&format=pjpg&auto=webp&v=enabled&s=b188e5d2d05a32a5b7d7ec93b51009ed84518956"></ion-img>
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
                  <ion-img src="https://static.wikia.nocookie.net/kimetsu-no-yaiba/images/f/fd/Kyojuro_anime.png"></ion-img>
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
                  <ion-img src="https://static.wikia.nocookie.net/kimetsu-no-yaiba/images/6/66/Zenitsu_anime.png"></ion-img>
                  <p><strong>Zenitsu Agatsuma</strong>
                    (我あが妻つま善ぜん逸いつ, Agatsuma Zen'itsu?) es un Cazador de Demonios y un compañero de viaje de Tanjiro Kamado. A su vez es uno de los personajes principales de Kimetsu no Yaiba.
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
              <ion-accordion>
                <ion-item slot="header" color="light">
                  <ion-label>Tanjiro Kamado</ion-label>
                </ion-item>
              </ion-accordion>
            </ion-accordion-group>
          </div>
        </ion-accordion>
        <ion-accordion value="third">
          <ion-item slot="header" color="light">
            <ion-label>En mi vida</ion-label>
          </ion-item>
          <div class="ion-padding" slot="content">Third Content</div>
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
  IonThumbnail
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
}
</style>
