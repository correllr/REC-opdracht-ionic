<template>
  <ion-page>

    <ion-tabs>
      <ion-router-outlet></ion-router-outlet>
      <ion-tab-bar slot="bottom">
        <ion-tab-button tab="home" href="/tabs/home">
          <ion-icon aria-hidden="true" :icon="home" />
          <!-- <ion-label>Home</ion-label> -->
        </ion-tab-button>

        <ion-tab-button tab="tab1" href="/tabs/tab1">
          <ion-icon aria-label="Toegewezen Rapportages" :icon="documentText" />
          <!-- <ion-label>Toegewezen</ion-label> -->
        </ion-tab-button>

        <ion-tab-button tab="tab2" href="/tabs/tab2">
          <ion-icon aria-label="Uitgevoerd Rapportages" :icon="fileTrayFull" />
          <!-- <ion-label>Uitgevoerd</ion-label> -->
        </ion-tab-button>

        <ion-tab-button tab="tab3" href="/tabs/tab3">
          <ion-icon aria-label="Knowledgebase" :icon="book" />
          <!-- <ion-label>Knowledgebase</ion-label> -->
        </ion-tab-button>

        <ion-tab-button tab="tab4" href="/tabs/tab4">
          <ion-icon aria-label="Instellingen" :icon="settings" />
          <!-- <ion-label>Instellingen</ion-label> -->
        </ion-tab-button>
      </ion-tab-bar>
    </ion-tabs>
  </ion-page>
</template>

<script setup lang="ts">
import { IonTabBar, IonTabButton, IonTabs, IonIcon, IonPage, IonRouterOutlet } from '@ionic/vue';
import { book, fileTrayFull, documentText, settings, home } from 'ionicons/icons';


</script>
