<template>
    <ion-toolbar color="light">
        <ion-buttons slot="start">
          <ion-button href="/tabs/home">
            <ion-icon src="@/../assets/logoBW.svg" slot="start"></ion-icon>
            <ion-label class="mainFont">Real Estate Care</ion-label>
          </ion-button>
        </ion-buttons>
        
        <ion-buttons slot="end">
            <ion-button>
                <ion-icon slot="icon-only" :icon="camera"></ion-icon>
            </ion-button>
          <ion-button>
            <ion-icon slot="icon-only" :icon="personCircle"></ion-icon>    
          </ion-button>
        </ion-buttons>
      </ion-toolbar>
</template>

<script setup lang="ts">
    import { IonIcon, IonButtons, IonButton, IonToolbar, IonLabel } from '@ionic/vue';
    import { camera, personCircle } from 'ionicons/icons';
    
    const imgUrl = "@/../assets/logoblackTransparent.png";

</script>

<style scoped>
 ion-button {
  font-size: 1.6rem;
 }

 .mainFont {
  text-transform: none;
  font-size: 1.8rem;
 }
</style>