<template>
    
    <ion-list lines="full">
        <ion-list-header>
            <ion-label>Knowledgebase</ion-label>
        </ion-list-header>
        <ion-item-group>
            <ion-item-divider>
                <ion-label>Top List</ion-label>
            </ion-item-divider>
            <ion-item>
                <ion-label color="primary">
                    Een artikel
                </ion-label>
                <!-- <ion-icon :icon=openIcon size="large"></ion-icon> -->
            </ion-item>
            <ion-item>
                <ion-label color="primary">
                    Andere artikel
                </ion-label>
                <!-- <ion-icon :icon=openIcon size="large"></ion-icon> -->
            </ion-item>
        </ion-item-group>
        <ion-item-group>
            <ion-item-divider>
                <ion-label>Bottom List</ion-label>
            </ion-item-divider>
            <ion-item>
                <ion-label color="primary">
                    Derde artikel met een langere titel
                </ion-label>
                <!-- <ion-icon :icon=openIcon size="large"></ion-icon> -->
            </ion-item>
            <ion-item>
                <ion-label color="primary">
                    Nog een vierde artikel met een nog langere titel
                </ion-label>
                <!-- <ion-icon :icon=openIcon size="large"></ion-icon> -->
            </ion-item>
            <ion-item>
                <ion-label color="primary">
                    Laatste artikel
                </ion-label>
                <!-- <ion-icon :icon=openIcon size="large"></ion-icon> -->
            </ion-item>
        </ion-item-group>
    </ion-list>

</template>
<script setup lang="ts">

import { IonList, IonItem, IonIcon, IonLabel, IonListHeader, IonItemDivider, IonItemGroup } from '@ionic/vue';
import { folderOpenOutline } from 'ionicons/icons';

const openIcon = folderOpenOutline;
</script>
<style scoped>
    ion-list-header {
        font-size: 120%;
    }

    ion-item-divider {
        font-size: 120%;
    }
  
</style>