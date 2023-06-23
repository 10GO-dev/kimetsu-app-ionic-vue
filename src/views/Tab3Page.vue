<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Tu Perfil de GitHub</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content>
      <ion-tabs>
        <ion-tab-bar slot="top">
          <ion-tab-button tab="profile">
            <ion-label>Perfil</ion-label>
          </ion-tab-button>
          <ion-tab-button tab="repositories">
            <ion-label>Repositorios</ion-label>
          </ion-tab-button>
        </ion-tab-bar>
        <ion-tab tab="profile">
          <ion-content>
            <!-- Contenido del perfil -->
            <iframe src="https://github.com/TU_USUARIO" width="100%" height="100%" frameborder="0"></iframe>
          </ion-content>
        </ion-tab>
        <ion-tab tab="repositories">
          <ion-content>
            <!-- Contenido de los repositorios -->
            <iframe src="https://github.com/TU_USUARIO?tab=repositories" width="100%" height="100%" frameborder="0"></iframe>
          </ion-content>
        </ion-tab>
      </ion-tabs>
    </ion-content>
  </ion-page>
</template>


<script lang="ts">
import { 
  IonPage, IonHeader, IonToolbar, IonTitle, IonContent,
  IonTabs, IonTabBar, IonTabButton, IonLabel, IonIcon 
} from '@ionic/vue';
import { home, book, informationCircle } from 'ionicons/icons';
export default {
  components: { IonPage, IonHeader, IonToolbar, IonTitle, IonContent, IonTabs, IonTabBar, IonTabButton, IonLabel, IonIcon },
  setup() {
    return {
      home, book, informationCircle
    }
  }
}
</script>
