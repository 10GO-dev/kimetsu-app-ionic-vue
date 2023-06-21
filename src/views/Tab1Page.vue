<template>
  <ion-page>
    <ion-list :fullscreen="true">
    
        <ion-item-group>
          <ion-item-divider>
            <ion-label class="title">Demon Slayer: (Kimetsu no Yaiba)</ion-label>
          </ion-item-divider>
          <ion-item lines="none">

            <swiper :autoplay="{ delay: 2000, disableOnInteraction: false }" :pagination="{ clickable: true }">
              <swiper-slide>
                <img src="https://sphinxanime.com/wp-content/uploads/2021/04/kimetsunoyaibawallpapersphinxanime.jpg" alt="kimetsu Image" />
              </swiper-slide>
              <swiper-slide>
                <img src="https://www.crunchyroll.com/imgsrv/display/thumbnail/1200x675/catalog/crunchyroll/6b5f4fc8c0a7bb5012b9c0930a46570f.jpe" alt="kimetsu Image" />
              </swiper-slide>
              <swiper-slide>
                <img src="https://static3.srcdn.com/wordpress/wp-content/uploads/2020/05/Demon-Slayer-Movie-2.jpg" alt="kimetsu Image" />
              </swiper-slide>
            </swiper>
          </ion-item>
          <ion-item lines="none"/>
          <ion-item lines="none">
            <ion-text> Es el Período Taisho en Japón. Tanjiro, un niño de buen corazón que vende carbón para ganarse la vida, encuentra a su familia asesinada por un demonio. Para empeorar las cosas, su hermana menor, Nezuko, la única superviviente, se ha transformado ella misma en un demonio.</ion-text>
          </ion-item>
          <ion-item lines="none"/>
        </ion-item-group>
        <ion-router-outlet>
        </ion-router-outlet>
          <a class="ion-padding" href="/tabs/tab2"><ion-icon :icon="arrowForward"></ion-icon>  Toca aquí para ver mas info.</a>
    </ion-list>
  </ion-page>
</template>

<script lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent, IonText, IonLabel,IonItem,IonItemGroup, IonItemDivider, IonList, IonIcon,IonRouterOutlet} from '@ionic/vue';
import { defineComponent } from 'vue';
import { Swiper, SwiperSlide } from 'swiper/vue';
import SwiperCore, { Autoplay, Pagination } from 'swiper';
import { arrowForward } from 'ionicons/icons';

// Import Swiper styles
import 'swiper/swiper-bundle.css';

// Import Ionic Swiper styles
import '@ionic/vue/css/ionic-swiper.css';

SwiperCore.use([Autoplay, Pagination]);

export default defineComponent({
  components: {
    IonPage,
    IonHeader,
    IonToolbar,
    IonTitle,
    IonContent,
    IonText,
    Swiper,
    SwiperSlide,
    IonLabel,
    IonItemGroup,
    IonItem,
    IonItemDivider,
    IonList,
    IonIcon,
    IonRouterOutlet,
},
 setup(){
  return { arrowForward}
 }
});
</script>

<style scoped>
.title {
  font-size: medium;
  
}

ion-item-divider {
  --background: #790000cb;
  --color: #fff;

  --padding-top: 10px;
  --padding-bottom: 10px;
  --padding-start: 20px;
  --padding-end: 20px;
}

ion-text{
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}
</style>
