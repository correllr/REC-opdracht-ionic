<template>
    
    <ion-list  lines="full">
      <ion-item>
          <ion-label color="primary">
              Uitgevoerd Rapport een
          </ion-label>
          <ion-icon :icon=openIcon color="light"></ion-icon>
      </ion-item>
      <ion-item>
          <ion-label color="primary">
            Uitgevoerd Rapport twee
          </ion-label>
          <ion-icon :icon=openIcon color="light"></ion-icon>
      </ion-item>
      <ion-item>
          <ion-label color="primary">
            Uitgevoerd Rapport drie
          </ion-label>
          <ion-icon :icon=openIcon  color="light"></ion-icon>
      </ion-item>
    </ion-list>

</template>
<script setup lang="ts">

import { IonList, IonItem, IonIcon, IonLabel } from '@ionic/vue';
import { downloadOutline } from 'ionicons/icons';

const openIcon = downloadOutline;
</script>
<style scoped>
ion-item {
    --background: var(--gradient);
}
</style>