<template>
    
      <ion-list lines="full">
        <ion-list-header>
            <ion-label>Toegewezen Rapportages</ion-label>
          </ion-list-header>
        <ion-item>
            <ion-label color="primary">
                Toegewezen Rapport een
            </ion-label>
            <ion-icon :icon=openIcon></ion-icon>
        </ion-item>
        <ion-item>
            <ion-label color="primary">
                Toegewezen Rapport twee
            </ion-label>
            <ion-icon :icon=openIcon></ion-icon>
        </ion-item>
        <ion-item>
            <ion-label color="primary">
                Toegewezen Rapport drie
            </ion-label>
            <ion-icon :icon=openIcon></ion-icon>
        </ion-item>
      </ion-list>
 
</template>
<script setup lang="ts">

import { IonList, IonItem, IonIcon, IonLabel, IonListHeader } from '@ionic/vue';
import { folderOpenOutline } from 'ionicons/icons';

const openIcon = folderOpenOutline;
</script>
<style scoped>
    ion-list-header {
        font-size: 120%;
    } 
    
</style>