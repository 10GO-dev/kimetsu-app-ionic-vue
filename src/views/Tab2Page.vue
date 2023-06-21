<template>
  <ion-page>
    
    <ion-accordion-group :fullscreen="true">
    <ion-header>
            <ion-label class="title">Demon Slayer: (Kimetsu no Yaiba)</ion-label>
    </ion-header>
    <ion-accordion value="first">
      <ion-item slot="header" color="light">
        <ion-label>First Accordion</ion-label>
      </ion-item>
      <div class="ion-padding" slot="content">First Content</div>
    </ion-accordion>
    <ion-accordion value="second">
      <ion-item slot="header" color="light">
        <ion-label>Second Accordion</ion-label>
      </ion-item>
      <div class="ion-padding" slot="content">Second Content</div>
    </ion-accordion>
    <ion-accordion value="third">
      <ion-item slot="header" color="light">
        <ion-label>Third Accordion</ion-label>
      </ion-item>
      <div class="ion-padding" slot="content">Third Content</div>
    </ion-accordion>
  </ion-accordion-group>
  </ion-page>
</template>

<script lang="ts">
  import { IonPage, IonAccordion, IonAccordionGroup, IonItem, IonLabel,IonItemDivider } from '@ionic/vue';
  import { defineComponent } from 'vue';

  export default defineComponent({
    components: {
      IonPage,
      IonAccordion,
      IonAccordionGroup,
      IonItem,
      IonLabel,
      IonItemDivider
    },
  });
</script>
<style scoped>

ion-item-divider {
  --background: #790000cb;
  --color: #fff;
  
  --padding-top: 10px;
  --padding-bottom: 10px;
  --padding-start: 20px;
  --padding-end: 20px;
}

</style>