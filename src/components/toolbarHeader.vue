<template>
    <ion-toolbar>
        <ion-buttons slot="start">
          
            <ion-img :src=imgUrl alt="logo" id="headerLogo"></ion-img>
     
        </ion-buttons>
        <!-- <ion-title color="primary">
          <h1>
            Real Estate Care
          </h1>
          
        </ion-title> -->
        
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
        
       
      </ion-toolbar>
</template>

<script setup lang="ts">
    import { IonIcon, IonButtons, IonButton, IonTitle, IonToolbar, IonImg } from '@ionic/vue';
    import { camera, personCircle } from 'ionicons/icons';
    
    const imgUrl = "@/../assets/logoblackTransparent.png";

</script>

<style scoped>
  ion-toolbar {
    --background: var(--gradient);
  }

  #headerLogo {
    width: 75px;
  }

  h1 {
    text-align: center;
    text-shadow: 0 0 1px white;
  }

  ion-icon {
    color: white;
  }
    
</style>