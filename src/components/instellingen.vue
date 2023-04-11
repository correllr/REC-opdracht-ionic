<template>
    
    <ion-list lines="full">
        <ion-list-header>
            <ion-label>Instellingen</ion-label>
        </ion-list-header>
        
            <ion-item>
                <ion-avatar slot="start">
                    <ion-icon :icon="personCircle" size="large"></ion-icon>
                </ion-avatar>
                <ion-label color="primary">Set foto</ion-label>
                <!-- <ion-icon :icon=openIcon size="large"></ion-icon> -->
            </ion-item>
            <ion-item>
                <ion-label color="primary">
                    Wachtwoord
                </ion-label>
                <!-- <ion-icon :icon=openIcon size="large"></ion-icon> -->
            </ion-item>
        
            <ion-item>
                <ion-label color="primary">
                    <ion-toggle justify="start">Enable Dark mode</ion-toggle>Light/Dark mode
                </ion-label>
                <!-- <ion-icon :icon=openIcon size="large"></ion-icon> -->
            </ion-item>
            
            <ion-item>
                <ion-label color="primary">
                    Meldingen
                </ion-label>
                <!-- <ion-icon :icon=openIcon size="large"></ion-icon> -->
            </ion-item>
        
       
    </ion-list>

</template>
<script setup lang="ts">

import { IonList, IonItem, IonIcon, IonLabel, IonListHeader, IonAvatar, IonToggle } from '@ionic/vue';
import { folderOpenOutline, personCircle } from 'ionicons/icons';

const openIcon = folderOpenOutline;
</script>
<style scoped>
  
  
</style>