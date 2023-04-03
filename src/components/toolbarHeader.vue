<template>
    <ion-toolbar>
        <ion-buttons slot="start">
          <ion-button fill="outline">
            <ion-icon slot="start" name="star"></ion-icon>
            Star
          </ion-button>
        </ion-buttons>
        <ion-buttons slot="end">
            <ion-button>
                <ion-icon slot="icon-only" :icon="camera"></ion-icon>
                <!-- <ion-label>Foto</ion-label> -->
            </ion-button>
          <ion-button>
            <ion-icon slot="icon-only" :icon="personCircle"></ion-icon>
            <!-- <ion-label>Log In</ion-label> -->
          </ion-button>
        </ion-buttons>
        <ion-title>Real Estate Care</ion-title>
        <ion-img src="" alt=""></ion-img>
      </ion-toolbar>
</template>

<script setup lang="ts">
    import { IonLabel, IonIcon, IonButton, IonPage, IonRouterOutlet } from '@ionic/vue';
    import { camera, personCircle } from 'ionicons/icons';

</script>

<style scoped>
ion-icon {
    color: white;
  }
    
</style>