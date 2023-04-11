<template>
    
    <ion-list  lines="full">
      <ion-list-header>
        <ion-label>Uitgevoerd Rapportages</ion-label>
      </ion-list-header>
      <ion-item>
          <ion-label color="primary">
              Uitgevoerd Rapport een
          </ion-label>
          <ion-icon :icon=openIcon></ion-icon>
      </ion-item>
      <ion-item>
          <ion-label color="primary">
            Uitgevoerd Rapport twee
          </ion-label>
          <ion-icon :icon=openIcon></ion-icon>
      </ion-item>
      <ion-item>
          <ion-label color="primary">
            Uitgevoerd Rapport drie
          </ion-label>
          <ion-icon :icon=openIcon></ion-icon>
      </ion-item>
    </ion-list>

</template>
<script setup lang="ts">

import { IonList, IonItem, IonIcon, IonLabel, IonListHeader } from '@ionic/vue';
import { downloadOutline } from 'ionicons/icons';

const openIcon = downloadOutline;
</script>
<style scoped>
  ion-list-header {
    font-size: 120%;
  }
</style>